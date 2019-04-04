# .NET Core and Docker
This is a really basic core installation of ASP .NET to teach about a way it can be dockerized an ASP .NET application 

##Prerequesites
Install dot-net
Install docker

## Installation


```sh
git clone https://github.com/nostick/dot-net-core myApp
cd myApp
docker build -t myapp .
docker run -d -p 8080:80 --name MyNetApp myapp

```

## Ejemplo de uso

On browser write
```url
http://localhost:8080
```
