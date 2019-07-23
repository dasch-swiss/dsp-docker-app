# Knora-Docker-App

Docker-App for running the complete Knora-Stack.

**Requires Docker-CLI 19.0.3 or newer!**

## Usage

### Start everything

```
$ docker app render | docker-compose -f - up
```

### Start everything without `webapi`

```
$ docker app render --set enable-webapi=false | docker-compose -f - up
```

## Useful Commands

```
$ docker app inspect
$ docker app render
$ docker app render --parameters-file prod.yml
$ docker app push --tag myrepo/hello:0.1.0
$ docker app inspect myrepo/hello:0.1.0
```
