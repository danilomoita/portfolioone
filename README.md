# Challenge ONE | Front End - Portfólio
---

<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/168887837-b6d26532-6782-48dc-92eb-e48bf6c57a15.png">
</p>

###  Primeiros Passos:
---
#### 🔹Marque esse projeto com uma ⭐
#### 🔹Siga as orientações do que temos neste repositório 📚


### Analisando nosso repositório!
---
### Este é o repositório base do nosso projeto, nele voce encontrará:
#### 🔹index.html: Documento HTML finalizado que você pode utilizar em seu projeto. Fonte, CSS e JavaScript já linkado e todas as sessões comentadas. Sinta-se a vontade para executar o seu próprio HTML caso deseje;
#### 🔹style.css: Documento de CSS com instruções de estilo e também algumas sugestões para seu desenvolvimento
#### 🔹validacao.js: Documento vazio para que possa aplicar sua lógica de programação, trabalhando com a validação de formulário em JavaScript
#### Ao clonar, ou realizar o download do projeto base, você tera essa apresentação:


<p align="center" >
     <img width="600" heigth="600" src="https://user-images.githubusercontent.com/101413385/168888313-d031e9e1-1449-4b73-bd3c-3102223097f3.png">
</p>




<!-- /*CSS Reset / Normalize*/
/*Já deixaremos o básico de reset de estilos. Caso queira adicionar mais informações
coloque nas sessões indicadas*/

:root {
    /*Insira a variavel das outras cores inspecionando o modelo do figma*/
    /*Se esforce para trabalhar com variáveis, é uma dica profissional valiosa*/
    --cor-de-fundo: #F5F5F5;
    --cor-de-link: #000;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: var(--cor-de-fundo);
    font-family: 'Raleway';
    line-height: 1;
}

ol,
ul,
li {
    list-style: none;
}

a {
    text-decoration: none;
    color: var(--cor-de-link);
}

/*Neste desafio, gostariamos que praticassem a metodologia BEM, caso seintam a vontade 
de utiliza-la. 

Mas o que é o BEM?

BEM (Block, Element, Modifier) ​​é uma abordagem baseada em componentes para o desenvolvimento
web. A ideia por trás disso é dividir a interface do usuário em blocos independentes.
Isso torna o desenvolvimento de interface fácil e rápido, mesmo com uma interface
de usuário complexa, e permite a reutilização de código existente sem copiar e colar.

Link da documentação oficial!
https://en.bem.info/methodology/quick-start/*/

/*Sessão Menu*/

.menu {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    max-width: 1136px;
    margin: 0 auto;
    margin-bottom: 2rem;
    padding: 2rem 0;

}

.menu header {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 0.5rem;


}

.menu__title {
    font-size: 1rem;
    font-weight: 700;
    color: #464646;
}

.menu nav {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 2rem;
    font-size: 1rem;
    font-weight: 500;
    color: #464646;

}

.menu__list {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 2rem;
}

.menu__list__item__contato {
    font-weight: bold;
}

/*Sessão Title*/
.title {
    max-width: 1136px;
    margin: 0 auto;
    margin-bottom: 2rem;

}

.title__div {
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;

}

.title__container {
    display: flex;
    flex-direction: column;
    padding-right: 1rem;
    gap: 1.5rem;
}

.title__bio {
    font-size: 3.25rem;
    font-weight: 700;
    color: #464646;
}

.title__subsection {
    font-size: 1.375rem;
    font-weight: 400;
    color: #464646;
}

.title__network {
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    font-size: 1rem;
    font-weight: 500;
    color: #464646;
    gap: 2rem;
}

/*Sessão About*/

.about {
    background-color: #EAF2FD;


}

.about__container {
    max-width: 1136px;
    margin: 0 auto;
    padding: 4rem 0;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    justify-content: flex;
}

.about__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
}

.about__paragraph {
    font-size: 1rem;
    font-weight: 400;
    color: #464646;
    padding-right: 24rem;
}

.about__container>img {
    width: 140px;
    height: 52px;
}

/*Sessão Skills*/

.skills {
    max-width: 1136px;
    margin: 2rem auto 5.5rem auto;
    margin-bottom: 5.5rem;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.skills__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
    text-align: center;
}

.skills__line {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1rem;
}

.skills__box>ul {
    background-color: white;
    display: flex;
    flex-direction: column;
    width: 176px;
    height: 174px;
    justify-content: flex-end;
    padding: 1rem;
}

/*Sessão Hobbies*/

.hobbies {
    max-width: 1136px;
    margin: 0 auto 5.5rem auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.hobbies__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
    text-align: center;
}

.hobbies__line {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1rem;
}

.hobbies__box>ul {
    background-color: white;
    display: flex;
    flex-direction: column;
    width: 176px;
    height: 174px;
    justify-content: flex-end;
    padding: 1rem;
}

/* Experiência Acadêmica*/

.academic {
    background-color: #EAF2FD;
}

