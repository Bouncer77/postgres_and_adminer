# Запустить

```bash
# Убеждаемся что docker установлен
docker -v

# Убеждаемся, что docker-compose установлен
docker-compose -v

```

Если docker не установлен, то установить с [сайта](https://docs.docker.com/get-started/) 

[Docker for Windows](https://docs.docker.com/desktop/windows/install/)

[Docker for Ubuntu](https://github.com/Bouncer77/knowledge_base/blob/master/Docker/00-Install_Docker.md)

```bash
# Собираем проект
docker-compose build

# Запускаем проект
docker-compose up

# Переходим в браузере по localhost
#
# db:       PostgresSQL
# user:     postgres
# password: example
```