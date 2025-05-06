<script setup>


</script>


<template>
    <div class="main">
    <div class="grid">
<div class="left">
    <h4>clickfunnels</h4>
    <p class="tm">Increased stick rate by 3% with end to end design, from problem to high fidelity solution using proven design thinking methodologies.</p>
</div>
<div class="right"></div>
    </div>
</div>
</template>



<style>

.main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto;
    width: 100vw;
}
.grid {
  display: grid;
  grid-template-columns: repeat(16, 1fr);
  column-gap: 32px;
  width: 1280px;
}


.left {
  display: flex;
  flex-direction: column;
  grid-column: span 6;
  border: solid 1px black;
  background-color: #21242D;
  color: white!important;
  padding: 24px;
  gap: 12px;
  border-radius: 24px;
}
.right {
  grid-column: span 10;
  border: solid 1px black;
  border-radius: 24px;
}
</style>