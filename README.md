# Tickei

Bem-vindo(a) ao Tickei. App de tarefas desenvolvido utilizando a Stack [MERN](https://www.mongodb.com/mern-stack)  para o desafio técnico da empresa Ebytr.

# Bibliotecas e frameworks utilizados

## Front-end: 

- [React](https://pt-br.reactjs.org/) 
- [Tailwindcss](https://tailwindcss.com/docs/guides/create-react-app)

- [Tailwind Styled Components](https://www.npmjs.com/package/tailwind-styled-components)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Eslint](https://eslint.org/)
- [React Testing Library](https://testing-library.com/)

## Back-end:

- [Express](https://expressjs.com/pt-br/)

- [Cors](https://www.npmjs.com/package/cors)

- [Nodemon](https://www.npmjs.com/package/nodemon)
- [Mongodb](https://www.npmjs.com/package/mongodb)
- [Eslint](https://eslint.org/)
- [DotEnv](https://www.npmjs.com/package/dotenv)

# Como Utilizar

Inicialmente clone a aplicação:

```shell
git clone git@github.com:dcmatheus/Tickei.git
```

Devido ao uso do `git submodules` será necessário também iniciar os submódulos da aplicação:

```shell
cd ./Tickei
git submodule init
git submodule update
```

## Instale as dependências do Back-End e inicie a API

Dentro da pasta raiz do projeto execute:

```shell
cd ./tickei-back-end
npm install 
```

Será necessário criar um aquivo `.env` com as seguintes chaves:

```she
PORT=
DB_URL=
DB_NAME=
```

Contendo respectivamente a porta que será utilizada pela aplicação, a URL do banco de dados e por ultimo o nome do mesmo.

Por fim, inicie a API :

```sh
npm run dev
```

## Instale as dependências do Front-End e inicie a Aplicação

Dentro da pasta raiz do projeto execute:

```shell
cd ./tickei-front-end
npm install
```



