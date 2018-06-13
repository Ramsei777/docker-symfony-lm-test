# docker-symfony-lm-test

# Установка

Клонируем репозиторий:

```bash
$ git clone https://github.com/Ramsei777/docker-symfony-lm-test
```

Запуск из корневого каталога

```bash
$ docker-compose up
```

## Выполнение команд внутри контейнера

```
$ docker-compose exec php bin/console doctrine:schema:update --force
```

или

```
$ docker-compose exec php composer req profiler

```

## &nbsp;
