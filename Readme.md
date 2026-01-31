# 🎮 Jokenpo - Pedra, Papel e Tesoura

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</div>

> Jogo clássico de Pedra, Papel e Tesoura desenvolvido durante a formação **DevClub**. Desafie a Alexa e teste sua sorte!

---
## Demonstrações
<img src="./assets/Captura de tela 2026-01-31 172148.png" />
<img src="./assets/Captura de tela 2026-01-31 172200.png" />
## 📋 Sobre o Projeto

Jogo interativo de Jokenpo (Pedra, Papel e Tesoura) onde você compete contra a Alexa (inteligência artificial). O jogo conta pontos, exibe as escolhas de cada jogador e determina o vencedor em tempo real.

**Características:**
- Interface limpa e intuitiva
- Sistema de pontuação persistente durante a sessão
- Feedback visual ao passar o mouse nos botões
- Responsivo para dispositivos móveis
- Escolhas aleatórias da máquina usando JavaScript

---

## 🎯 Funcionalidades

✅ Escolha entre **Pedra**, **Papel** ou **Tesoura**  
✅ **Pontuação em tempo real** — acompanhe seu desempenho vs Alexa  
✅ **Feedback visual** — mostra sua escolha e a escolha da Alexa  
✅ **Resultado instantâneo** — vitória, derrota ou empate  
✅ **Responsivo** — funciona perfeitamente em mobile e desktop  
✅ **Efeitos hover** — animações suaves ao passar o mouse  

---

## 🕹️ Como Jogar

1. Clique em uma das três opções: **Pedra**, **Papel** ou **Tesoura**
2. A Alexa fará sua escolha aleatoriamente
3. O resultado aparece instantaneamente:
   - **Pedra** vence **Tesoura**
   - **Papel** vence **Pedra**
   - **Tesoura** vence **Papel**
4. Acompanhe a pontuação e continue jogando!

---
## Acesse
 [JokenPo](https://jogojokenpoh.netlify.app/)
## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica
- **CSS3** — Estilização e responsividade
- **JavaScript (Vanilla)** — Lógica do jogo e interatividade

---

## 📁 Estrutura do Projeto

```
jokenpo/
├── index.html          # Estrutura HTML
├── styles.css          # Estilos e responsividade
├── javascript.js       # Lógica do jogo
└── assets/             # Imagens
    ├── pedra.png
    ├── papel.png
    └── tesoura.png
```

---

## 💻 Demonstração

### Desktop
- Interface centralizada
- Botões lado a lado
- Hover effects com cores distintas

### Mobile
- Layout vertical responsivo
- Botões empilhados para melhor experiência touch
- Mesma funcionalidade em telas pequenas

---

## 🎨 Destaques do Código

### Lógica de Jogo
```javascript
const playTheGame = (human, machine) => {
    if (human === machine) {
        result.innerHTML = "Deu empate"
    } else if (
        (human === 'paper' && machine === 'rock') ||
        (human === 'rock' && machine === 'scissors') ||
        (human === 'scissors' && machine === 'paper')
    ){
        humanScoreNumber++
        result.innerHTML = "Você ganhou!" 
    } else {
        machineScoreNumber++
        result.innerHTML = "Você perdeu para Alexa!" 
    }
}
```

### Escolha Aleatória da Máquina
```javascript
const playMachine = () => {
    const choices = ['rock', 'paper', 'scissors']
    const randomNumber = Math.floor(Math.random() * 3)
    return choices[randomNumber]
}
```


## 🎓 Aprendizados

Durante o desenvolvimento deste projeto na formação DevClub, pratiquei:

- ✅ Manipulação do DOM com JavaScript
- ✅ Event listeners e funções de callback
- ✅ Lógica condicional para regras de jogo
- ✅ Geração de números aleatórios
- ✅ Media queries para responsividade
- ✅ Hover effects e transições CSS
- ✅ Estruturação semântica de HTML

---


## 📞 Contato

- 📧 **Email**: hernandesneves07@gmail.com
- 💼 **LinkedIn**: [linkedin.com/in/hernandes-sales](https://linkedin.com/in/hernandes-sales)
- 🐙 **GitHub**: [@hernandessn](https://github.com/hernandessn)

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais durante a formação DevClub.

---

<div align="center">
  <p><strong>Desenvolvido com 💙 durante a formação DevClub</strong></p>
  <p>Projeto acadêmico - 2024</p>
</div>