<template>
  <footer>
    <div>
          <div>
            <p>&copy; Saberes e Sabores 2023 </p>
            <br>
        <div class="link">
          <p><a href="https://instagram.com/saberessabores.interior" target="_blank" class="fab fa-instagram">Instagram</a></p>
        </div>
        </div>
      </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>

footer {
  padding: 20px 0;
  position: static;
width: 100%;
background-color: #f17d00;
text-align: center;
bottom: 0;
left: 0;
right: 0;

}

footer p {
  color: #ffffff;
  margin-top: 0px;
}
.link{
  position: relative;
  box-shadow: var(--box-shadow);
  padding:12px;
}

.link  a{
  width: 110px;
  font-size: 20px;
  color:#fff;
  text-decoration: none; 
  transition: all 0.2s ease-in-out;
}

.link .fa-instagram:hover{
  color: rgb(187, 45, 45);
}
</style>
