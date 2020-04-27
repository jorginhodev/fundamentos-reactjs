<h1 align="center">
    <img alt="GoStack" src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" width="200px" />
</h1>

<h3 align="center">
  Primeiro projeto com React
</h3>

<p align="center">Desafio 07: GoFinances Web, aplicado no <a href="https://rocketseat.com.br/bootcamp">Bootcamp GoStack</a> 🎓</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instala%C3%A7%C3%A3o-e-execu%C3%A7%C3%A3o">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-funcionalidades-da-aplica%C3%A7%C3%A3o">Funcionalidades da aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-especifica%C3%A7%C3%A3o-dos-testes">Especificação dos testes</a>
</p>

## 🖥 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [ReactJS](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://github.com/axios/axios)
- [date-fns](https://date-fns.org/)
- [styled-components](https://styled-components.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Jest](https://jestjs.io/)

## 🚀 Instalação e execução

1. Faça um clone desse repositório;
2. Entre na pasta rodando `cd fundamentos-reactjs`;
3. Rode `yarn` para instalar as dependências;
4. Rode `yarn start` e teste a aplicação no [Insomnia](https://insomnia.rest/);
5. Rode `yarn test` para rodar os testes.

## 🚀 Sobre o desafio

Nesse desafio, continuamos desenvolvendo a aplicação de gestão de transações, treinando o que você foi aprendido até agora no Node.js junto ao TypeScript, mas dessa vez incluindo o uso de banco de dados com o TypeORM e envio de arquivos com o Multer!

Essa será uma aplicação que deve armazenar transações financeiras de entrada e saída e permitir o cadastro e a listagem dessas transações, além de permitir a criação de novos registros no banco de dados a partir do envio de um arquivo csv.

Nesse desafio, continuamos desenvolvendo a aplicação de gestão de transações, a GoFinances. Agora iremos praticar o que foi aprendido até agora no React.js junto com TypeScript, utilizando rotas e envio de arquivos por formulário.

A aplicação irá se conectar ao backend do Desafio 06, e exibir as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.


### Funcionalidades da aplicação

- **`Listar as transações da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na sua API.

**Dica**: Você pode utilizar a função [Intl](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/NumberFormat) para formatar os valores. Dentro da pasta `utils` no template você encontrará um código para te ajudar.

- **`Exibir o balance da sua API`**: Sua página `Dashboard`, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: Na sua página `Import`, você deve permitir o envio de um arquivo no formato `csv` para o seu backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

## 🚀 Especificação dos testes

Para esse desafio, temos os seguintes testes:

- **`should be able to list the total balance inside the cards`**: Para que esse teste passe, sua aplicação deve permitir que seja exibido na sua Dashboard, cards contendo o total de `income`, `outcome` e o total da subtração de `income - outcome` que são retornados pelo balance do seu backend.

* **`should be able to list the transactions`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados dentro de uma tabela, toda as transações que são retornadas do seu backend.

- **`should be able to navigate to the import page`**: Para que esse teste passe, você deve permitir a troca de página através do Header, pelo botão que contém o nome `Importar`.

- **`should be able to upload a file`**: Para que esse teste passe, você deve permitir que um arquivo seja enviado através do componente de drag-n-drop na página de `import`, e que seja possível exibir o nome do arquivo enviado para o input.

Feito com 💜 by Jorge Ramos
