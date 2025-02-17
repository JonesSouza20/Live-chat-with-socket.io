# Live Chat com Socket.io

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://shields.io)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

Um projeto de chat em tempo real utilizando Node.js, Express e Socket.io.

## 📑 Índice

- [📂 Estrutura do Projeto](#estrutura-do-projeto)
- [🚀 Funcionalidades Principais](#funcionalidades-principais)
- [⚙️ Configuração e Execução](#configuração-e-execução)
  - [📋 Pré-requisitos](#pré-requisitos)
  - [📥 Clonar o repositório](#clonar-o-repositório)
  - [📦 Instalar dependências](#instalar-dependências)
  - [🏃‍♂️ Executar o projeto](#executar-o-projeto)
- [🔜 Roadmap](#roadmap)
- [🤝 Contribuição](#contribuição)
- [📄 Licença](#licença)
- [📚 Referências](#referências)

## 📂 Estrutura do Projeto

```
LIVE-CHAT-WITH-SOCKET.IO
│── liveChat
│   │── node_modules/
│   │── chat.db
│   │── index.html
│   │── index.js
│   │── License
│   │── package-lock.json
│   │── package.json
│   │── README.md
```

## 🚀 Funcionalidades Principais

- Comunicação em tempo real usando WebSockets
- Interface simples para troca de mensagens
- Gerenciamento de conexões de usuários

## ⚙️ Configuração e Execução

### 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### 📥 Clonar o repositório

```sh
git clone https://github.com/JonesSouza20/live-chat-with-socket.io.git
cd live-chat-with-socket.io/liveChat
```

### 📦 Instalar dependências

```sh
npm install
```

Dependências utilizadas:

- `express` - Framework web para Node.js
- `socket.io` - Biblioteca para WebSockets

### 🏃‍♂️ Executar o projeto

```sh
node index.js
```

O servidor estará rodando em `http://localhost:3000`

## 🔜 Roadmap

- [ ] Implementar autenticação de usuários.
- [ ] Adicionar suporte para envio de arquivos.
- [ ] Melhorar a interface do usuário.

## 🤝 Contribuição

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature-minha-feature`)
3. Commit suas mudanças (`git commit -m 'Adicionando minha feature'`)
4. Faça um push para a branch (`git push origin feature-minha-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📚 Referências

- [Documentação do Node.js](https://nodejs.org/)
- [Documentação do Express.js](https://expressjs.com/pt-br/)
- [Documentação do Socket.io](https://socket.io/)
- [Documentação do PostgreSQL](https://www.postgresql.org/docs/)