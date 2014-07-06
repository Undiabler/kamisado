<h4>Камисадо - логическая, настольная игра в жанре стратегии.</h4>

<b>Как играть:</b><br/>
Как и в шахматах игрокам предлагается поле 8х8, но с разноцветными клетками.<br/>
Каждый игрок имеет 8 фишек (драконов) разного цвета.<br/>
Первыми ходят черные. Первый ход черные могут сделать любым цветом. Каждый последующий раз ходить можно только тем цветом на который походил противник. (т.е. противник походил на синюю клетку - вы ходите синей фишкой. Вы поставили свою фишку на зеленый цвет - противник должен ходить зеленым и т.д.)<br/>
Если цвет которым вы должны ходить - заблокирован, противник ходит снова тем цветом на котором стоит ваша заблокированная фишка.<br/>
Ходить можно только вперед и по диагоналям. Ходы вбок недопускаются. Перепрыгивать через фишки нельзя.<br/>
Выигрывает тот кто первым достигнет противоположного конца поля. <br/>

<b>О проекте:</b><br/>
Проект абсолютно бесплатный, без регистрации. Работает только в браузерах с поддержкой WebSockets.
В данном проекте я тренировался пользоваться сокетами в JS. Серверная часть написанна на Node.js. Она будет выложенна чуть позже. 

Реализованно сейчас:
	
	-	Защита от неправильных и подделаных данных
	-	Проверка доступности сервера
	-	Анимация движения
	-	Выиграш/проиграш
	-	Проверка на заблокированный ход
	-	Ходы по очереди определенными цветами
	-	Режим ожидания (поиск противника)

Необходимо реализовать:
	
	-	Чат
	-	Приглашение по прямой ссылке
	-	Проверка на патовую ситуацию (когда заблокированны обе стороны)
	-	Возможность переключение оформления сайта (светлый/черный)
	-	Страница/высплывающее окно правил игры

По всем вопросам и предложениям можно писать на мыло: <i>undiabler@gmail.com</i>
