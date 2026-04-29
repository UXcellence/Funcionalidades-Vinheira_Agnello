# 🍷 Vinheria Agnello — Funcionalidades JS

Projeto acadêmico de **Web Development** com foco em lógica de programação com JavaScript. Contém uma série de exercícios que cobrem os principais conceitos fundamentais da linguagem, exibidos em uma página simples da Vinheria Agnello.

---

## 📋 Sobre o Projeto

Esta aplicação é uma página web simples (`index.html`) que serve de base para a execução de exercícios JavaScript. Os exercícios abordam desde tipos de variáveis e operadores até manipulação do DOM, sendo todos resolvidos no arquivo `script.js`.

---

## 📚 Exercícios Implementados

### Exercício 1 — Tipos de Variáveis
Demonstração dos diferentes estados de uma variável em JavaScript:
- Variável declarada sem valor (`undefined`)
- Variável com string vazia
- Variável com valor atribuído

### Exercício 2 — Operadores de Comparação
Comparação entre variáveis usando os operadores `!=`, `==`, `===` e `>=`, com destaque para a diferença entre igualdade abstrata (`==`) e estrita (`===`).

### Exercício 3 — Calculadora de IMC
Solicita peso e altura via `prompt` e calcula o IMC do usuário. Utiliza estrutura `switch(true)` para classificar o resultado em:
- Abaixo do peso (IMC < 18.5)
- Peso ideal (18.5 ≤ IMC ≤ 24.9)
- Acima do peso (IMC > 24.9)

### Exercício 4 — Estrutura de Repetição
Loop `for` que itera e exibe no console os números de 1 a 50.

### Exercício 5 — Sistema de Login
Simula uma autenticação de usuário com `prompt`. Valida usuário e senha usando comparação estrita (`===`) e exibe mensagem de sucesso ou falha no console.
- **Usuário:** `admin`
- **Senha:** `1234`

### Exercício 6 — Cálculo de Média com Aprovação
Coleta 7 notas via `prompt`, calcula a média aritmética e informa via console se o aluno foi **aprovado** (média ≥ 6) ou **reprovado**.

### Exercício 7 — Manipulação do DOM
Coleta dados do aluno (nome, idade, curso e ano) via `prompt` e os exibe dinamicamente na página HTML usando `document.getElementById` e `innerHTML`.

### Exercício 8 — Métodos de String
Aplica métodos de string sobre um texto fixo:
- `indexOf()` — primeira ocorrência de `"em"`
- `lastIndexOf()` — última ocorrência de `"ia"`
- `includes()` — verifica a presença de `"ciência"` e `"métodos"`

### Exercício 9 — Conversão de Tipos
Converte uma string numérica (`"321.12"`) para número com `parseFloat`, identifica se é inteiro ou float com `Number.isInteger()` e exibe o tipo com `typeof`.

---

## 🗂️ Estrutura de Arquivos

```
Funcionalidades-Vinheira_Agnello-main/
├── index.html          # Página principal com estrutura e estilo inline
├── Equipe.txt          # Integrantes do grupo
└── src/
    └── js/
        └── script.js   # Todos os exercícios JavaScript
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Estilo inline (cor de fundo, tipografia) |
| JavaScript | Lógica dos exercícios e manipulação do DOM |

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/UXcellence/Funcionalidades-Vinheira_Agnello.git
   ```

2. Abra o arquivo `index.html` diretamente no navegador.

> ⚠️ O projeto utiliza `prompt()` para entrada de dados. Certifique-se de que o navegador não está bloqueando pop-ups. Os resultados dos exercícios 1 a 6 e 8 a 9 são exibidos no **console do navegador** (F12). O exercício 7 exibe os dados diretamente na página.

---

## 👩‍💻 Equipe

Projeto desenvolvido por alunas da FIAP:

| Nome | RM |
|---|---|
| Giovanna Lins Sayama | 565901 |
| Ana Luiza De Franco e Rinaldi | 564061 |
| Giovana Gaspar Larocca | 564965 |
| Rayssa Luzia Portela Aquino | 562024 |
| Kimberly Kristina Oliveira Silva | 564080 |

---

## 📄 Licença

Projeto acadêmico desenvolvido para fins educacionais. © 2025 — Todos os direitos reservados.
