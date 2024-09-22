# CinePrime Frontend 🍿

Bem-vindo ao repositório do frontend da aplicação CinePrime. Aqui você encontrará as informações necessárias para configurar e rodar o ambiente de desenvolvimento da aplicação.

## Índice

- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Rodando o Projeto](#rodando-o-projeto)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Licença](#licença)

## Pré-requisitos

Antes de iniciar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

- [Node.js](https://nodejs.org/en/) - Versão 14 ou superior
- [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/) - Gerenciador de pacotes
- [Vue CLI](https://cli.vuejs.org/) - Caso deseje utilizar a interface de comando para Vue.js

## Instalação

Siga os passos abaixo para instalar e configurar o projeto na sua máquina local:

```bash
git clone https://github.com/hyarlei/CinePrime_Vue.git
```

Já no arquivo raiz do projeto, acesse o diretório do frontend:

   ```bash
   cd .\frontend\
   ```

## Configuração

Instale as dependências necessárias com o gerenciador de pacotes de sua preferência (npm ou yarn):

   ```bash
   npm install
   ```

   Ou, caso esteja utilizando o Yarn:

   ```bash
   yarn install
   ```

## Rodando o Projeto

Após configurar as variáveis de ambiente, você pode rodar o servidor de desenvolvimento:

```bash
npm run dev
```

Ou, se estiver usando o Yarn:

```bash
yarn dev
```

Isso iniciará o projeto em modo de desenvolvimento. Acesse [http://localhost:8080](http://localhost:8080) para ver a aplicação rodando.

## Estrutura do Projeto

Abaixo, uma visão geral da estrutura de diretórios da aplicação:

```
├── public/                   # Arquivos públicos
├── src/                      # Código fonte principal
│   ├── api/                  # Fornece as informações de fimes
│   ├── assets/               # Imagens e arquivos estáticos
│   ├── components/           # Componentes Vue reutilizáveis
│   ├── pages/                # Páginas da aplicação
│   ├── routes/               # Configuração de rotas Vue Router
|   ├── service/              # Configuração de serviços
│   ├── store/                # Gerenciamento de estado Vuex
│   ├── App.vue               # Componente raiz
│   └── main.js               # Ponto de entrada da aplicação
└── package.json              # Arquivo de dependências e scripts
```

## Tecnologias Utilizadas

Aqui estão as principais tecnologias utilizadas no desenvolvimento do frontend:

- **Vue.js 3** - Framework JavaScript progressivo para construção de interfaces de usuário.
- **Vue Router** - Gerenciamento de rotas da aplicação.
- **Vuex** - Gerenciamento de estado centralizado.
- **Axios** - Cliente HTTP para integração com APIs externas.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).