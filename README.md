# 🎲 Jogo do Número Secreto

Um jogo simples e divertido onde o objetivo é **adivinhar o número secreto** gerado aleatoriamente pelo sistema. Desenvolvido em **HTML, CSS e JavaScript**.

---

## 🖼️ Prévia do Projeto

![Screenshot do Jogo](./img/ia.png)

---

## 🚀 Funcionalidades

- Sorteio aleatório de números **entre 1 e 50** (configurável).
- Feedback dinâmico para o jogador:
  - "O número secreto é maior" ou "O número secreto é menor".
- Contagem de tentativas até acertar.
- Botão para reiniciar o jogo após vitória.
- **Leitura em voz** do texto usando [ResponsiveVoice](https://responsivevoice.org/).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do projeto.
- **CSS3**: Estilização e layout responsivo.
- **JavaScript (ES6+)**: Lógica do jogo e manipulação do DOM.
- **ResponsiveVoice.js**: Conversão de texto em voz.

---


---

## ▶️ Como Jogar

1. Abra o arquivo `index.html` no navegador.
2. Escolha um número entre **1 e 50**.
3. Clique em **Chutar**:
   - Se errar, receberá uma dica se o número é maior ou menor.
   - Se acertar, verá o total de tentativas e poderá iniciar um novo jogo.
4. Clique em **Novo jogo** para reiniciar.

---

## 🔧 Como Executar

Você pode clonar o repositório e abrir localmente:

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/jogo-numero-secreto.git

# Acessar a pasta
cd jogo-numero-secreto

# Abrir no navegador
start index.html   # Windows
xdg-open index.html # Linux
open index.html    # macOS
