# Animação de Quadrado com GSAP

Este é um projeto introdutório de animação web utilizando a biblioteca **GSAP (GreenSock Animation Platform)**. O objetivo é demonstrar como manipular propriedades CSS de elementos HTML através de JavaScript de forma performática e simples.

## O que este projeto faz?

O projeto exibe um quadrado roxo centralizado em uma tela preta. Ao carregar a página, o GSAP executa uma animação que:
1.  Move o quadrado **200px para baixo** (eixo Y).
2.  Altera a cor de fundo de **roxo para amarelo**.
3.  Realiza essa transição suavemente ao longo de **4 segundos**.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página.
* **CSS3:** Estilização e layout (Flexbox para centralização).
* **JavaScript:** Lógica da animação.
* **GSAP (via CDN):** Biblioteca externa responsável pela animação.

## Estrutura dos Arquivos

```text
/
├── index.html
├── style.css            
└── script.js 

## Como executar o projeto

1.  **Clone este repositório** (ou baixe os arquivos):
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
    ```
2.  **Abra o arquivo** `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).

## Exemplo de Código

A animação acontece nesta linha do arquivo `script.js`:

```javascript
// Move o elemento .quadrado para y:200 e muda a cor para amarelo em 4 segundos
gsap.to(".quadrado", {
    y: 200, 
    duration: 4, 
    backgroundColor: "yellow"
});
