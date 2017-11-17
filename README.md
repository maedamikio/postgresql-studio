# PostgreSQL Studio

This PostgreSQL Studio works one container.

# docker run

You can run container from Docker Hub or Build Image.

## from Docker Hub

This version is 2.0

```
$ docker run -d -p 8080:8080 --name postgresql-studio maedamikio/postgresql-studio
```

## from Build Image

```
$ git clone git@github.com:maedamikio/postgresql-studio.git
$ cd postgresql-studio
$ docker build -t postgresql-studio .
$ docker run -d -p 8080:8080 --name postgresql-studio postgresql-studio
```

# Sign In

```
http://localhost:8080/
```

# Authors

* **MAEDA Mikio** - [Twitter](https://twitter.com/maeda_mikio)
