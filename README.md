# Docker Todo List

![Docker Logo Horizontal Blue](https://www.docker.com/wp-content/uploads/2022/03/horizontal-logo-monochromatic-white.png)

## Índice

- [Sobre](#sobre)
- [Comece aqui](#comece_aqui)
- [Instruções](#instrucoes)

## Sobre <a name = "sobre"></a>

Este projeto foi desenvolvido enquanto estudei na [Trybe](https://www.betrybe.com/).

Foi recebida uma aplicação Full Stack já pronta de um aplicativo de lista de tarefas. O objetivo deste projeto foi containerizar cada camada da aplicação, onde tínhamos Frontend, Backend e uma camada de Testes. Sendo a última, uma aplicação que testa a comunicação entre os dois primeiros serviços.

Durante o projeto, escrevíamos comandos para ser interpretados pela linha de comando do Docker (CLI). Logo em seguida era criada a Dockerfile de cada camada, que nada mais é que instruções para que o Docker pudesse buildar as imagens. Por fim, foi feito um Compose. Este por sua vez, orquestrava como as camadas dos três containers se comportariam juntas.

## Comece aqui <a name = "comece_aqui"></a>

Aqui estão as instruções para clonar o repositório e rodá-lo localmente.

### Pré-requisitos

```
Docker e Node.js
```

Instruções para instalação do [Docker](https://docs.docker.com/get-docker/)

Instruções para instalação do [Node.js](https://nodejs.org/en/download/)

## Instruções <a name = "instrucoes"></a>

Para rodar a aplicação, execute os seguintes comandos no terminal.

### Acesse o diretório do projeto

```
cd docker-todo-list
```

### Suba os containers

```
docker compose up -d
```

### Acesse o aplicativo no navegador

```
localhost:3000
```
