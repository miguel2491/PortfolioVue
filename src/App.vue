<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
      <nav>
        <div class="row">
          <div class="r_perfil">
            <div class="circle-1">
              MADS
            </div>
            <div class="r_name">
              <RouterLink to="/"><b>Miguel Ángel</b> Domínguez</RouterLink>
            </div>
          </div>
          <div class="r_opciones">
            
            <RouterLink to="/resumen">Resume</RouterLink>
            <RouterLink to="/portfolio">Portfolio</RouterLink>
            <RouterLink to="/contact">Contact</RouterLink>
          </div>
        </div>
      </nav>

  <RouterView />
</template>

<style scoped>
  .r_perfil, .r_opciones{
    width: 50%;
  }
  .circle-1{
    position: absolute;
    width: 90px;
    height: 80px;
    background: #007bff;
    border-radius: 50%;
    color:white;
    font-weight: bold;
    text-align: center;
    font-size: 26px;
    padding: 20px 25px 5px 5px;
    margin: 3% 2% 0% 3%;
  }
  .r_name{
    margin: 13% 15% 5% 28%;
  }
  .r_name a {
    color: white;
    text-decoration: none;
    font-size: 24px;
  }
  .r_opciones{
    margin-top: 6%;
  }
  .r_opciones a{
    color:white;
    text-decoration: none;
    font-size: 22px;
    margin:3%;
  }
  .r_opciones a:hover{
    background: white;
    color:black;
    text-shadow: #e2e;
    border-radius: 20px;
    width: 100%;
    box-shadow: 0px 15px 20px rgba(46, 229, 157, 0.4);
  }
</style>
