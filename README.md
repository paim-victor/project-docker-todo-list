# Docker Todo List

Primeiro projeto do modulo de back-end, na trybe. Projeto visa o apredizado da tecnologia Docker, que nos ajuda a conteinerizaras aplicações de frontend, backend e testes, criar uma conexão entre elas e orquestrar seu funcionamento! 🐋

## 📋 Habilidades

- Conhecimento dos comandos dockers no CLI - Interface de linha de comando;
- Criação de um contêiner Docker para uma aplicação de front-end;
- Criação de um contêiner Docker para uma aplicação de back-end;
- Criação de contêiner Docker para uma aplicação de testes;
- Orquestração de três contêineres utilizando o Docker compose.

### 🚀 Tecnologias

- DOCKER
- BASH

### 🔧 Instalação

```
npm install
cd docker
```
## ⚙️ Executando

- Buildando as imagens de back-end, front-end e testes:
```
docker image build -t todobackend ./todo-app/back-end
docker image build -t todofrontend ./todo-app/front-end
docker image build -t todotests ./todo-app/tests
```

- Subindo e orquestramos os containers:
```
docker-compose up -d
```

## 🛠️ Testes
```
docker attach docker_todotests_1
```

## 📫 Contatos:

<div>
<a href = "mailto:victor-paim@hotmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/seu-usuário-linkedln-aqui" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>
