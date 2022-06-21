# Frontend Mentor - NFT Card component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](./images/Captura%20da%20Web_21-6-2022_145526_127.0.0.1.jpeg)
![](./images/Captura%20da%20Web_21-6-2022_145538_127.0.0.1.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Treinando a utilização do CSS

To see how you can add code snippets, see below:

```html
```

Adicionando posição relativa na classe mãe e absoluta na classe filho para que ocorra sobreposição de imagens.

```css
.card__imagem {
    position: relative;
}

.card__imagem-base {
    height: 302px;
    margin:24px;
    border-radius: 10%;
}

.imagem-transicao {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 302px;
    width: 302px;
    position: absolute;
    top: 0;
    margin: 24px;
    background-color: rgba(0, 255, 247, .5);
    border-radius: 10%;
    transition: .3s;
    opacity: 0;
    cursor: pointer;
    
}

.imagem-transicao:hover {
    opacity: 1;
}

```

### Continued development

Vou continuar criando sites utilizando HTML e CSS para praticar e inplementar o JS.


### Useful resources

- FrontEndMentor
- Alura Cursos

## Author

- Frontend Mentor - [@hugoborgess](https://www.frontendmentor.io/profile/HugoBorgess)


## Acknowledgments

