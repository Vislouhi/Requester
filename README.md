# Глас народа. Симбиоз месенджера и торрентов

ГЛАВНАЯ ЗАДАЧА ПРОГРАММЫ - РАСПРОСТРАНЕНИЕ ЛЮБОЙ

Слабые места социальных сетей в стране где есть цензура:
<li> Можно заблокировать ресурс
<li> Можно найти и посадить автора
<li> Можно требовать от площадки забанить пользователя
  
  Главное ограничение на распостранение информации, очевидно, накладывает небезосновательный страх людей быть репрессироваными.
  Эта система должна позволить безопасно распостранять любую информацию.
  
  Главная идеология взята из торрентов. Заключается она в том, что на сервере не храниться текстовых сообщений вообще. Сам сервер представляет из себя маленький набор кодов и может быть размещен одновременно на любом количестве площадок. Пользователь не имеет аккаунта т.к. наличия такового система не предусматривает. Чтобы идентифицировать пользователя необходимо отловить из сети кусок информации, расшифровать его, вычислить по IP его отправителя. Эта задачу практически реализовать черезвычайно сложно. При том, что если информация попала в поле зрения фашистов, то это означает, что эта информация многократно передавалась по сети хаотичным способом, обязательно с использованием VPN и анонимайзеров. На практике предъявить человеку какие-либо обвинения можно будет только изъяв у него телефон и найдя там программу. Но пока до этого дойдет можно будет успеть этой программой хорошо попользоваться.


![Image alt](https://github.com/vislouhi/Requester/raw/master/20180313_134406_0001.png)

Что храниться на телефоне?

В самой хардовой версии программы предполагается хранение всей информации в зашифрованном виде. Предусмотрено наличие двух паролей. При введении одного получаем доступ к сообщениям, при введении другого получаем запуск игры "сапер" и полное удаление данных. Пароль через сеть никогда не передается, так что узнать его практической возможности нет. Так же рассматривается вариант, что программа не имеет ключа для хранящихся в ее памяти данных. Прочитать данные можно один раз, при получении таковых от сервера. Когда пользователь добавляет текст в рассылку, он сохраняется на телефоне в зашифрованном виде без ключа доступа. И не доступен для чтения никогда.

На нижеследующей картинке показан принцип действия программы:

Программа отправляет на сервер список номеров имеющихся в ее базе сообщений. Сервер отправляет обратно те номера из полученных на которые есть запросы. Программа отсылает на сервер тексты сообщений, а сервер перенаправляет эти тексты пользователям не сохраняя их. Доставка сообщений будет происходить обычным гугловским сервисом GCM.

![Image alt](https://github.com/vislouhi/Requester/raw/master/20180311_184711_0001.png)

Следующая картинка иллюстрирует как приложение формирует запрос на доставку сообщений. Программа отправляет список номеров прочитанных сообщений на сервер и отправляет свой номер в гугловской службе сообщений. Этот номер заносится в базу данных к тем номерам сообщений которых нет у порльзователя.
![Image alt](https://github.com/vislouhi/Requester/raw/master/20180313_133507_0001.png)
![Image alt](https://github.com/vislouhi/Requester/raw/master/20180313_133806_0001.png)




https://ru.files.fm/u/znmfjcqm
