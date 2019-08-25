<template>
<div>
    <navbar/>
    <div class="lego">
    <div class="home-header"><h2>TechJV.net</h2></div>
    <div class="home-subheader"><h5>The Digital Portfolio of Sami and Steven Voelker</h5></div>
    <img src="../img/legoBG.jpg"/>
    <div class="people-header">
        <h3>Who are you here to see?</h3>
        <a href=""><button type="button" class="btn btn-outline-secondary">Steven</button></a>
        <a href=""><button type="button" class="btn btn-outline-secondary">Sami</button></a>
    </div>
    
    </div>
</div>
    
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    name: 'home',
    components: {
    Navbar
    }
}
</script>
<style scoped>
.lego{
    position: relative;
    text-align: center;
    color: white;
   
}
.people-header{
  position: absolute;
  bottom: 120px;
  left: 116px;
  color: white;
 
  
}
.btn-outline-secondary{
    color: white;
    margin: 10px;
}
.home-header{
    position: absolute;
    top: 20px;
    right: 5%;
}
.home-subheader{
    position: absolute;
    top: 60px;
    right: 5%;
    
}

</style>