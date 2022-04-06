<template>
  <section>
    <div class="container70 d-flex">
      <div id="icon">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="img digital comics"> 
          <span>DIGITAL COMICS</span>
      </div>
      <div id="icon">
          <img src="../assets/img/buy-comics-merchandise.png" alt="img merchandise">
          <span>DC MERCHANDISE</span>
      </div>
      
      <div id="icon">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
          <span>SUBSCRIPTION</span>
      </div>

      <div id="icon">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator">
          <span>COMIC SHOP LOCATOR</span>
      </div>

      <div id="icon">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="dc power visa">
          <span>DC POWER VISA</span>

      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: "componentSectionIcons"
}
</script>

<style scoped>

section {
  padding: 43px 0;
  background-color: hsl(209deg 98% 49%);
  
}

.d-flex {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

img {
  width: 35px;
}

#icon {
  display: flex;
  align-items: center;
  color: white;
  font-size: 10px;
}

#icon img {
  margin-right: 10px;
}

</style>