# labs-auction-goexpert-master

Sistema de leilão desenvolvido em Go com persistência em MongoDB. Esse projeto foi criado como parte de um estudo prático com foco em boas práticas de arquitetura e organização de código.

---

## Pré-requisitos

Antes de rodar o projeto, você precisará ter instalado:

- [Go 1.20+](https://golang.org/dl/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [MongoDB](https://www.mongodb.com/) (utilizado via Docker)

---

## Estrutura do Projeto

abs-auction-goexpert-master/
├── cmd/auction/ # Ponto de entrada do app (main.go)
├── configuration/ # Configurações de logger, banco de dados, erros
├── internal/ # Entidades e casos de uso
├── docker-compose.yml # Subida de MongoDB via Docker
├── Dockerfile # Dockerfile da aplicação
├── go.mod / go.sum # Dependências Go
└── .env # Variáveis de ambiente

---

## Rodando em ambiente local

### 1. Clone o repositório
git clone https://github.com/mourasjames/labs-auction-goexpert-master.git
cd labs-auction-goexpert-master

### 2.
docker-compose up -d


