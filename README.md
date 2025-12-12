# Python Web Quiz (Academic Project)

This is an **academic project**, created exclusively for educational purposes. It demonstrates concepts of web development in Python, the use of Factory and Decorator design patterns, and integration with a MongoDB database.  
The application consists of a web-based quiz with scoring, dynamic questions, and a user ranking system.

## How the Application Works

The application has three main pages:

### Registration
The user enters their name, which will be used to record responses and scores.

### Quiz
Displays questions created dynamically through a Factory.  
A Decorator can transform regular questions into bonus questions.  
At the end, the score is calculated and saved to the database.

### Results and Ranking
Displays the final score and the overall user ranking retrieved from MongoDB.

---

## Architecture and Concepts Used

- **Factory Pattern:** dynamic creation of questions.  
- **Decorator:** transforms regular questions into bonus questions.  
- **MongoDB:** stores responses, scores, and ranking data.

---

## 📦 Installation and Execution

Install the dependencies:

1. Install Python.

2. In the command prompt, inside the *Quiz* folder, run:
   ```bash
   pip install -r requirements.txt

3. run: 
    ```bash
    uvicorn main:app --reload

4. if it does not work, try:
    ```bash
    python -m uvicorn main:app --reload


#Português
# Quiz Web em Python (Projeto Acadêmico)

Este é um **projeto acadêmico**, criado exclusivamente para fins educacionais. Ele demonstra conceitos de desenvolvimento web em Python, uso dos padrões de projeto Factory e Decorator e integração com banco de dados MongoDB.  
A aplicação consiste em um quiz web com pontuação, perguntas dinâmicas e ranking de usuários.

## Como funciona a aplicação

A aplicação possui três páginas principais:

### Cadastro
O usuário insere o nome, que será usado para registrar respostas e pontuações.

### Quiz
Exibe perguntas criadas dinamicamente por um Factory.  
Um Decorator pode transformar perguntas comuns em perguntas bônus.  
Ao final, a pontuação é calculada e salva no banco.

### Resultados e Ranking
Exibe pontuação final e o ranking geral dos usuários, consultado no MongoDB.

---

## Arquitetura e Conceitos Usados

- **Factory Pattern:** criação dinâmica de perguntas.  
- **Decorator:** transforma perguntas em perguntas bônus.  
- **MongoDB:** armazena respostas, pontuação e ranking.

---

## 📦 Instalação e Execução

Instale as dependências:  

1. Instale Python

2. Insira o seguinte código no cmd, dentro da pasta Quiz:
   ```bash
   pip install -r requirements.txt

3. Rode: 
    ```bash
    uvicorn main:app --reload

4. Caso não funcione, tente:
    ```bash
    python -m uvicorn main:app --reload