<template>
  <div class="home">
    
      <div class="home-logo">
        <img class="imagem-logo" src="/img/logo.png" alt="">
      </div>
      <div class="text">  
         <img class="imagem-texto" src="/img/quem somos.png" alt="">
       <div class="text-1">
        <p>O projeto denominado <strong> “Saberes e Sabores: Uma (re)visita ao interior” </strong> visa promover e explorar os conceitos de Locavorismo e Turismo Rural na nossa região, com foco principal no Maciço de Baturité. No entanto, pretendemos desenvolver métodos que possam ser efetivados em outras áreas, conforme o princípio da replicabilidade.
        </p>
        </div>
        <div class="text-2">
        <p>Nosso objetivo é promover o Locavorismo na região e aprofundar os laços sociais e culturais compartilhados entre produtores locais, consumidores e turistas. 
        </p>
        </div>
        <img class="imagem-icones" src="/img/Icones.png" alt="">
        <img class="imagem-boneco" src="/img/Boneco.png" alt=""> 
        <div class="text-3">
        <p>Nesse contexto, examinaremos de que forma se desenvolve a confiança, comunicação e cooperação nesta cadeia de produção, além de buscarmos disseminar estes saberes populares de uma forma educacional.
        </p>
        </div>
        <div class="text-4">
        <p>
          Deste modo, este estudo de caso se torna importante para verificar como o <strong> locavorismo </strong> busca explorar de forma sustentável os benefícios do turismo rural e dessa prática específica na economia local, bem como a renda que gera para os envolvidos no setor.
        </p>
        </div>
      </div>
        <div class="text-button">
          <p>Conheça o que é o Locavorismo!</p>
          
        </div>
        <div class="home-2-button">
          <router-link to="/Locavorismo"><button @click="scrollToTop()" class="button">Clicando aqui!</button></router-link>
        </div>
  </div>
  </template>
  
  <script>
  export default{
    name: 'HomeView',
    components:{
    },
      methods: {
    scrollToTop() {
      this.$router.push('/Locavorismo');
      window.scrollTo({
          top: 0,
          behavior: "smooth"
        });
      }
    } 
  }
  
  </script>
  
  <style scoped>
  
  
  /* Regras de estilo comuns a todas as telas */
  @media only screen and (min-width: 600px) {
    .home {
    overflow-x: hidden;
    margin-top: 70px;
    background-color: #ffa600;
    background-image: url('../../public/img/Desfocado.png');
    height: 360vh;
    background-repeat: no-repeat;
    background-size: cover;
    display: block;
    align-items: center;
    justify-content: center;
    overflow-y: hidden;
    z-index: 0;
    position: relative;
  }
  .home {
    background-image: url('../../public/img/Desfocado.png');
  }
  .home-logo {
    padding: 20px;
  }
  .imagem-logo{
    width: 500px;
    height: auto;
    padding: 2px 10px;
  }
   
    .imagem-texto {
      width: 400px;
    }
    .imagem-icones{
      position: absolute;
      margin-top: -550px;
      margin-left: 500px;
    }
    .text-1, .text-2 {
      width: 700px;
      
      margin: 90px 50px;
      font-size: 32px;
    }
    .text-3{
      width: 600px;
      margin-left: 800px;
      font-size: 32px;
    }
    .text-4{
    position: relative;
    font-size: 32px;
    width:700px;
    margin-top: 200px ;
    margin-left: 400px;
    display: flex;
    text-align:unset;  }
    .imagem-boneco {
      width: 500px;
      margin-top: -100px;
      margin-left: 300px;
    }
    .text-button p{
    width: 100%;
    height: auto;
    display: flex;
    font-size: 38px;
    margin-left: 450px;
    margin-top: 100px;
    margin-bottom: 60px;
    font-family: 'Century Gothic';
  }
    .button{
    background-color: transparent;
    border: 2px solid #000;
    color: #000;
    cursor: pointer;
    padding: 10px 20px;
    width: 300px;
    font-size: 18px;
    text-align: center;
    border-radius: 20px;
    transition: all 0.3s ease;
  }
  .button:hover{
    background-color: #ffffff;
    color: #6f5f17;
  }
  }
  
  /* Regras de estilo para telas menores que 600px */
  @media only screen and (max-width: 600px) {
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    width: 100%;
    z-index: 0;
    overflow-x: hidden;
  }
  .home {
    background-color: #ffa600;
    background-image: url('../../public/img/Desfocado.png');
    height: 450vh;
    background-repeat: no-repeat;
    background-size: cover;
    display: block;
    align-items: center;
    justify-content: center;
    overflow-y: hidden;
    z-index: 0;
    position: relative;
  }
  .home {
    background-image: url('../../public/img/Desfocado.png');
  }
  .home-logo {
    padding: 20px;
  }
  .imagem-texto {
      width: 350px;
    }
  .imagem-logo{
    width: 400px;
    margin-left: -30px;
    height: auto;
    padding: 2px 10px;
  }
  .imagem-icones{
      position: relative;
      margin-top: 100px;
      margin-left: -20px;
    }
  .imagem-boneco{
    width: 350px;
    margin-top: 50px;
  }
  .text {
    font-size: 50px;
    font-family: 'Century Gothic';
  }
  .text-1 {
    width:365px;
    position: relative;
    font-size: 23px;
    display: flex;
    text-align: left;
    margin-top: 80px;
    margin-left: 15px;
  }
  .text-2 {
    width:350px;
    position: relative;
    font-size: 23px;
    display: flex;
    margin-top: 80px;
    margin-left: 15px;
    justify-content: space-between;
    text-align: justify;
  }
  .text-3 { 
     width:350px;
    position: relative;
    font-size: 23px;
    display: flex; 
     margin: 15px;
    justify-content: space-between;
    text-align: justify;
  }
  .text-4 {
    position: relative;
    font-size: 23px;
    width:350px;
    margin: 15px;
    margin-top: 100px ;
    display: flex;
    text-align:justify;
  }
    .text-button p{
    width: 100%;
    height: auto;
    display: flex;
    font-size: 38px;
    margin-top: 100px;
    margin-bottom: 20px;
    font-family: 'Century Gothic';
  }
    .text-button p {
      font-size: 30px;
      font-family: 'Century Gothic';
    }
    .button{
    background-color: transparent;
    border: 2px solid #000;
    color: #000;
    cursor: pointer;
    padding: 10px 20px;
    width: 300px;
    font-size: 18px;
    text-align: center;
    border-radius: 20px;
    transition: all 0.3s ease;
  }
  .button:hover{
    background-color: #ffffff;
    color: #6f5f17;
  }
  }
  </style>
  