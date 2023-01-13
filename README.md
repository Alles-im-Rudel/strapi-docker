# Alles im Rudel Strapi Docker

This docker stack is used to build and test the alles-im-rudel-strapi container.

## Usage

First, clone your app into the /app directory.

```shell
git clone git@github.com:Alles-im-Rudel/alles-im-rudel-strapi.git app
```

Afterwards, copy the .env.example to .env and modify its values as needed.
```shell
cp .env.example .env
```

You can now start the app using:
```shell
docker-compose up -d --build
```
