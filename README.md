# Projeto2
# 🚀 LeIA

**Resumo:** 
Este projeto é uma aplicação de interface gráfica desenvolvida em Python que utiliza a API da OpenAI para gerar resumos detalhados de livros. O usuário insere o título de um livro e recebe um resumo envolvente, sem spoilers pesados, facilitando a compreensão da obra antes da leitura completa. A solução é voltada para leitores, estudantes e profissionais que buscam conhecer rapidamente o conteúdo de livros.
---

## 🎯 Objetivo

O principal objetivo deste projeto é desenvolver uma ferramenta prática e acessível que permita aos usuários obter resumos detalhados e de qualidade de livros variados de forma rápida e automatizada. O sistema resolve o problema da dificuldade que muitas pessoas enfrentam ao tentar decidir quais livros ler ou ao buscar compreender a essência de uma obra sem a necessidade de ler o texto completo.
A motivação para o desenvolvimento do projeto vem da crescente demanda por soluções que facilitem o acesso ao conhecimento e otimizem o tempo do usuário, utilizando tecnologias modernas de inteligência artificial para gerar conteúdos personalizados e relevantes.
Além disso, o projeto integra conhecimentos essenciais da disciplina, como programação em Python, desenvolvimento de interfaces gráficas com Tkinter, consumo de APIs externas (OpenAI), tratamento de exceções, manipulação de imagens e gestão de estados em interfaces. Assim, ele serve como uma aplicação prática que demonstra a integração entre teoria e prática, mostrando como algoritmos e tecnologias atuais podem ser usados para resolver problemas reais.

---

## 👨‍💻 Tecnologias Utilizadas

Linguagem de Programação:
Python 3.x

Bibliotecas para Interface Gráfica:
tkinter — Biblioteca padrão do Python para criação de interfaces gráficas (GUI).
ttk (Themed Tkinter) — Complemento do tkinter para widgets com aparência moderna.
scrolledtext — Widget de texto com barra de rolagem integrada.

Manipulação de Imagens:
Pillow (PIL) — Biblioteca para abrir, redimensionar e manipular imagens.

Integração com API de Inteligência Artificial:
openai (OpenAI Python SDK) — Cliente oficial para consumir a API da OpenAI e gerar resumos via modelos GPT.

---

## 🗂️ Estrutura do Projeto

```
📦 Projeto
├── 📁 app
│   ├── main.py                 
│   ├── api.py                  
│   ├── gui.py                  
│   ├── utils.py               
│   └── assets
│       └── logo.png            
├── README.md                   
├── requirements.txt           
└── .env
---

## ⚙️ Como Executar

### ✅ Rodando Localmente

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/seu-projeto.git
cd nome-do-projeto
```

2. Crie o ambiente virtual e ative:

```
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
```

3. Instale as dependências: 

```
pip install -r requirements.txt
pip install openai
pip install pillow
```

4. Execute a aplicação:

```
python testsfinal.py
```

---

## 📸 Demonstrações

Inclua aqui prints, gifs ou vídeos mostrando a interface ou o funcionamento do sistema:

- Tela inicial
- Exemplo de funcionalidade
- Resultados esperados

---

## 👥 Equipe

| Nome | GitHub |
|------|--------|
| Gustavo Gomes Guimarães | [@GustavG3](https://github.com/GustavG3/Projeto2) |
| Paulo Resende Tironi Ferreira | [@Paulo](https://github.com/exemplo) |

---

## 🧠 Disciplinas Envolvidas

- Estrutura de Dados I
- Teoria dos Grafos
- Linguagens Formais e Autômatos

---

## 🏫 Informações Acadêmicas

- Universidade: **Universidade Braz Cubas**
- Curso: **Ciência da Computação / Análise e Desenvolvimento de Sistemas**
- Semestre: 2º / 3º / 4º / 5º / 6º
- Período: Manhã / Noite
- Professora orientadora: **Dra. Andréa Ono Sakai**
- Evento: **Mostra de Tecnologia 1º Semestre de 2025**
- Local: Laboratório 12
- Datas: 05 e 06 de junho de 2025

---

## 📄 Licença

MIT License — sinta-se à vontade para utilizar, estudar e adaptar este projeto.
