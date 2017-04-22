# HOW TO USE

This are some of the ways we can use this image, but is not an exhaustive list of commands we can run against it.


## Build the NODE ZSH Docker Image

This step is optionally, because the first time you execute a `sudo docker-compose run` command it will build the image.

```shell
sudo docker-compose build
```

## Run the Container as Node User

Normally you want to run the Container as the `node` user to play with `npm`.

#### Keeps the Container after you exit it.

```shell
sudo docker-compose run node-user
```

#### Removes the Container after you exit it.

```shell
sudo docker-compose run --rm node-user
```

## Run Container with Node CLI

This will give you access to the `node` CLI shell inside the Docker Container.

```shell
sudo docker-compose run node-cli
```

## Run Container as Root User

In case you need to access the Container as the Root User.

```shell
sudo docker-compose run root-user
```
