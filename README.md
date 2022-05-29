# 42-inception

## Few commands to manipulate docker

### Add your user in docker group

```sh
usermod -aG docker <USER>
```

### Build an image

```sh
docker build <FOLDER_OF_DOCKERFILE> -t <MY_IMAGE_NAME>
```

### Run the image

```sh
docker run -it <MY_IMAGE_NAME>
```

## Wordpress

### Ressources

* Alpine: [wordpress](https://wiki.alpinelinux.org/wiki/WordPress#Install_lighttpd.2C_PHP.2C_and_MySql)
