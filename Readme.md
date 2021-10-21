<h1 align="center">NLW Heat - Server</h1>

<p align="center">
  <a href="#-descricao">Descrição</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

## Descrição

- Projeto backend desenvolvido durante a semama NLW da Rocketseat.

> Obs.: Nesse projeto temos autenticação via OAuth usando o GitHub, envios de mensagem em tempo real com o socket.io.

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🎲 Como executar

```bash
# Clone este repositório
$ git clone https://github.com/Bruno-Cesar123/heat_server.git

# Acesse a pasta do projeto no terminal/cmd
$ cd server

# Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub

# Instale as dependências
$ npm install ou yarn

# Execute as migrations do Prisma
$ yarn prisma migrate dev

# Execute a aplicação em modo de desenvolvimento
$ $ npm run dev ou yarn dev

# O servidor inciará na porta:3000 - acesse <http://localhost:4000>
```

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](license) para mais detalhes.

---

Feito por **Bruno Cesar** [**LinkedIn**](https://www.linkedin.com/in/bruno-cesar-b0039715a/)