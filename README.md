<h1 align="center">
  <img alt="Ignite" src=".github/logo.png" width="200px" />
</h1>

<h3 align="center">
  Github Explorer
</h3>

<p align="center">Criação de uma simples aplicação para explorar repositórios do Github utilizando o ReactJS</p>

<p align="center">
  <a href="#como-executar-o-projeto">Como executar o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#anotações">Anotações</a>
</p>

<p align="center">Front-end</p>

<p align="center">
  <img src=".github/frontend.png" width="90%">
</p>

## Como executar o projeto

### Clonar este repositório

```bash
git clone https://github.com/eliasmcastro/rocketseat-ignite-reactjs-github-explorer.git
```

### Requisitos

- [Node.js](https://nodejs.org) na versão 20.16.0
- [Yarn](https://yarnpkg.com) na versão 1.22.5

### Passos para a execução

**1. Executar aplicação**

Instalar as dependências do projeto

```bash
yarn
```

Iniciar a aplicação

```bash
yarn dev
```

A aplicação começará a ser executada em http://localhost:8080

## Anotações

### Configurando estrutura

- `yarn init -y` cria o arquivo package.json
- `yarn add react` para instalar o ReactJS
- `yarn add react-dom` para instalar o ReactDOM

### Configurando Babel

- O Babel é uma ferramenta de transpilação — ou seja, ela converte código escrito em uma versão mais recente do JavaScript (como ES6, ES7, etc.) para uma versão mais antiga e amplamente compatível com a maioria dos navegadores
- `yarn add @babel/core @babel/cli -D` para instalar o babel core e cli
- `yarn add @babel/preset-env @babel/preset-react -D` para instalar o babel preset-env e preset-react
- `yarn add babel-loader -D` para instalar o babel-loader (integração entre o babel e o webpack)

### Configurando Webpack

- O Webpack é uma ferramenta de empacotamento de módulos e ele tem como principal objetivo pegar diferentes arquivos de recursos (como JavaScript, CSS, imagens, fontes, etc.) e empacotá-los em um ou mais arquivos de saída (bundles), para que possam ser carregados de maneira eficiente pelo navegador.
- `yarn add webpack webpack-cli -D` para instalar o webpack e webpack-cli
- `yarn add html-webpack-plugin -D` para instalar o html-webpack-plugin
- `yarn webpack` para executar o Webpack
- `yarn add webpack-dev-server -D` para instalar o webpack-dev-server
- `yarn webpack serve` para iniciar o Webpack Dev Server, que fará a aplicação rodar em `http://localhost:8080`

### Variáveis de Ambiente

- `yarn add cross-env -D` para instalar o cross-env

### CSS

- `yarn add style-loader css-loader -D` para instalar o style-loader e css-loader
- `yarn add node-sass -D` para instalar o node-sass
- `yarn add sass-loader -D` para instalar o sass-loader

### React Refresh Webpack Plugin

- `yarn add @pmmmwh/react-refresh-webpack-plugin react-refresh -D` para instalar o React Refresh Webpack Plugin