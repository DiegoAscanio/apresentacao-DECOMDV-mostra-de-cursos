<style>
  body {
    color: #fae5ee;
  }
  section {
    background-image: url("https://i.pinimg.com/originals/3f/0d/68/3f0d68483e9885f320de9f7c482f1bd5.gif");
    background-size: cover;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 80px;
    padding-right: 80px;
  }

  .transparent {
    background-color: transparent!important;
  }

  .transparent-table-tr-td-th {
    background-color: rgba(0, 0, 0, 0.0) !important;
  }

  .cabecalho-conteudo-container {
    display: grid;
    grid-template-rows: 150px auto auto auto;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-areas: 
        ". cabecalho ."
        "conteudo conteudo conteudo"
        "conteudo conteudo conteudo"
        "conteudo conteudo conteudo";
    height: 100%;
  }

  .corpo-docente-container {
    display: grid;
    align-items: flex-start;
    grid-template-rows: 150px auto;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-areas: 
        ". corpo-docente-titulo corpo-docente-titulo ."
        "corpo-docente-foto-1 corpo-docente-foto-2 corpo-docente-foto-3 corpo-docente-foto-4";
    height: 100%;
  }

  .corpo-docente-titulo {
    grid-area: corpo-docente-titulo;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .corpo-docente-foto-1 {
    grid-area: corpo-docente-foto-1;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .corpo-docente-foto-2 {
    grid-area: corpo-docente-foto-2;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .corpo-docente-foto-3 {
    grid-area: corpo-docente-foto-3;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .corpo-docente-foto-4 {
    grid-area: corpo-docente-foto-4;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .cabecalho {
    grid-area: cabecalho;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 5%;
    padding: 2.5%;
  }

  .conteudo {
    grid-area: conteudo;
    margin: 5%;
    padding: 2.5%;
    background-color: rgba(255,255,255,0.85);
    border-radius: 10px;
    font-size: 16px;
    text-align: justify;
  }

  .conteudo-absoluto {
    position: absolute;
    top: 30%;
    margin-left: 5%;
    margin-right: 5%;
    font-size: 28px;
    text-align: justify;
  }
  .huge {
    font-size: 32px;
  }
  .large {
    font-size: 24px;
  }
  .normal {
    font-size: 22px;
  }
  .regular {
    font-size: 18px;
  }
  .small {
    font-size: 16px;
  }
  .footnotesize {
    font-size: 14px;
  }
  .scriptsize {
    font-size: 12px;
  }
  .tiny {
    font-size: 10px;
  }
  .bold {
    font-weight: bold;
  }
  section.centered table {
    margin-left: auto;
    margin-right: auto;
  }
  section.lead p {
    text-align: justify;
    font-size: 18px;
  }
  section.lead h1, h2, h3, h4 {
    text-shadow: 4px 4px 4px rgba(200, 200, 200, 0.8);
    text-align: center;
    color: black;
  }
  section.transparent img {
    background-color: transparent!important;
  }

  .first-page-group {
    background-color: rgba(255,255,255,0.85);
    border-radius: 10px;
  }
  
  .grid-50-50 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    text-align: justify;
  }

  .grid-66-33 {
    display: grid;
    grid-template-columns: 2fr 1fr;
    text-align: justify;
  }

  .grid-75-25 {
    display: grid;
    grid-template-columns: 3fr 1fr;
    text-align: justify;
  }

  .grid-80-20 {
    display: grid;
    grid-template-columns: 4fr 1fr;
    text-align: justify;
  }

  .grid-33-66 {
    display: grid;
    grid-template-columns: 1fr 2fr;
    text-align: justify;
  }

  .grid-element {
    margin-left: 5%;
    margin-right: 5%;
    padding-left: 2.5%;
    padding-right: 2.5%;
  }
  img[alt=grid-img] {
    display: block;
    width: 100%;
  }

  img[alt=grid-img-50] {
    display: block;
    margin: auto;
    width: 50%;
  }

  img[alt=grid-img-75] {
    display: block;
    margin: auto;
    width: 75%;
  }


  img[alt=centered-img] {
    display: block;
    margin: auto;
  }

  /* logo cefet-mg */
  img[src="https://i.imgur.com/QIP7K61.png"] {
    width: 150px;
    height: 150px;
    background-color: transparent!important;
  }

  /* tio patinhas */
  img[src="https://i.imgur.com/4f2mQSd.png"] {
    margin-left: auto;
    margin-right: auto;
    border-radius: 10px;
  }

  .grid-3-3 {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 150px auto auto;
    grid-template-areas: 
        ". logo ."
        "texto texto imagem"
        "texto texto imagem";
    height: 100%;
  }
  .logo {
    grid-area: logo;
  }
  .texto {
    grid-area: texto;
    margin: 2.5%;
    padding: 2.5%;
    background-color: rgba(255,255,255,0.85);
    border-radius: 10px;
    font-size: 16px;
    text-align: justify;
  }
  .imagem {
    display: flex;
    align-items: center;
    justify-content: center;
    grid-area: imagem;
    margin: 5%;
    padding: 2.5%;
  }
  img[alt=professor] {
    display: block;
    width: 100%;
    border-radius: 10px;
  }
  .legenda-professor {
    background-color: rgba(255,255,255,0.85);
    padding-left: 25px;
    padding-right: 25px;
    margin-left: auto;
    margin-right: auto;
    font-size: 14px;
    color: black;
    border-radius: 10px;
    text-align: center;
  }
</style>

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
