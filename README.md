# Risuto

Teste o aplicativo neste [link](http://risuto.sytes.net/).

## Sobre o projeto

**Risuto** is an app to create, control and share grocery lists. In the app you can create lists, including locals and items. This lists can be shared with other users by share requests. In the buy menu you can select the list and the local of the list for filter the items by local, allowing you to control which one you already get.

### PT-BR

**Risuto** é um aplicativo de criação, controle e compartilhamento de listas de compras. Com ele você pode criar listas, incluindo locais de compras e os items nestes locais. Estas listas podem ser compartilhadas com outro usuários, por meio de convites de compartilhamento. Ao selecionar o menu de compra, escolhendo a lista e o local, os items relacionados são filtrados por local de compra, podendo ter o controle do que já foi comprado.

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

  - Acess your lists anywhere with your account;

- Lists:

  - View all your lists and shared lists with you;
  - Create, edit or share your lists in the list menu;

- List page:

  - Add new locals and items;
  - Edit or remove items or locals;

- Buy:

  - Select the list and local that you want to start shopping;
  - Check the items as you are buying;
  - Edit or remove items that are not found during the shopping;

- Share:

  - View new share requests;
  - Manage the lists that are shared with you;
  - Manage the lists that you share with others;

- Profile:

  - Edit you personal information;
  - Logoff from your account;

## Technologies

The following tools and frameworks were used in the construction of the project:

## Front-end

<p>
  <img style='margin: 5px;' src='https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E'>
</p>

## Back-end

<p>
  <img style='margin: 5px;' src='https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white'>
  <img style='margin: 5px;' src='https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white'>
</p>

## DevOps

<p>
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
