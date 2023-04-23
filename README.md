# Контейнер для автоматического запуска связки из ngin + mysql + phpmyadmin

Для запуска контейнеров:

1. ```git clone git@github.com:HenLeiko/eraVR.git```
2. ```cd eraVR```
  1. Заполните env файл.
  2. Укажите корректные порты для сервисов в файле docker-compose.
3. ```sudo docker-compose up -d```

Для настройки БД использовать env файл, как показано в env-exemple
