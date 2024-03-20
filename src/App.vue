

<!-- Javascript -->
<script>
export default {
  data(){
    return{
      title: 'Hello World',
      paragraph: 'questo è un paragrafo.'
    };
  }
};
</script>



<!-- HTML -->
<template>
  <div class="text">
    <h1>{{ title }}</h1>
    <p>{{ paragraph }}</p>
  </div>
</template>



<!-- CSS -->
<style>
  h1{
    color: rgb(197, 10, 10);
    font-size: 60px;
  }

  p{
    font-size: 30px;
    font-weight: 600;
  }
</style>
