
<div align="center">
  <h3 align="center">Шаблон FastApi для МВП</h3>

  <p align="center">
    Структура проекта для легкой разработки 
  </p>
</div>


### О чём проект
Минималистичный шаблон с удобной структурой проекта для использования в петпроектах или при создании MVP на хакатонах


### Локальный запуск

Перед тем, как развернуть у себя сервис необходимо установить [Docker](https://docs.docker.com/get-docker/) и [Docker Compose](https://docs.docker.com/compose/install) на вашу машину.

Далее, необходимо выполнить следующие действия:

```bash
# Клонируем репозиторий
git clone -b master https://github.com/Capitan-Parrot/FastApi-template.git
# Переходим в папку с проектом
cd FastApi-template
# Запускаем сервис
docker-compose up -d --build
```
