# Atividade-30PTS---Int.-Tec.-Informa-o
## Objetivo do Projeto

Este projeto tem como objetivo demonstrar o uso de containers Docker para facilitar o desenvolvimento, implantação e execução de aplicações de forma isolada e padronizada.

## Comandos Utilizados

- `docker build -t nome-da-imagem .`  
    Cria uma imagem Docker a partir do Dockerfile presente no diretório atual.
- `docker run -d --name nome-do-container -p 8080:80 nome-da-imagem`  
    Executa um container em segundo plano, mapeando a porta 80 do container para a porta 8080 do host.
- `docker ps`  
    Lista os containers em execução.
- `docker stop nome-do-container`  
    Para a execução do container.

## Como Executar o Container

1. Clone o repositório:
     ```bash
     git clone <url-do-repositorio>
     cd <nome-do-diretorio>
     ```
2. Construa a imagem Docker:
     ```bash
     docker build -t nome-da-imagem .
     ```
3. Execute o container:
     ```bash
     docker run -d --name nome-do-container -p 8080:80 nome-da-imagem
     ```
4. Acesse a aplicação em `http://localhost:8080` no navegador.