# Landing Page - Trilha de CSS da DIO 🎨

Este projeto é uma landing page desenvolvida como parte do **Desafio 01** da **Trilha de CSS** da [DIO](https://www.dio.me/). O HTML foi fornecido como base e a proposta consistia em aplicar **todo o CSS do zero**, praticando os principais fundamentos da linguagem de estilização.

> 🔄 Este projeto é um **fork** do repositório original disponibilizado pela DIO, no qual o HTML já foi estruturado, cabendo ao participante a responsabilidade de aplicar os estilos CSS.

---

## 💻 Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts (Raleway)

---

## 🧠 Conceitos de CSS aplicados

Durante o desenvolvimento da estilização da página, foi possível colocar em prática diversos conceitos importantes do CSS, como:

### 🎯 Estilização Global
- Uso do seletor universal `*` para reset de margens e paddings.
- Definição de `box-sizing: border-box` para controle previsível de tamanhos.

### 🎨 Tipografia e Cores
- Importação de fontes personalizadas via `@import` do Google Fonts.
- Aplicação de gradientes com `background: linear-gradient` combinados com `-webkit-background-clip: text` para efeito de texto com gradiente.

### 🖼️ Imagens e Fundos
- Uso de `background-image` para imagens com sobreposição de gradientes.
- Propriedade `background-attachment: fixed` para efeito parallax simples.
- Controle de `background-size: cover` para preencher áreas.

### 📐 Layout e Box Model
- `display: flex` e `flex-direction`, `justify-content` e `align-items` para criação de layouts flexíveis e responsivos.
- Utilização de `text-align`, `margin`, `padding` e `border` para estruturação e espaçamento dos elementos.

### 💡 Componentização Visual
- Criação de componentes reutilizáveis, como os blocos de módulos (`.module`), com uso de `border-radius`, `box-shadow` e `hover effects`.

### 🔧 Detalhes visuais e refinamento
- Uso de `text-transform`, `letter-spacing` e `text-shadow` para realce tipográfico.
- Estilização de botões com `border-image`, `text-transform` e `font-weight`.

---

# Desafio 01: Criando sua primeira Landing Page com HTML e CSS

Bem vindo(a) ao primeiro desafio da Trilha de CSS da DIO! Nela, você vai construir sua primeira Landing Page com HTML e CSS, colocando em prática os fundamentos do CSS,
as propriedades básicas da linguagem de estilização, além de trabalhar com as unidades de medidas relativas e absolutas que aprendemos ao longo da trilha.

[Clique aqui](https://micheleambrosio.github.io/dio-trilha-css-desafio-01/) para acessar o resultado final da Landing Page criada a partir do desafio!

![image](https://user-images.githubusercontent.com/55519539/183538055-6cce606c-7d1d-4d15-a4be-ffeb5b37c956.png)

Para você realizar o desafio, basta fazer um **fork** para o seu GitHub e começar a mexer no projeto.
Dentro da pasta *main*, você vai encontrar todas as imagens e o arquivo HTML, contendo a estrutura básica da sua página, faltando apenas
realizar a estilização da sua página. É necessário que você faça toda a parte responsável por interligar sua página HTML com suas folhas
de estilo para que o resultado da estilização funcione.

[Link do Figma](https://www.figma.com/file/3PiokoJj9IhGDnNiWAJbz7/DIO---Desafio-01?node-id=2%3A6) contendo o protótipo do desafio para
que você possa se basear.

*Observações: para aplicar os textos em gradiente, utilize a propriedade CSS background-clip, porém, para funcionar em alguns navegadores,
é necessário utilizar a propriedade -webkit-background-clip: text;*

Caso tenha alguma dúvida, ou queira comparar o resultado do desafio que você fez, nós temos o site finalizado na branch *final*. Basta alterar a branch do projeto
utilizando o comando `git checkout final` no seu terminal.
