<center><image src="https://github.com/evgenkarlson/ALL_SCHOOL_42/raw/master/03_Norme____(%D0%9D%D0%BE%D1%80%D0%BC%D1%8B_%D0%B8_%D0%9F%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0_%D0%A8%D0%BA%D0%BE%D0%BB%D1%8B)/src/page1image3852832-small-13.png"></center>
</br>
<center><h2>Системное и сетевое администрирование</h1></center>
</br>
<center><h2>init</h2></center>
</br>
<center><i>Резюме: Введение в Системное и Cетевое Администрирование</i></center>
</br>
</br>
</br>

# Глава I.

## Предисловие

</br>

Хотите верьте, хотите нет, но этот проект зародился в ночной запой. Да, верно, когда мы решили запустить эти предметы и это посвящение, мы были совершенно никакие.

В штаб-квартире `Slash16` [Желтая Безумная Обезьяна](https://www.yellowmadmonkey.com/), после того как все в команде выпили много бутылок, среди которых три "Grey Goose", один "Absolut", два "Jäger" и один семилетний "Havana Club" (об этом стоит упомянуть), мы придумали отличную идею - создать несколько вводных тем о системном и сетевом администрировании.

Так что, конечно, мы не писали тогда там темы, хотя даже если бы, на самом деле, мы могли бы, то все бы мы в конечном итоге все равно напились, так что это была плохая идея ...

В любом случае, после такой долгой работы с кальяном, свежими мохито и хорошим плейлистом [Trace Urban VocalTeknix](https://youtu.be/W0l81iYp6n4?list=PL8kREmwZBbARsIwdgZLVRcI8quzIIoySp), чтобы поднять нам настроение, здесь - наконец - мы предоставляем вам наш результат!

Надеемся, вам понравится, и не забывайте, что это только начало!

Поцелуи и шоколадки,

Команда `Slash16`.


</br>
</br>
</br>

# Глава II. 

## Цели

Этот первый проект, `init`, даст вам возможность познакомиться с основными командами системы и сети, многими службами, используемыми на сервере, а также некоторыми идеями сценариев, которые могут быть полезны системным администраторам на ежедневной основе.


</br>
</br>
</br>

# Глава III. 

## Основные инструкции

Вы должны использовать команды терминала только для выполнения всех упражнений по этому предмету.

В этом проекте есть три типа вопросов. Вы можете определить тип ожидаемого ответа с помощью цветового кода:

:blue_heart: Синим цветом - команда 

:green_heart: Зеленым цветом - вывод команды 

:heart: Красным цветом - вычет, написанный вашими словами 

   - Создайте папку для каждой части этой темы в корне вашего репозитория. Эти папки должны называться `network`, `system` и `scripts`. Запишите свои ответы в файл, названный в честь номера вопроса, состоящего из двух цифр. Например: Ответ на вопрос `01` части `network` должен быть в файле `network/01`.

   - Сдавайте свои скрипты как исполняемые.

> Часть 1 - `Сеть`(Network) должна выполняться на школьных компьютерах `Mac`. Части 2 и 3, `Система`(System) и `Написание скриптов`(Scripting) должны выполняться на виртуальной машине `Debian` (подумайте о `live CD debian`).

</br>
</br>
</br>

# Глава IV.

## Обязательная часть

</br>

### V.1 Давай дружить

Подпишитесь на `Slash16` в [Facebook](https://www.facebook.com/slash16), [Twitter](https://twitter.com/slashseize) and [Linkedin](https://www.linkedin.com/company/5277426). 

</br>

### V.2  Сеть

1. :blue_heart: Получите список сетевых интерфейсов машины без отображения каких-либо подробностей для этих интерфейсов. Только список имен

2. :blue_heart: Определите и отобразите характеристики интерфейса "Ethernet":  
a) Определить широковещательный адрес  
b) Определите все IP-адреса, которые являются частью одной одсети  

3. :blue_heart: Определите MAC-адрес карты Wi-Fi

4. :blue_heart: Определите шлюз по умолчанию в таблице маршрутизации

5. :blue_heart: Определите IP-адрес DNS, который отвечает на следующий URL: "slash16.org"

6. :blue_heart: Получите полный путь к файлу, который содержит IP-адрес DNS-сервера, который вы используете

7. :blue_heart: Запросите внешний DNS-сервер на доменном имени "slash16.org" (например, google - "8.8.8.8")

8. :blue_heart: Найдите провайдера "slash16.org"

9. :green_heart: Найдите внешний IP-адрес "42.fr"

10. :blue_heart: Определите сетевые устройства между вашим компьютером и доменом "slash16.org"

11. :blue_heart: Используйте выходные данные предыдущей команды, чтобы найти имя и IP-адрес устройства, которое устанавливает связь между вами(локальная сеть) и внешним миром

12. :blue_heart: Найдите IP-адрес, назначенный вам DHCP-сервером

13. :green_heart: Благодаря предыдущему вопросу и обратному "DNS" найдите имя вашего хоста

14. :heart: Какой файл содержит локальные записи "DNS"?

15. :heart: Перенаправьте адрес "intra.42.fr" на "46.19.122.85"

</br>

### V.3  Система

1. :heart: В каком файле вы можете найти установленную версию вашего "Debian"?

2. :blue_heart: Какую команду вы можете использовать для переименования вашей системы?

3. :heart: Какой файл нужно изменить, чтобы сделать его постоянным?

4. :blue_heart: Какая команда показывает время с момента последней загрузки вашей системы?

5. :blue_heart: Назовите команду, определяющую состояние службы "SSH"

6. :blue_heart: Назовите команду, которая перезагружает службу "SSH"

7. :blue_heart: Выясните "PID" службы "SSHD"

8. :heart: Какой файл содержит ключи "RSA" систем, которым разрешено подключение через "SSH"?

9. :blue_heart: Какая команда позволяет узнать, кто подключен к Системе?

10. :blue_heart: Назовите команду, которая отображает таблицы разделов дисков?

11. :blue_heart: Назовите команду, которая отображает доступное пространство, оставшееся и используемое в системе, понятным для человека способом

12. :blue_heart: Выясните точный размер каждой папки "/var" понятным для человека способом с указанием пути к ней

13. :blue_heart: Назовите команду, которая в реальном времени находит запущенные в данный момент процессы

14. :blue_heart: Запустите команду "tail -f /var/log/syslog" в фоновом режиме

15. :blue_heart: Найдите команду, которая завершает работу фонового процесса.


16. :heart: Найдите сервис, который позволяет запускать определенные задачи по регулярному расписанию

17. :blue_heart: Найдите команду, которая позволяет подключиться по ssh на "виртуальной машине".(Параллельно с графической сессией)

18. :blue_heart: Найдите команду, убивающую службу "ssh"

19. :blue_heart: Перечислите все службы, которые запускаются во время загрузки, и назовите этот вид служб

20. :blue_heart: Перечислите всех существующих пользователей на "виртуальной машине"

21. :blue_heart: Перечислите всех реальных пользователей "виртуальной машины"

22. :blue_heart: Найдите команду, которая добавляет нового локального пользователя

23. :heart: Объясните, как подключиться как новый пользователь. (С графической сессией и сессией "ssh")

24. :blue_heart: Найдите команду, которая выводит список всех пакетов

</br>

### V.3  Написание Скриптов

1. Напишите сценарий, который отображает только `логин`, `UID` и `путь` каждой записи файла `/etc/passwd`.

2. Напишите сценарий, который удаляет `АКТИВНОГО` пользователя на `виртуальной машине`.

3. Три - очарование. Напишите сценарий по вашему выбору.



</br>
</br>
</br>

# Глава V.

## Бонусная часть 


Никаких бонусов по этому предмету, просто сделайте это как можно быстрее, чтобы перейти к еще лучшим проектам.



</br>
</br>
</br>

# Глава VI.

## Сдача и экспертная оценка


Сдавайте свою работу, используя репозиторий `git`, как обычно. Во время оценки будет оцениваться только работа, которая находится в вашем репозитории. Не забывайте обращать внимание на имена файлов и папок, которые вы передаете.
