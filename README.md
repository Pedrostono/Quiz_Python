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
    uvicorn main:app --reload

4. Caso não funcione, tente:
    python -m uvicorn main:app --reload