.academic__container {
    max-width: 1136px;
    margin: 0 auto;
    padding: 5rem 0;
    display: flex;
    flex-direction: column;
    gap: 2rem;

}

.academic__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
    text-align: center;
}

.academic__courses {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 1rem;
}

.academic__courses__list {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
}


.academic__courses__item__img {
    background-color: white;
    width: 368px;
    height: 286px;
    display: flex;

}

.academic__courses__item__img>img {
    margin: auto;
}

.academic__courses__item__title {
    font-size: 1.365rem;
    font-weight: 700;
    color: #464646;
}

.academic__courses__item__subtitle {
    font-size: 1rem;
    font-weight: 500;
    color: #464646;
}

/* experiência*/

.experience {
    max-width: 1136px;
    margin: 0 auto;
    padding: 2rem 0;
    display: flex;
    flex-direction: column;
    gap: 4rem;
}

.experience__section__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
    text-align: center;
    margin-bottom: -2rem;
}

.experience__box {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 1rem;
}

.experience__box:nth-child(odd) {
    flex-direction: row-reverse;
}

.experience__info {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
}

.experience__title {
    font-size: 1.375rem;
    font-weight: bold;
    color: #464646;
}

.experience__text {
    font-size: 1rem;
    font-weight: 500;
    color: #464646;
}

.experience__botao--repo {
    width: 116px;
    height: 51px;
    background-color: #F5F5F5;
    border-color: #2A7AE4;
    color: #2A7AE4;
    font-size: 1rem;
    font-weight: 400;
}

.experience__botao--demo {
    width: 116px;
    height: 51px;
    background-color: #2A7AE4;
    border-color: #2A7AE4;
    color: #F5F5F5;
    font-size: 1rem;
    font-weight: 400;
}

/*Contato*/

.formcontato {
    background-color: #EAF2FD;
}

.formcontato__contacto {
    max-width: 1136px;
    margin: 0 auto;
    padding: 8rem 0;
    display: flex;
    gap: 1rem;
}

.formcontato__text {
    display: flex;
    flex-direction: column;
    width: 100%;

}

.formcontato__title {
    font-size: 2rem;
    font-weight: 700;
    color: #464646;
    margin-bottom: 1rem;
}

.formcontato__subtext {
    font-size: 1rem;
    font-weight: 500;
    color: #464646;
}

.formcontato__form{
    margin-top: 1rem;
}

.formcontato__form__input {
    position: relative;
    padding: 0.75rem;
    padding-top: 1.75rem;
    background-color: white;
    border-radius: 0.25rem;
    border-bottom: 1px solid #c8c8c8;
    margin-bottom: 1rem;
}

.formcontato__form__input input,
.formcontato__form__input textarea {
    all: unset;
    width: 100%;
}

.formcontato__form__input label {
    color: #a2a2a2;
    position: absolute;
    top: 0;
    left: 0.75rem;
    transform: translateY(1.375rem);
    transition: all 0.2s;
}

.formcontato__form__input input:focus+label,
.formcontato__form__input input:not(:placeholder-shown)+label,
.formcontato__form__input textarea:focus+label,
.formcontato__form__input textarea:not(:placeholder-shown)+label {
    font-size: 0.75rem;
    transform: translateY(0.5rem);
}

.formcontato__form__input:focus-within {
    border-bottom: 2px solid #2a7ae4;
}

.formcontato__form__input:focus-within label {
    color: #2a7ae4;
}

.formcontato__botao {
    background-color: #2A7AE4;
    color: white;
    width: 165px;
    height: 51px;
    border-style: none;
}

/*footeer*/

.footer {
    background-color: white;
}

.footer__rodape {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 2rem 0;
    font-size: 1rem;
    font-weight: 500;
    color: #464646;
}

/* Chegou a hora de se desafiar com a responsividade, 
utilize como referência os breakpoints @media abaixo*/

