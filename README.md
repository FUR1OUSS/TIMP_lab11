**Лабораторная работа №11**

Установим ngrok: brew install ngrok/ngrok/ngrok

Подключим токен: ngrok config add-authtoken <token>

Установим python: brew install python3

Создадим папку lab11 и сделаем там файл > index.html, а также пропишем python3 -m http.server для запуска локального сервера

Запустим ngrok: ngrok http 8000

<img width="1116" alt="Снимок экрана 2023-06-01 в 15 15 32" src="https://github.com/FUR1OUSS/TIMP_lab11/assets/82472327/845a3e25-8cb9-42fd-849a-b64a8545e898">

Для подключения к серверу скопируем ссылку, которая находиться напротив forwarding
