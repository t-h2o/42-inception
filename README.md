# 42-inception

## Add your user in docker group

```sh
usermod -aG docker <USER>
```

## Build an image

```sh
docker build <FOLDER_OF_DOCKERFILE> -t <MY_IMAGE_NAME>
```

## Run the image

```sh
docker run -it <MY_IMAGE_NAME>
```