/*Tablet*/
@media (min-width: 768px) and (max-width: 1199px) {


    /* Menu */
    .menu {
        margin: 1rem;
        padding: 0;
    }

    .menu__list {
        display: none;
    }


    /*title*/
    .title {
        margin: 2rem;
    }

    .title__profile {
        width: 146px;
        height: 146px;
    }

    .title__bio {
        font-size: 1.375rem;
    }

    .title__subsection {
        font-size: 1rem;
    }

    .title__network {
        gap: 2rem;
    }

    /*About*/
    .about__container {
        margin: 0;
        padding: 2rem;
    }

    .about__title {
        font-size: 1.375rem;
    }

    .about__paragraph {
        font-size: 0.875rem;
        padding: 0;
    }


    /*Skills*/
    .skills {
        margin: 2rem;
    }

    .skills__title {
        font-size: 1.375rem;
    }

    .skills__line {
        flex-wrap: wrap;
        gap: 1rem;
        justify-content: center;
        width: 704px;
        margin: 0 auto;
    }


    .skills__box>ul {
        width: 224px;
        height: 118px;
        margin-bottom: 2rem;
    }

    /*Hobbies*/

    .hobbies {
        margin: 2rem;
        margin-bottom: 0;
    }

    .hobbies__title {
        font-size: 1.375rem;
    }

    .hobbies__line {
        flex-wrap: wrap;
        gap: 1rem;
        justify-content: center;
        width: 704px;
        margin: 0 auto;
    }

    .hobbies__box>ul {
        width: 224px;
        height: 118px;
        margin-bottom: 2rem;
    }

    /*Experiências acadêmicas*/
    .academic__container {
        padding: 2rem;
    }

    .academic__title {
        font-size: 1.375rem;
    }

    .academic__courses {
        width: 704px;
        margin: 0 auto;
    }

    .academic__courses__item__img {
        width: 224px;
        height: 118px;
    }

    .academic__courses__item__img>img {
        height: 58px;
    }

    .academic__courses__item__title {
        font-size: 1rem;
    }

    .academic__courses__item__subtitle {
        font-size: 0.875rem;
    }


    /*Experiência profissional*/

    .experience {
        margin: 0;
        gap: 4rem;
    }

    .experience__section__title {
        font-size: 1.375rem;
    }

    .experience__box {
        flex-direction: column;
    }

    .experience__box:nth-child(odd) {
        flex-direction: column;
    }

    .experience__img {
        width: 704px;
        height: 320px;
    }

    .experience__info {
        width: 704px;
    }

    .experience__title {
        font-size: 1rem;
    }

    .experience__text {
        font-size: 0.875rem;
    }

    /*Contato*/
    .formcontato__contacto {
        padding: 2rem;
    }

    .formcontato__img {
        display: none;
    }

    .formcontato__title {
        font-size: 1.375rem;
    }

    .formcontato__subtitle {
        font-size: 1rem;
    }

    .formcontato__botao {
        width: 151px;
        height: 40px;
        font-size: 0.875rem;
    }

    /*Footer*/
}

/*Mobile*/
@media (max-width: 767px) {

    /*Menu*/
    .menu {
        margin: 1rem;
        padding: 0;
    }

    .menu__list {
        display: none;
    }

    .menu__list__item__contato {
        font-weight: 400;
        font-size: 1rem;
    }

    /*Titulo*/
    .title {
        margin: 1rem;

    }

    .title__div {
        flex-direction: column;
        align-items: flex-start;
    }

    .title__profile {
        width: 98px;
        height: 98px;
    }

    .title__container {
        padding: 0;
    }

    .title__bio {
        font-size: 1.375rem;
    }

    .title__subsection {
        font-size: 0.875rem;
    }

    .title__network__item {
        font-size: 0.875rem;
        font-weight: 600;
    }

    /*Sessão sobre*/
    .about__container {
        padding: 1rem;
    }

    .about__title {
        font-size: 1.375rem;
    }

    .about__paragraph {
        font-size: 0.875rem;
        padding: 0;
    }

    /*Skills*/
    .skills {
        margin: 1rem;
    }

    .skills__title {
        font-size: 1.375rem;
    }

    .skills__line {
        flex-wrap: wrap;
        width: 328px;
        margin: 0 auto;
    }

    .skills__box {
        margin-bottom: 1rem;
    }

    .skills__box>ul {
        width: 156px;
        height: 118px;
    }

    /*Hobbies*/
    .hobbies {
        margin: 1rem;
        margin-bottom: 0;
    }

    .hobbies__title {
        font-size: 1.375rem;
    }

    .hobbies__line {
        flex-wrap: wrap;
        width: 328px;
        margin: 0 auto;
    }

    .hobbies__box {
        margin-bottom: 1rem;
    }

    .hobbies__box>ul {
        width: 156px;
        height: 118px;
    }

    /*Formação Acadêmica*/
    .academic__container {
        padding: 1rem;
    }

    .academic__title {
        font-size: 1.375rem;
    }

    .academic__courses {
        flex-direction: column;
        margin: 0 auto;
    }

    .academic__courses__item__img {
        width: 296px;
        height: 118px;
    }

    .academic__courses__item__img>img {
        height: 58px;
    }

    .academic__courses__item__title {
        font-size: 1rem;
    }

    .academic__courses__item__subtitle {
        font-size: 0.875rem;
    }

    /*Experiência Profissional*/
    .experience {
        padding: 2rem;
    }

    .experience__section__title {
        font-size: 1.375rem;
    }

    .experience__box {
        flex-direction: column;
    }

    .experience__box:nth-child(odd) {
        flex-direction: column;
    }

    .experience__info {
        width: 296px;
    }

    .experience__img {
        width: 296px;
        height: 144px;
    }

    .experience__title {
        font-size: 1rem;
    }

    .experience__text {
        font-size: 0.875rem;
    }


    /*Contato*/
    .formcontato__contacto {
        padding: 2rem;
    }

    .formcontato--esquerda {
        display: none;
    }

    .formcontato__title {
        font-size: 1.375rem;
    }

    .formcontato__subtext {
        font-size: 1rem;
    }
} -->