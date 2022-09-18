<p  align="center">
<a  href="https://mepoupe.com/"  target="blank"><img  src="https://mepoupe.com/images/logo.jpg"  alt="MePoupe Logo" /></a>
</p>

<p  align="center">Teste de desenvolvimento para o <a  href="https://mepoupe.com/"  target="_blank">Me Poupe!</a></p>

## Funcionalidades

>+ ### 1 - Cálculo de média
Calcula a média de dois números. O resultado é arredondado para 2 casas decimais utilizando o método Half Round Up.

>+ ### 2 - Consulta de CEP.
Realiza a consulta de endereços através do cep fornecido.

## Executando o projeto

### Clone o projeto e o submódulos

```bash
 $ git clone --recurse-submodules https://github.com/JoaoLiima/mepoupe-workspace.git
```

### Instalação

Entre na pasta `mepoupe-api` e instale as dependências:

```bash
$ npm install
```

ou

```bash
$ yarn install
```

### Executando a aplicação

Dentro da pasta `mepoupe-workspace`, execute:

```bash
$ sudo docker-compose up
```

### Utilizando a aplicação

Uma vez que a aplicação esteja rodando, é possível acessar a página com a documentação da API através do link: http://localhost:3000/docs

## Tecnologias utilizadas

>+ [NodeJS](https://nodejs.org/en/)
>+ [NestJS](https://nestjs.com/)
>+ [TypeScript](https://www.typescriptlang.org/)
>+ [Axios](https://axios-http.com/ptbr/docs/intro)
>+ [Jest](https://jestjs.io/)
>+ [Docker](https://www.docker.com/)
