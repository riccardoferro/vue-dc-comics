// HTML
<template>
    <header>
        <div class="container70 d-flex">
            <!-- //logo -->
            <img src="../assets/img/dc-logo.png" alt="logo_dc_comics">

            <!-- navbar -->
            <div>
                <ul class="d-flex">
                  <li>CHARACTERS</li>
                  <li>COMICS</li>
                  <li>MOVIES</li>
                  <li>TV</li>
                  <li>GAMES</li>
                  <li>COLLECTIBLES</li>
                  <li>VIDEOS</li>
                  <li>FANS</li>
                  <li>NEWS</li>
                  <li>SHOP</li>
                </ul>
            </div>
        </div>
    </header>
</template>

//JS
<script>
  export default {
      name: "ComponentHeader",
  }
</script>

// CSS
<style scoped>

/* Header custom */
header {
  min-height: 80px;
  border-top: 25px solid black;
  padding: 15px 0;
}

/* Header custom logo*/
header img {
  max-width: 65px;
}

/* Display flex  */
.d-flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* Custom unordered list */
ul {
  list-style-type: none;
}

ul li {
  margin: 0 10px;
  font-size: 10px;
  height: 65px;
  line-height: 65px;
  vertical-align: center;
}

ul li:hover {
  color: blue;
  border-bottom: 5px solid blue;
}

</style>