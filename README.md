# Ping 
Aplicação Java com container para exemplo


## Pré-requisitos

- Java 17 +
- Docker 
- Acesso a internet
- Acesso ao docker Hub

## Instalação

#### Clone

```
git clone https://github.com/Gubisss/ping.git
```

#### Instalação


## Execução


#### Docker

Criação de image

```
docker build -t ping .

```
docker build -t ping-java -f Dockerfile_java .



*executar container 

spring.profiles.active=dev


```
docker run -d -p 8080:8080 -e PROFILE=prd ping
docker run -d -p 8080:8080 -e PROFILE=prd gubisss/ping (se quiser baixar a sua imagem do docker)
```

```
docker run -d -p 8080:8080 minhaimagen:tag
```

docker exec -it (id) bash

docker run -d -p 9000:8080 -e PROFILE=prd ping-java


docker tag ping gubisss/ping

#### Menu iniciar

> Menu Iniciar: Selecionar e clicar em Aplicação X

#### Navegação

http://localhost:8080


## Features (Funcionalidades)

#### Upload de arquivos

> __Lorem Ipsum__ is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's

#### Conversão de dados

> __Lorem Ipsum__ is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's


## Contatos

- Desenvolvedor 1 - desenvolvedor1@email.com
- Desenvolvedor 2 - desenvolvedor2@email.com


## Referencias

 - [UOL](https://www.uol.com.br/)
 - [Gov br](https://www.gov.br/)