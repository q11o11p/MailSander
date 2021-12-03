# MailSender
![Alt-picture](image/photo_2021-12-01_17-01-54.jpg)

**Mailsender** — парсер, с помощью которого можно
отправить любое сообщение на любую почту *через консоль*.
## Установка и настройка
1. Скачать репозиторий к себе на компьютер.
2. Скачать с сайта [chromedriver.chromium.org](https://chromedriver.chromium.org/) архив с `chromedriver.exe`, 
соответствующий версии вашего Chrome браузера, и распаковать данный архив в папку `code`.
3. В терминале:`cd C:\путь\к\репозиторию\MailSender && pip install -r requirements.txt`
### Настройка config.py
1. `cd code` 
2. `echo data = {'login': "ваш логин от почты", 'password': "ваш пароль"} >> config.py`
### Note
Логин и пароль должны быть от **mail.ru** почты
## Запуск парсера
`python mailsender.py`
```
Кому:*адрес получателя*
Сообщение:*любой текст*
Кол-во секунд:*тут нужно указать время (в секундах) для загрузки страниц в браузере.
Зависит от скорости вашего интернета и т.д. Рекомендуется ставить не меньше 30 секунд*

Пример:
Кому: ivan1234@gmail.com
Сообщение: привет!
Кол-во секунд: 30
```

