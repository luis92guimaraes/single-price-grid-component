# Frontend Mentor Challenge | Single Price Grid Component


#### Este é mais um desafio vindo do @Frontendmentor, é um exemplo de um menu para assinatura.

## Índice

- [Capturas de telas](#capturas-de-telas)
- [Links](#links)
- [Construído com](#construído-com)
- [O que aprendi](#o-que-aprendi)
- [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Recursos úteis](#recursos-úteis)
- [Luis Fernando Guimaraes](#autor)

### Capturas de telas

#### Tela Desktop

<img src="./src/images/desktop.gif" alt="Tela desktop exibindo funcionalidades">

#### Tela Ipad

<img src="./src/images/ipad.gif" alt="Tela tablet exibindo funcionalidades">

#### Tela Mobile

<img src="./src/images/mobile.gif" alt="Exibindo responsividade no mobile">

### Links

- Site URL: https://luis92guimaraes.github.io/stats-preview-card-component/

### Construído com

<div style="display: inline_block"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">     
</div>

### O que aprendi

Esse exercicio é proposto dentro do site @Frontend Mentor, foi um exercício que me permitiu ampliar meu conhecimento com o uso da propriedade Grid. 

## Trechos de códigos

```
main {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    padding: 40px;
}

.container {
    display: grid;
    grid-template-areas: "content1 content1"
    "content2 content3";
    grid-template-rows: repeat(2, 300px);
    grid-template-columns: repeat(2, 450px);
    border-radius: 10px;
    box-shadow: 10px 10px 10px gainsboro;
}

.content1 {
    grid-area: content1;
    background-color: #fff;
    padding: 40px;
    display: flex;
    flex-direction: column;
    border-radius: 10px 10px 0 0;
}
```

### Desenvolvimento contínuo

Pretendo continuar aprendendo cada vez mais sobre as ferramentas utilizadas nesse projeto, ainda tem muita coisa pra ser absorvida mas sigo confiante e feliz em estar conseguindo tornar meu conhecimento solido e poder realizar projetos como esse com mais clareza e confiança a cada dia de estudos.

### Recursos úteis

- [Mdn](https://developer.mozilla.org/en-US/) - O Mozilla Developer Network (MDN) desempenha um papel crucial ao fornecer recursos abrangentes e atualizados para desenvolvedores web em todo o mundo.
- [W3School](https://www.w3schools.com/css/default.asp) - Esse site sempre me ajuda a resolver qualquer problema relacionados a códigos de uma maneira fácil e muito rápida.
- [Dev em Dobro](https://www.youtube.com/@DevemDobro) - Este é um canal onde encontro muito material. Tem muito conteúdo relacionado ao desenvolvimento. Recomendo a todos que querem aprender sobre esse e outros conceitos relacionados.

## Autor

[Luis Fernando Guimarães](https://www.linkedin.com/in/luisfguimaraes/)
