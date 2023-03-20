<script setup>

</script>

<template>
    <div class="row">
      <div class="col-6">
        <div class="d_img_perfil">
          <img src="../../src/assets/joey.png" class="img_perfil">
        </div>
      </div>
      <div class="col-6 d_perfil">
        <p>FullStack Developer</p>
        <h2>Migue Ángel Domínguez</h2>
        <p class="p_des">
          I studied a degree in computer science, I have my degree, I have 7 years of experience in web development participating in various projects and in different business rules, I like to continue learning
          <br>
          I adapt to new challenges and ways of working
        </p>
        <div class="row mb-4">
          <div class="col-6">
            <a class="btnDownload" target="_blank" download="../assets/CV2023.pdf" href="../assets/CV2023.pdf">Download CV</a>
          </div>
          <div class="col-6">
            <RouterLink to="/contact" class="btnContact">Contacto</RouterLink>
          </div>
        </div>
      </div>
    </div>
</template>
<style>
  .d_img_perfil{
    display: block;
    position:relative;
    width: 50%;
    padding-bottom: calc(100% - 550px);
    border-radius: 1000px;
    overflow: hidden;
    background-color: #444;
    box-shadow:0 0 25px 0 rgba(0,0,0,.8);
    border:18px solid #444;
    margin-left: 25%;
  }
  .img_perfil{
    width: 150px;
    height: 180px;
    margin-left: 20%;
  }
  .d_perfil{
    color:white;
  }
   .btnDownload, .btnContact{
    background: transparent;
    color:white;
    font-weight: bold;
    border: 1px solid white;
    border-radius: 20px;
    width: 60%;
    margin-bottom: 10%;
    text-decoration: none;
    display: block;
    text-align: center;
  }
  .btnDownload:hover{
    background: #007ced;
    border-color: #007ced;
    color:white;
    text-decoration: none;
  }
  .btnContact:hover{
    background: white;
    border-color: white;
    color:black;
  }
  .p_des{
    color: white;
    font-weight: 100;
    font-size: 20px;
    padding-right: 20px;
  }
</style>