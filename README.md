# Risuto

Teste o aplicativo neste [link](http://risuto.sytes.net/).

## Sobre o projeto

**Ristuo** é um aplicativo de criação, controle e compartilhamento de listas de compras. Com ele você pode criar listas, incluindo locais de compras e os items nestes locais. Estas listas podem ser compartilhadas com outro usuários, por meio de convites de compartilhamento. Ao selecionar o menu de compra, escolhendo a lista e o local, os items relacionados são filtrados por local de compra, podendo ter o controle do que já foi comprado.

## Getting Started

This project works with [Docker](https://www.docker.com/resources/what-container/)!

1. Clone this repository:

```bash
git clone https://github.com/NilsonNetto/risuto.git
```

2. On **risuto folder** run the following commands

```bash
git submodule init
git submodule update
```

3. On **risuto folder** run the docker containers

```bash
docker-compose up --build
```

4. Access the app on http://localhost on your favorite browser

5. If needed you can acess the API on http://localhost/api

## Funcionalidades

- Login:

  - Acesse suas listas em qualquer lugar com a sua conta cadastrada;

- Listas:

  - Visualize todas as suas listas ou compartilhadas com você;
  - Crie, edite ou compartilhe suas listas pelo menu de listas;

- Tela das listas:

  - Adicione novos locais e items nesta tela;
  - Edite ou exclua itens ou locais;

- Iniciar Compra:

  - Selecione a lista e local que você deseja iniciar as compras;
  - Marque os itens conforme for fazendo sua compra;
  - Altere ou exclua itens que não forem encontrados na hora da compra;

- Compartilhar:

  - Veja se você tem convites de compartilhamento;
  - Veja quais listas estão compartilhadas com você;
  - Veja quais listas você compartilhou com outro usuário;

- Perfil:

  - Altere seus dados do aplicativo;
  - Faça o logoff da sua conta para possibilitar outros usuários;

## Technologies

The following tools and frameworks were used in the construction of the project:

## Front-end

  <img style='margin: 5px;' src='https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E'>

## Back-end

  <img style='margin: 5px;' src='https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white'>

## DevOps

  <img style='margin: 5px;' src='https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white'>
</p>

## Feedbacks

This project is working in its first version, i'm still working on it to implement new features and maybe solving some bugs.

If you have any feedback i'll appreciate it!

<a href="mailto:eng.nilsonnetto@gmail.com" target="_blank">
  <img style='margin: 5px;' src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="30" alt="gmail logo"  />
</a>
<a href="https://www.linkedin.com/in/nilson-netto-76b820240/" target="_blank">
  <img style='margin: 5px;' src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="30" alt="linkedin logo"  />
</a>
