# TCC – Sistema de Gerenciamento de Ordens de Manutenção Automotiva

Projeto desenvolvido como Trabalho de Conclusão de Curso (TCC) no curso técnico em Informática. Trata-se de um sistema para gerenciar ordens de manutenção automotiva, construído com tecnologias como **Node.js, JavaScript, jQuery, HTML, CSS, EJS e Less**.

---

## 📑 Índice

1. [Descrição](#descrição)  
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)  
3. [Estrutura do Projeto](#estrutura-do-projeto)  
4. [Pré-requisitos](#pré-requisitos)  
5. [Instalação](#instalação)  
6. [Execução](#execução)  
7. [Funcionalidades](#funcionalidades)  
8. [Banco de Dados](#banco-de-dados)  
9. [Contribuição](#contribuição)  
10. [Licença](#licença)

---

## 📖 Descrição

Este projeto tem como objetivo oferecer um sistema completo de gerenciamento de **ordens de manutenção automotiva**, auxiliando oficinas e empresas do setor a organizar clientes, veículos, serviços e histórico de manutenções.

A interface foi desenvolvida com tecnologias web modernas, garantindo um sistema dinâmico, responsivo e fácil de usar.

---

## 🛠 Tecnologias Utilizadas

- **Node.js** – backend da aplicação  
- **JavaScript** – lógica de front-end  
- **jQuery** – manipulação DOM e integração via AJAX  
- **HTML / CSS / Less** – estruturação e estilização das páginas  
- **EJS** – templates no servidor para páginas dinâmicas  
- **MySQL (estimado)** – banco de dados relacional  

---

## 📂 Estrutura do Projeto

```
├── src/                   # Código-fonte da aplicação (rotas, lógicas e controllers)
├── public/                # Arquivos públicos (CSS, JS, imagens)
├── views/                 # Templates EJS para renderização das páginas
├── sessions/              # Configuração de sessões e autenticação
├── BANCODEDADOSTCC.txt    # Arquivo com instruções/scripts do banco de dados
├── package.json           # Dependências e scripts do npm
└── package-lock.json      # Versão exata das dependências
```

---

## ⚙️ Pré-requisitos

Antes de executar o projeto, instale:

- [Node.js](https://nodejs.org/)  
- [npm](https://www.npmjs.com/)  
- [MySQL](https://dev.mysql.com/downloads/) (ou outro, conforme `BANCODEDADOSTCC.txt`)

---

## 📦 Instalação

Clone o repositório e instale as dependências:

```cmd ou powershell
git clone https://github.com/joaovictoresilva123/TCC---Sistema-de-Gerenciamento-de-Ordens-de-manutencao-automotiva.git
cd TCC---Sistema-de-Gerenciamento-de-Ordens-de-manutencao-automotiva
npm install
```

---

## 🚀 Execução

1. Configure o banco de dados conforme instruções do arquivo `BANCODEDADOSTCC.txt`.  
2. Inicie o servidor:  

```cmd ou powershell
npm start
```

3. Acesse no navegador:  

```
http://localhost:3000
```

---

## ✅ Funcionalidades

- Cadastro, listagem e edição de **ordens de manutenção**  
- Registro de **clientes e veículos**  
- Gestão de **serviços realizados**  
- Controle de **autenticação e sessões**  
- Interface dinâmica com **jQuery + AJAX**  
- Banco de dados com tabelas pré-definidas  

---

## 🗄 Banco de Dados

O arquivo `BANCODEDADOSTCC.txt` contém:

- Estrutura de tabelas  
- Scripts de criação  
- Instruções de configuração  

Sugestão: importar o arquivo em um banco **MySQL** para inicializar as tabelas.

---



