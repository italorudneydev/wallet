# Carteira de Pagamentos

## Sobre o Projeto
Este é um projeto de carteira de pagamentos, desenvolvido para facilitar os pagamentos entre pessoas e lojistas. A carteira de pagamentos fornece uma solução simples e segura para realizar todas as transações de pagamento necessárias.

## Começando

Para obter uma cópia local em execução, siga estas etapas simples.

### Pré-requisitos

Antes de conseguir rodar este projeto, tenha certeza que você possui as seguintes ferramentas instaladas:
- Docker
- docker-compose
- Git

Se não, você pode instalá-los usando os links abaixo:
- [Docker](https://www.docker.com/products/docker-desktop)
- [docker-compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Instalação do Projeto

1. Clone o repositório
``git clone git@github.com:italorudneydev/wallet.git``
2. Copie o arquivo .env.example para .env
``cp .env.example .env``
3. Suba os containers do projeto
``docker-compose up -d``
4. Entre no container da aplicação
``docker-compose -it exec app bash``
5. Instale as dependências do projeto
``composer install``
6. Gere a chave da aplicação
``php artisan key:generate``
   Agora, você deve ter o projeto rodando localmente!
