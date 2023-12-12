#Инструкция к запуску
1. Склонировать репозиторий
2. Чтобы запустить сервис необходимо ввести
```docker
docker-compose up -d --build
```
и перейти по http://localhost:8501/

3. На странице сервиса можно выбрать функции "Создать секрет" или "Вернуть секрет по коду". В строке секрет ввести информацию, которую мы хотим спрятать. В строку с кодовой фразой ввести любую фразу. 
Далее необходимо нажать на кнопку создать секрет и скопировать возникший код. При выборе функции "Вернуть секрет по коду" в строку нужно вводить именно этот код. Каждый внесенный секрет можно вернуть по ключу только 1 раз.
4. Чтобы остановить сервис, необходимо ввести
```docker
docker-compose down
```
![GitHub Logo](/Architecture_scheme.png)
