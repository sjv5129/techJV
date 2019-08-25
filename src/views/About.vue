<template>
<div>
<navbar/>
<div class="container">
  <div class="row">
    
    <div class="col"><img class="sami" src="../img/sami.jpg"/></div>
    <div class="col"><img class="steve" src="../img/steve.jpg"/></div>
    
    <div class="w-100"></div>
    
    <div class="col"><h2>Samantha Voelker</h2></div>
    <div class="col"><h2>Steven Voelker</h2></div>
    
    <div class="w-100"></div>
    
    <div class="col"><h5>Electrical Engineer</h5></div>
    <div class="col"><h5>Software Developer</h5></div>

    <div class="w-100"></div>
    
    <div class="col"> </div>
    <div class="col"> </div>

    <div class="w-100"></div>
    
    <div class="col"><p>After a 10+ year sales career it was time for a change.</p></div>
    <div class="col"><p>After a 10+ year sales career it was time for a change.</p></div>
    
  </div>
</div>
</div>   
</template>

<script>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
export default {
    name: 'about',
    components: {
        Navbar,
        Footer
    }
}
</script>

<style scoped>
.sami{
    width: 200px;
    height: auto;
    border-radius: 10px;
}
.steve{
    width: 200px;
    height: auto;
    border-radius: 10px;
}
.col{
    display: flex;
    background: rgba(0, 0, 0, .1);
   
}
.background1{
    width: auto;
    height: auto;
   
}
</style>