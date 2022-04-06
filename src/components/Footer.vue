//HTML
<template>
    <footer class="d-flex">
        <div class="container70">
            <div></div>
            <div class="image">
            </div>
        </div>
    </footer>
</template>

//JS
<script>
  export default {
      name: "ComponentFooter"
  }
</script>

//CSS
<style scoped>

  footer{
      background-image: url('../assets/img/footer-bg.jpg');
      background-repeat: no-repeat;
      background-size: cover;
      height: 300px;
  }

  .d-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
/* '../assets/img/dc-logo-bg.png' */
 
 .image {
   width: 80%;
   height: 600px;
   background-image: url('../assets/img/dc-logo-bg.png');
   background-repeat: no-repeat;
 }

</style>