# ![movie-icon](https://github.com/GeovanniSantos/dsmovie/blob/main/assets/movie.png) DSMovie 

![image](https://github.com/GeovanniSantos/dsmovie/blob/main/assets/animação.gif)

## Sobre o projeto

https://geovanni-dsmovie.netlify.app

DSMovie é uma aplicação full stack web e mobile construída durante a 6ª edição da **Semana DevSuperior** (#sds6), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em avaliação de preferência de filmes, onde o usuário responde o formulário e insere uma nota de 1 a 5, e atualiza no app web.

## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/devsuperior/bds-assets/main/sds/dsmovie-dominio.png)

# Tecnologias utilizadas
## Back end
- Java JDK 17
- Spring Boot
- Web / JPA / H2 / Postgres / Security
- Maven
- Postman
## Front end
- Visual Code
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- React Router DOM
- React Hooks 
- Apex Charts
- Expo
- Bootstrap
- Axios
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11 / Node

```bash
# clonar repositório
git clone https://github.com/GeovanniSantos/dsmovie

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/GeovanniSantos/dsmovie

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
yarn start
```
