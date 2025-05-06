<script setup>


</script>


<template>
   
    <div class="main">
        <div class="header"><h2>Portfolio</h2></div>
    <div class="grid">
<div class="left">
    <div class="leftContainer">
        <img src="public/images/ClickFunnels-Logo (1) 1.png"  width="160px" class="image">
    <h3 class="white">Data Import Feature For a Martech SaaS Application</h3>
    <p class="tl">Increased stick rate by 3% with end to end design, from problem to high fidelity solution using proven design thinking methodologies.</p>
    <div class="progress"></div>
</div>
</div>
<div class="right">

</div>
    </div>
</div>
</template>



<style>

.main {
  display: flex;
  justify-content: center; /* center .grid horizontally */
  width: 100vw;
  flex-direction: column;
  align-items: center;
  gap: 32px;
  padding-top: 48px;


}

.image{
    padding-bottom: 16px;
}

.leftContainer{
    width: 360px;
    display: flex;
    flex-direction: column;
    gap: 24px;
    max-height: auto;
}

.header{
    width: 1280px;
    height: 36px;


}
.grid {
  display: grid;
  grid-template-columns: repeat(16, 1fr);
  column-gap: 32px;
  width: 1280px;
}

.white{
    color: white;
}


.left {
  display: flex;
  flex-direction: column;
  grid-column: span 6;
  border: solid 1px black;
  background-color: #21242D;
  color: rgba(255, 255, 255, 0.72)!important;
  padding: 40px 32px;
  gap: 24px;
  border-radius: 24px;

}
.right {
  grid-column: span 10;
  border: solid 1px black;
  border-radius: 24px;
  background-color: var(--bg-strong);
}

.progress{
    height: 10px;
    border-radius: 500px;
    background-color: var(--text-light);
    margin-top: 12px;
    width: 100%;
}
</style>