<template>
  <div class="container">
    <header>
      <h1>Quizee</h1>
      <input type="text" placeholder="Search...">
    </header>

    <div class="options__container">
      <div class="options__card">
        <img src="../src/assets/Math.jpg" alt="" class="options__img">
        <div class="options__desc">
          <h2 class="options__header">Math</h2>
          <p class="options__prompt">15 questions</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
  .container{
    max-width: 1000px;
    margin: 0 auto;

  }

  header{
    margin-bottom: 10px;
    margin-top: 30px;
    display: flex;
    align-items: center;
    gap: 15px;
  }
  
  .header h1{
    /* font-weight: bold; */
    font-weight: 700;
    margin-right: 30px;
  }

  header input{
    border: none;
    background-color: rgb(128, 128, 128, 0.1);
    padding: 10px;
    border-radius: 5px;
  }

  .options__container{
    display: flex;
    flex-wrap: wrap;
    margin-top: 40px;
  }

  .options__card{
    width: 310px;
    overflow: hidden;
    border-radius: 2%;
    box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 35px;
    margin-right: 20px;
    cursor: pointer;
  }

  .options__img{
    width: 100%;
    height: 190px;
    margin: 0;
  }

  .options__desc{
    padding: 0 5px;
  }

  .options__header{
    font-weight: bold;
  }

</style>