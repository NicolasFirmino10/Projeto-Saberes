<template>
  <div class="home">
      <div class="home-logo">
          <img class="imagem-logo" src="/img/Festa Logo.png" alt="">
      </div>
      <div class="text">  
          <div class="text-1">
               <p>Para falar da festa da colheita, é essencial fornecer uma visão geral de seu contexto histórico e cultural. Então aqui vai um resumo sobre a Festa da Colheita:
               </p>
               <img class="imagem-1" src="/img/festa 1.jpg" alt="">
              </div>
          <div class="text-2">     
              <p>A festa originou-se no pretexto de comemorar a colheita, apesar de não ter sido das melhores, nesse ano 2023. Além disso, constituiu uma oportunidade ideal para promover e divulgar os conceitos trabalhados ao longo do projeto, o Locavorismo e o Turismo rural de base comunitária. O evento serviu de incentivo e atração para a prática do TRBC (que ocorreu de 1º a 2 de julho), incentivando os turistas a se hospedarem nas casas da comunidade. Além disso, forneceu uma feirinha para os produtores locais entrevistados mostrarem e venderem seus produtos. 
              </p>
              <img class="imagem-2" src="/img/festa 2.jpg" alt="">
          </div>
          <div class="text-3">
              <p>O evento contou com uma programação para lá de boa! Incluiu uma variedade de destaques culturais e expressões de gratidão, começando no primeiro dia. Entre os destaques, uma apresentação cativante do Reisado Boi Surubim, uma farinhada de beiju, uma encantadora exibição de forró pé de serra e a Feirinha do Saberes e Sabores. No segundo dia, os participantes assistiram uma demonstração passo a passo do processo de fabricação da Cajuína São João, e viveram experiências tipicamente interioranas, como banho de açude e passeio de pau de arara. Para completar, um delicioso almoço, preparado com muito carinho para os visitantes.
              </p>
              <img class="imagem-3" src="/img/festa 3.jpg" alt="">
          </div>
          <div class="text-4">
          <p>
            Durante a programação, teve a participação de pessoas de diversos seguimentos, que vieram aproveitar a festa, mas também para reafirmar seu apoio e sua pareceria. Participaram diversas instituições como, como IFCE, IDF, Coopamab, INSS, Unilab, sindicatos, associações, CearáPrev, Agência de Turismo Comtú, Escola de Gastronomia Social Ivens Dias Branco, Conexão Maciço, Escola Grão de Mostarda, Fundação Fé e Alegria, Obra Kolping, Ematerce e Prefeitura de Redenção.
          </p>
          <img class="imagem-4" src="/img/festa 4.jpg" alt="">
          
          </div>
          <img class="imagem-5" src="/img/festa 5.jpg" alt="">
          <img class="imagem-6" src="/img/festa 6.jpg" alt="">
      </div>
  </div>
</template>

<script>

export default{
  name: 'Festa',
  methods: {
scrollToTop() {
  this.$router.push('/Festa');
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
overflow-x: hidden;
margin-top: 70px;
background-color: #99411B;
height: 650vh;
background-repeat: no-repeat;
background-size: cover;
display: block;
align-items: center;
justify-content: center;
overflow-y: hidden;
z-index: 0;
position: relative;
}

.imagem-logo{
width: 500px;
height: auto;
padding: 2px 5px;
}
.text{
color: #fff;
}
.text-1 {
width: 700px;
margin-left: 50px ;
margin-top: 100px;
font-size: 32px;
}
.imagem-1 {
  width: 500px;
  margin-top: -300px;
  margin-left: 800px;
}
.text-2 {
width: 700px;
margin-left: 750px;
margin-top: 150px;
font-size: 32px;
}

.imagem-2 {
  width: 500px;
  margin-top: -600px;
  margin-left: -1500px;
}

.text-3 {
width: 650px;
margin-left: 100px;
margin-top: 200px;
font-size: 33px;
}

.imagem-3 {
  width: 500px;
  margin-top: -600px;
  margin-left: 800px;
}
.text-4 {
font-size: 32px;
width: 700px;
margin-top: 150px ;
margin-left: 200px;
display: flex;
text-align: unset;
}
.imagem-4 {
  width: 800px;
  margin-top: 100px;
  margin-left: 100px;
}
.imagem-5 {
  width: 700px;
  margin-top: 100px;
  margin-left: -300px;
}
.imagem-6 {
  width: 700px;
  margin-top: 100px;
  margin-left: 500px;
}

@media (max-width: 768px) {
.text-1,
.text-2,
.text-3,
.text-4 {
  width: 80%;
  margin-left: 20px;
  font-size: 20px;
}
.home-logo {
  width: 100%;
  text-align: center;
}

.imagem-logo {
  width: 80%;
  height: auto;
  padding: 2px 5px;
}

.home {
  margin-top: 50px;
  height: auto;
  min-height: 100vh;
}


.imagem-1,
.imagem-2,
.imagem-3,
.imagem-5,
.imagem-6 {
  width: 100%;
  margin-left: 0;
  margin-top: 20px;
}
.imagem-4{
  width: 100%;
  margin-left: -200px;
  margin-top: 600px;
}
}


</style>