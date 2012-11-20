Проект 2. Идея и интерфейс приложения
=============

Для начала небольшое отступление. Идея приложения, высказанная Рахимом в посвященной этой теме лекции показалась мне очень привлекательной. Я сам неоднократно пользуюсь таким способом, чтобы не забыть или пометить для себя какие-то важные вещи и часто ощущаю нехватку приложения, которое могло бы упростить задачу отправки участков текста к себе на почту.

Программа называется Send2ME

1. Программа предназначена для быстрой отправки участков текста на выбранный e-mail. В настройках необходимо указать свой личный e-mail, на который будет производиться отправка писем. Для расширения функционала программы предусмотреть возможность добавлять списки e-mail-ов для возможной отправки на один или несколько из них. 

2. Аудитория приложения - широкий круг пользователей, ценящих свое время :)

3. Идея программы в том, что можно, выделив участок текста и скопировав его в буфер обмена, быстро отправить его нужному адресату или себе. Такая фишка бывает очень удобна. Например читаешь текст и увидел что-то полезное. Чтобы не забыть - быстро отправляешь себе на почту. Или нашел что-то интересное и быстро отправляешь интересный участок своим знакомым.

4. При загрузке, приложение сворачивается в трей. По нажатию на иконку приложения в трее выпадает список с пунктами возможных действий: "отправить  мне", "отправить последним", "отправить выбранным", "настройки". Если буфер обмена пуст - активен только пункт "настройки". В настройках можно прописать свой e-mail, а также там будет возможность добавить дополнительные e-mail адреса в поле со списком. Возможно там еще будут какие-то необходимые настройки, необходимость в которых выплывет в процессе разработки. При непустом буфере обмена и нажатии "отправить мне" отправляется письмо с содержимым из буфера на email адрес, указанный в настройках как личный. При выборе "отправить последним" отправляется письмо по тем адресам, по которым было отправлено в прошлый раз. При выборе "отправить выбранным" - открывается панель с возможностью выбора нужных адресатов путем расстановки галочек возле соответствующих email адресов. Так же в этой панели должна быть кнопка "добавить email", нажатие по которой ведет в настройки в пункт, где можно добавлять, удалять, редактировать адреса.



PS: в идеале хотелось бы, чтобы программа при отправке определяла содержимое буфера. Если там html - то отправлять письмо в виде html, если plain text - то в виде обычного текста. Если же в буфере например файл - то чтобы отправлялось письмо с приаттаченным файлом. Но это в идеале :) Боюсь, что за время, которое будет отведено на разработку программы в рамках курса, можно и не успеть реализовать весь желаемый функционал. Тем более с нулевыми начальными знаниями object C