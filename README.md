# 🧮 Calculadora Web

Este projeto é uma calculadora simples desenvolvida com **HTML**, **CSS** e **JavaScript**, que permite realizar operações básicas de forma interativa e responsiva. Ideal para fins educacionais e como base para projetos mais complexos.

## 🚀 Funcionalidades

- Adição, subtração, multiplicação e divisão  
- Suporte a parênteses e números decimais  
- Interface amigável e responsiva  
- Suporte ao uso do teclado:
  - Números e operadores matemáticos
  - `Enter`: calcula o resultado
  - `Backspace`: apaga o último caractere
  - `Escape`: limpa o display

## 📂 Estrutura do Projeto

```plaintext
calculadora/
├── index.html         # Estrutura HTML da calculadora
├── calculadora.css    # Estilos da calculadora
└── README.md          # Documentação do projeto
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**

## 💡 Como Usar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Use o mouse ou o teclado para realizar os cálculos.

## 🧩 Código JavaScript - Principais Funções

- `adicionarCaractere(caractere)`: adiciona números ou operadores ao display.
- `limpar()`: limpa toda a expressão.
- `apagar()`: apaga o último caractere inserido.
- `calcular()`: executa a expressão matemática usando `eval()` com tratamento de erro.

## ⚠️ Aviso de Segurança

O uso da função `eval()` facilita a avaliação de expressões, mas **não é recomendado para aplicações em produção** sem tratamento adicional, pois pode representar risco de segurança se não for bem controlada.
