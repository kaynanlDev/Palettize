<script setup></script>
<template>
  <div class="cards">
    <div class="card">
      <div class="card-color"></div>
      <p>#000</p>
    </div>
    <div class="card">
      <div class="card-color"></div>
      <p>#000</p>
    </div>
    <div class="card">
      <div class="card-color"></div>
      <p>#000</p>
    </div>
    <div class="card">
      <div class="card-color"></div>
      <p>#000</p>
    </div>
  </div>
</template>
<style scoped lang="scss">
.cards {
  max-width: 70%;
  margin: 24px auto;
  display: flex;
  justify-content: center;
  gap: 16px;

  .card-color {
    width: 100%;
    height: 100%;
    background-color: #d9d9d9;
  }
  P {
    color: #69247c;
    font-weight: 700;
  }
}
</style>
