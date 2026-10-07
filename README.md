# 🥖 GagaPão 🥐

> [!NOTE]
> Calculadora de massa de pão feita com muito carinho. **Foco principal:** digitar o
> peso da farinha e ver, na hora, quanto vai de água, fermento e sal, sem papel, sem
> conta de cabeça e sem erro na hora de sovar.

O **GagaPão** é uma calculadora web de massa de pão que usa a **porcentagem do padeiro**:
a farinha é sempre **100%** e todos os outros ingredientes são calculados em cima dela.
Colocou 500 g de farinha? São 500 g a 100%. Colocou 900 g? Continua sendo 100%. O resto
se preenche sozinho, de forma visual, e no final aparece o **peso total da massa**. As
porcentagens já vêm com valores de uso comum, mas podem ser alteradas na hora, para cada
receita. Tudo roda direto no navegador, sem servidor, sem cadastro e sem internet depois
de aberto. O visual é de padaria, com tons pastéis, rosa e creme, pensado principalmente
para o iPhone. Projeto pessoal, feito para ser usado de verdade na cozinha. 💕

---

## 🚧 Status do Projeto

![Status](https://img.shields.io/badge/Status-No_Forno_%F0%9F%A5%96-brightgreen?style=for-the-badge) ![HTML5](https://img.shields.io/badge/HTML5-Arquivo_%C3%9Anico-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-Anima%C3%A7%C3%B5es-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-Puro-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Publicado-222222?style=for-the-badge&logo=github&logoColor=white)

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Como Funciona a Conta](#-como-funciona-a-conta)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Instruções de Utilização](#-instruções-de-utilização)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Autor](#-autor)
- [Agradecimentos](#-agradecimentos)

---

## 🔗 Links Úteis
* 🌐 **Calculadora no ar** (GitHub Pages): [gabriel200481.github.io/massa-de-pao](https://gabriel200481.github.io/massa-de-pao/). É só abrir no navegador, sem instalar nada.
* 💻 **Repositório**: [github.com/Gabriel200481/massa-de-pao](https://github.com/Gabriel200481/massa-de-pao)
* 📱 **Dica para o celular**: no Safari, toque em Compartilhar e depois em **Adicionar à Tela de Início**, e a calculadora vira um "aplicativo".

---

## 📝 Sobre o Projeto

O GagaPão nasceu de uma necessidade simples da cozinha: toda vez que a quantidade de
farinha muda, as outras medidas mudam junto, e fazer essa conta com as mãos cheias de
massa é um convite ao erro. A ideia foi tirar a conta do caminho, para sobrar atenção para
o que importa: a hidratação, o ponto da massa e o cheirinho de pão saindo do forno.

Por ser um arquivo único, sem servidor e sem banco de dados, ele pode ser enviado a
qualquer pessoa e funciona em qualquer navegador moderno. A escolha por HTML, CSS e
JavaScript puros mantém tudo leve, rápido e fácil de entender e de mexer.

---

## ✨ Funcionalidades Principais

- 🌾 **Farinha como base:** digite o peso da farinha em gramas; ela é sempre 100%.
- 💧 **Água automática:** padrão de **64%**, editável.
- 🫧 **Fermento automático:** padrão de **35%**, editável.
- 🧂 **Sal automático:** padrão de **2,4%**, editável.
- ⚖️ **Peso total da massa:** a soma de todos os ingredientes, sempre à vista.
- 🔢 **Pesos inteiros:** valores arredondados para 1 g (ou 1 ml), como numa balança de
  cozinha, e o total soma exatamente o que está na tela.
- ⌨️ **Vírgula ou ponto:** aceita `2,4` e `2.4`; no iPhone abre o teclado numérico.
- 🎞️ **Animações fofas:** os blocos entram em cascata, o pãozinho balança, os números
  "contam" até o valor novo e bolinhas de fermentação flutuam no fundo.
- 🎉 **Pãozinho pulão:** toque no pão do topo e ele pula esmagadinho, soltando confetes
  de farinha, brilhos e corações.
- 💫 **Reação ao digitar:** a cada mudança, o cartão dá uma "sambadinha", um brilho passa
  pelo total e uma chuvinha de confetes sobe.
- 🫶 **Ícones com vida:** a gotinha de água pula, as bolhas do fermento pulsam, o sal
  sacode e a espiga de trigo balança. O coração do rodapé bate.
- 📱 **Responsivo:** pensado para o iPhone 16, mas se adapta a telas maiores e menores.
- ♿ **Respeita "Reduzir movimento":** quem desliga as animações no celular não as vê.

---

## 🧮 Como Funciona a Conta

Cada ingrediente é calculado em cima do peso da farinha:

```text
peso do ingrediente = farinha × porcentagem ÷ 100
peso total          = farinha + água + fermento + sal
```

Exemplo com os valores padrão (farinha de **500 g**):

| Ingrediente | Porcentagem | Quantidade |
|---|:---:|:---:|
| 🌾 Farinha | 100% | 500 g |
| 💧 Água | 64% | 320 ml |
| 🫧 Fermento | 35% | 175 g |
| 🧂 Sal | 2,4% | 12 g |
| ⚖️ **Total** | | **1.007 g** |

Considera-se que 1 ml de água pesa 1 g.

---

## 🛠 Tecnologias Utilizadas

### 💻 Front-end
* **HTML5** e **CSS3** (variáveis, grid, flexbox e animações com `@keyframes`)
* **JavaScript** puro, sem bibliotecas e sem dependências externas

### ☁️ Hospedagem
* **GitHub Pages** (camada gratuita)

---

## 🔧 Instruções de Utilização

### 🌐 Opção 1: pelo link (recomendado)

Abra [gabriel200481.github.io/massa-de-pao](https://gabriel200481.github.io/massa-de-pao/)
no Safari, no Chrome ou em qualquer navegador. É o caminho que funciona em todos os
celulares.

### 📁 Opção 2: pelo arquivo, no computador

1. Baixe o arquivo `GagaPão.html` (ou o `index.html` do repositório).
2. Dê dois cliques nele. Ele abre no navegador e funciona sem internet.

> [!WARNING]
> No iPhone, a **pré-visualização** de arquivos (WhatsApp, e-mail, app Arquivos) não executa
> JavaScript: os números não são calculados. Nesse caso, use o link da Opção 1.

### ✏️ Mudar os valores padrão

Abra o arquivo em um editor de texto e procure os campos de porcentagem. O número em
`value` é o valor que a página abre:

```html
<input id="p-agua"     ... value="64">
<input id="p-fermento" ... value="35">
<input id="p-sal"      ... value="2,4">
```

Se mudar os padrões, atualize também os números escritos nos `<span id="r-...">` e em
`id="total"` (são os valores mostrados quando o JavaScript está desligado).

---

## 📂 Estrutura de Pastas

~~~text
Calculadora massa de pao/
├── README.md        # Este arquivo
└── GagaPão.html     # A calculadora inteira (HTML, CSS e JavaScript)
~~~

No repositório do GitHub, o mesmo arquivo se chama `index.html`, porque o GitHub Pages
procura por esse nome para montar o site:

~~~text
massa-de-pao/
├── README.md
└── index.html
~~~

---

## 👤 Autor

| 👤 Nome | 🖼️ Foto | :octocat: GitHub |
|---|:---:|:---:|
| Gabriel Afonso Infante Vieira | <img src="https://github.com/Gabriel200481.png" width="60px"/> | [@Gabriel200481](https://github.com/Gabriel200481) |

---

## 🙏 Agradecimentos

* A quem prova cada fornada e sempre pede mais um pedacinho. 💕
* Ao fermento, que faz o milagre acontecer enquanto a gente dorme. 🫧
* A todos que gostam de pão quentinho, com manteiga derretendo. 🥖
