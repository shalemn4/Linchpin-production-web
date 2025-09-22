<template>
  <Navbar />
<div class="m-4 pt-5 pb-5 bg rounded-4 bga ">
  <div class="container pt-5 mt-5 fs-1 pb-5">
    <div class="row">
      <div class="col">
        <p class="quote">A Hub of Ideas! <br/> A Society of Minds!</p>
        <p class="fs-5 quote">An independent student society empowering innovation</p>
        <button class="btn btn-dark btn-lg quote" @click="formlink">Become a member !</button>
       </div>
       <div class="col-2 d-flex">

      </div>

       </div>
  </div>
</div>
  <Events/>
  <Cards/>
  <About/>
  <Socials />
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
import Socials from './components/Socials.vue';
import Cards from './components/Cards.vue';
import Events from './components/Events.vue';
import About from './components/About.vue';

function formlink():void{
window.open("https://forms.gle/FASaR5xknVzW9s5n9", "_blank");
}
</script>

<style scoped>
.linchpinlogo
{
  width: 100px;
  height: 100px;
}
.bg
{
  background-color: rgb(243, 191, 94);
}
/* .bga
{
  background-image: url("./assets/linchpin.jpeg");
  
} */
.quote
{
  letter-spacing: 2px;
}
</style>
