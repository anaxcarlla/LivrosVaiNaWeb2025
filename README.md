# Sistema de Doação de Livros

Este projeto tem como finalidade o gerenciamento de doações de livros, permitindo o cadastro e a visualização de títulos disponíveis. A solução é composta por uma interface web desenvolvida em **React**, uma API construída com **Flask**, e um banco de dados local baseado em **SQLite**.

## Tecnologias Utilizadas

- **Front-end:** React.js, Axios
- **Back-end:** Python, Flask, Flask-CORS
- **Banco de Dados:** SQLite

## Funcionalidades

- Cadastro de livros com título, autor, categoria e URL da imagem da capa.
- Listagem de livros disponíveis para doação.
- Comunicação entre front-end e back-end por meio de API REST.
- Armazenamento persistente de dados em banco SQLite.

## Instruções de Instalação

### 1. Clonagem do Repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

2. Execução do Back-end (Flask)
cd backend
pip install flask flask-cors
python app.py

3. Execução do Front-end (React)
cd frontend
npm install
npm start

