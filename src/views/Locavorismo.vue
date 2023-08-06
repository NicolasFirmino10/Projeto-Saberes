<template>
    <div class="home">
      <div class="home-logo">
        <img class="imagem-logo" src="/img/locavorismo.png" alt="">
      </div>
      <img class="imagem-local" src="/img/local.png" alt="">
      <div class="text">  
            <div class="text-1">
                 <p>Comprar e utilizar mercadorias de fontes locais ou estabelecimentos menores tornou-se uma prática conhecida como locavorismo. As cidades do interior abrigam as conhecidas "bodegas" que atendem a essa tendência. A palavra "locavorismo" é derivado de "local" e "-voro", uma palavra latina que significa "comer", ou seja, é o consumo mais sustentável de uma região. 
                 </p>
                </div>
                <img class="imagem-caju" src="/img/caju.png" alt="">
                <img class="imagem-banana" src="/img/banana.png" alt="">
            <div class="text-2">
                
                <p>A preferência por esse tipo de uso está relacionada à praticidade e facilidade de disponibilidade dos produtos alimentícios e à busca de uma relação equilibrada com o meio ambiente. O locavorismo também busca evitar a perda de nutrientes, o frescor e o impacto ambiental que o alimento tem ao percorrer uma longa jornada até chegar ao mercado de massa.
                </p>
            </div>
            <img class="imagem-cafe" src="/img/cafe.png" alt="">
            <div class="text-3">
                <p>O termo, em seu sentido literal, refere apenas ao consumo de produtos do ramo alimentícios. Mas nós enquanto locávoros abrangemos o termo para o consumo de um território em suas mais diversas formas.
                </p>
            </div>
            <img class="imagem-carta" src="/img/carta.png" alt="">
            <div class="text-4">
            <p>
                O projeto Saberes e Sabores visa analisar e promover o Locavorismo de forma holística. Incentivando não somente o consumo de alimentos produzidos próximo aos consumidores, mas também a cultura, o turismo, a arte, a economia e a história da região.
            </p>
            </div>
        </div>
        <div class="text-button">
            <p>Agora, conheça um pouco dos nossos produtores!</p>
        </div>
        <div class="home-button">
            <router-link to="/Produtores"><button @click="scrollToTop()" class="button">Clicando aqui!</button></router-link>
        </div>
    </div>
</template>

<script>

export default{
    name: 'Locavorismo',
    methods: {
  scrollToTop() {
    this.$router.push('/Locavorismo');
    window.scrollTo({
        top: 0,
        behavior: "smooth",
      });
    }
  }
}

</script>

<style scoped>
.home {
background-color: #EF8535;
height: 360vh;
}

.imagem-logo {
width: 500px;
margin-top: 100px;
}

.imagem-cafe {
position: absolute;
width: 350px;
margin-left: 300px;
margin-top: 100px;
}

.imagem-local {
position: absolute;
width: 200px;
margin-left: -700px;
}

.imagem-caju {
position: absolute;
margin-left: -500px;
width: 250px;
margin-top: 100px;
}

.imagem-banana {
position: absolute;
width: 250px;
margin-top: 150px;
margin-left: -700px;
}

.imagem-carta {
position: absolute;
width: 300px;
margin-top: 150px;
margin-left: 300px;
}

.text-1 {
width: 700px;
margin-left: 260px ;
margin-top: 100px;
font-size: 32px;
}

.text-2 {
width: 700px;
margin-left: 750px;
margin-top: 100px;
font-size: 32px;
}

.text-3 {
width: 650px;
margin-left: 100px;
margin-top: 200px;
font-size: 33px;
}

.text-4 {
font-size: 32px;
width: 700px;
margin-top: 150px ;
margin-left: 350px;
display: flex;
text-align: unset;
}

.text-button p {
width: 600px;
height: auto;
display: flex;
font-size: 38px;
margin-left: 450px;
margin-top: 200px;
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

@media only screen and (max-width: 768px) {
.home {
height: auto;
}

.imagem-logo {
width: 300px;
margin-top: 50px;
}

.imagem-cafe {
position: relative;
width: 300px;
margin-left:10px;
margin-top: -80px;
}

.imagem-local {
position: relative;
width: 90px;
margin-top: -50px;
margin-bottom: -85px;
margin-left: -295px;
}

.imagem-caju {
position: relative;
width: 150px;
margin-left: 10px;
margin-top: -200px;
}

.imagem-banana {
  position: relative;
width: 150px;
margin-top: 10px;
margin-left: -300px;
}

.imagem-carta {
position: relative;
width: 300px;
margin-top: 10px;
margin-left: -10px;
}

.text-1 {
width: 90%;
margin: 50px auto;
font-size: 24px;
text-align: center;
font-family: 'Century Gothic';
}

.text-2 {
width: 90%;
margin: 50px auto;
font-size: 24px;
text-align: center;
font-family: 'Century Gothic';
}
.text-3 { 
   width:320px;
  position: relative;
  font-size: 23px;
  display: flex; 
   margin: 15px;
  justify-content: space-between;
  text-align: justify;
  font-family: 'Century Gothic';
}
.text-4 {
    position: relative;
  font-size: 23px;
  width:350px;
  margin: 15px;
  margin-top: 100px ;
  display: flex;
  text-align:justify;
  font-family: 'Century Gothic';
}
  .text-button p{
    width: 350px;
    position: relative;
  height: auto;
  display: flex;
  font-size: 38px;
  margin-left: 10px;
  margin-top: 100px;
  font-family: 'Century Gothic';
}

  .button{
  background-color: transparent;
  border: 2px solid #000;
  color: #000;
  cursor: pointer;
  padding: 10px 20px;
  width: 300px;
  margin-bottom: 100px;
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

