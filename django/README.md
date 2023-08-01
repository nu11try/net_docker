# Задание 2

## Билд образа:

```shell
docker build ./ -t nu11try_image_stock
```

## Запуск контейнера:

```shell
docker run -d -p 8000:8000 --name nu11try_container_stock nu11try_image_stock
```
