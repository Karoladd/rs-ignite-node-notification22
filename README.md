
<h1 align="center"> Ignite Node.js - Notification Back-End </h1>

<p align="center">
    Node.js week to learn more about the concepts and workings.
</p>

<p align="center">
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-references">References</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

## Result

<p align="center">
    <img alt="objective" src=".github/getnot.jpg" width="100%">
</p>

## Tkinter

<p align="center">
    <img alt="objective" src=".github/countnot.jpg" width="35%">
    <img alt="objective" src=".github/createnot.jpg" width="35%">
</p>
<p align="center">
    <img alt="objective" src=".github/readnot.jpg" width="33%">
    <img alt="objective" src=".github/unreadnot.jpg" width="33%">
    <img alt="objective" src=".github/cancelnot.jpg" width="33%">
</p>

## 🚀 Technologies

This project was developed with the following technologies:

- [Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.
- [Typescript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)

## 💻 Project

Project with the pandas library, allowing more knowledge about this tool

Microserviços - Utilizam um banco de dados. Uma aplicação onde as suas funcionalidades são separadas em projetos menores que, apesar de interligados, são independentes.
Dentro da pasta src, o NestJS possui três tipos de arquivos principais: Modules, controllers e services.
```bash
$ npm i -g@nestjs/cli
$ nest new folder_name
$ npm run start:dev
```
http://localhost:3000/
dist/ - conversor ts para js, node apenas entende js
node_modules/ - dependências
ctrl+shift+p >preferences: Open User Settings
app.controller.ts - rotas para a plicação
app.service.ts - funcionalidades gerais
Extensão Prisma
```bash
$ npm i prisma -D
$ npm i @prisma/client
$ npx prisma init --datasource-provider SQLite
$ npx prisma migrate dev
$ npx prisma studio
$ npm i class-validator class-transformer
```
lá em baixo, no CRLF, muda para LF
Importância de fazer Design Software antes de entrar com a programação.
Geralmente inicia criando um banco de dados.
infra/ tudo que se é externo da aplicação, banco de dados, API, http
undefined: valor sem nada (sem existencia)
null: valor vazio (com existêcia)
tsconfig.json
	"strict": true,
	"strictNullChecks": true,
	"strictPropertyInitialization": false,
jest.config.ts - jest of package.json
npm run test
repositories/ intermediario de comunicação de banco e app
https://martinfowler.com/microservices/
DTO - Data Transfer Object
ctrl+shift+p >TypeScript: Restart TS Server
https://app.rocketseat.com.br/
- Para adicionarmos uma camada de proteção no gerenciamento dos nossos dados, utilizaremos getters e setters na nossa classe Notification. Como eles ajudam nessa proteção?
Os getters e setters permitem que a gente busque e configure dados por meio de métodos definidos, podendo assim aplicar validações e outras proteções em vez de simplesmente aceitar os valores repassados.
- O que é o conceito Value Object?
Uma forma de agregar validações e outras funcionalidades no momento da definição de um campo.
- Qual a vantagem de utilizar in-memory database?
Trabalhar com os dados no mesmo padrão e formato do banco de dados em produção, porém mantendo os dados apenas em memória. Assim, evita a dependência de terceiros nos testes (banco de dados) e também do uso de mocks.
- O que é Mapper? Mapeamento de dados a partir de uma conversão na forma de acesso a esses dados para um formato conhecido pelo alvo.

START - PIP
- create folder: note
- pip install pandas tk PyInstaller
- change path variables 
- pyinstaller index.py
  * build/ dist/ index.spec
- App: build/ dist/ note/ index.spec
- dist - index/index.exe

PATH VARIABLES
- create folder in download
- alter path util/download.py
- alter path util/rename.py
- alter index.py

PYTHON
- Extension to run in VSCode: Python and Pylance

FOLDERS:
- test/xls - analyze excel
- test/excel - python result in excel
- test/note - python result in note
- test/project - learning tests

LEARNED:
- tkinter interface
- import function and libraries 
- add function in button
- change background color to loading
- get the list of directories
- check if the list is empty
- browse files with types
- read and write each line with open() utf-8
- delete files of directory
- list: append and delete items
- condiction to insert path or click in button
- move file to other folder 
- rename file with the data 

Links Usefull:
<p align="left"> Python Download - https://www.python.org/downloads/</p>
<p align="left"> VSCode Download -  https://code.visualstudio.com/download</p>
<p align="left"> Git Download -  https://git-scm.com/download/win</p>

## 🔖 References

Filtering rows and columns in a table:
https://www.youtube.com/watch?v=6M0PUNw7faE

How to read file line by line with Python:
https://www.youtube.com/watch?v=76loQGxS-Zg

Manipulating rows of pandas dataframes:
https://www.youtube.com/watch?v=-22JkOmJeSI

Select Rows & Columns by Name or Index in Pandas DataFrame using [ ], loc & iloc:
https://www.geeksforgeeks.org/select-rows-columns-by-name-or-index-in-pandas-dataframe-using-loc-iloc/

Delete all files directory python:
https://www.techiedelight.com/pt/delete-all-files-directory-python/

Remove list elements that contain given String in Python:
https://bobbyhadz.com/blog/python-remove-elements-from-list-that-contain-string

Adding a license to a repository:
https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository

## :memo: Licence

This project is under the MIT license.

---

Made with ♥ by Karoline :wave: [Let's program together!](https://www.linkedin.com/in/karoline-hikari-yamamoto/)

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
