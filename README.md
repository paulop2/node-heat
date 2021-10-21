<h1 align="center">NLW Heat - Node.js</h1>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
  <img src="https://img.shields.io/static/v1?label=NLW&message=Heat&color=8257E5&labelColor=000000" alt="NLW Heat" />
</p>


## 💻 Sobre o projeto

Node-Heat é uma das trilhas da aplicação desenvolvida na semana que consiste no envio de mensagens entre usuários, utilizando o github como autenticação .


Projeto desenvolvido durante o _stage 1_ da **NLW Heat - Next Level Week** oferecida pela [Rocketseat](https://nextlevelweek.com/), seguindo a trilha **Impulse**.
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

---

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🚀 Como executar

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub

- Clone o repositório e acesse a pasta;
- Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ❤️ por Paulo Vitor 👋🏽 [Entre em contato!](https://www.linkedin.com/in/paulo-vitor-s-841883127)