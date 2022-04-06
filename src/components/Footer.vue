//HTML
<template>
    <footer>
        <div class="container70 d-flex">
            <div>

            </div>
            <div class="image">
            </div>
            <!-- <img src="../assets/img/dc-logo-bg.png" alt=""> -->
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
  width:400px;
  height:300px;
  background-image: url('../assets/img/dc-logo-bg.png');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
 }

  /* img {
    height: 400px;
  } */
</style>