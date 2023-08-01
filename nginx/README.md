# Задание 1

## Билд докер образа:

```shell
docker build -t nu11try_image .
```

## Запуск контейнера:

```shell
docker run -d -p 8090:80 --name nu11try_container nu11try_image
```