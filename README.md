# Описание

Укротитель ссылок.

Сокращает любую ссылку до короткого вида http://yourdomain.com/abCdE

# Системные требоавния

* PHP >= 5.4
* MySQL / MariaDB

# Установка

* Клонируйте репозиторий

```
git clone https://github.com/vanchester/url_shortener.git
```

* Установите зависимости

```
cd /path/to/url_shortener
/path/to/php compoeser.phar up
```

* Настройте права на запись для директорий **assets** и **protected/runtime**

```
cd /path/to/url_shortener
chmod 777 ./assets ./protected
```

* Создайте базу данных и настройте подключение к ней: скопируйте файл **protected/config/db.example.php** 
в **protected/config/db.php**, откройте его в текстовом редакторе и пропишите параметры подключения

* Настройте корневую директорию веб-сервера на директорию, в которую клонирован проект url_shortener

Готово!

# Демо

http://url.suturin.com

# Варианты развития

* Авторизация и история сокращенных ссылок
* Мультиязычность
* Preview страниц сокращаемых ссылок
* Вынести в файл конфигурации длину кода ссылки и допустимые в нем символы