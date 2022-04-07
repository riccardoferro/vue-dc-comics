//HTML
<template>
    <footer>
        <div class="container70 d-flex">
            <div class="left-side-top-footer d-flex wrap">
                <div>
                    <span>DC COMICS</span>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                </div>
                <div>
                    <span>DC COMICS</span>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li>News</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li>News</li>
                    </ul>
                </div>
                <div>
                    <span>DC COMICS</span>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                    </ul>
                </div>
                <div>
                    <span>DC COMICS</span>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                    </ul>
                </div>
            </div>
            <!-- logo footer -->
            <div class="image">
            </div>
        </div>
        <div class="middle-footer ">
            <div class="container70 d-flex-center">
                <button>
                  SIGN-UP NOW!
                </button>

                <div class=" icons-footer d-flex">
                  <span id="followus"> FOLLOW US</span>
                  <img src="../assets/img/footer-facebook.png" alt="img logo facebook">
                  <img src="../assets/img/footer-twitter.png" alt="img logo twitter">
                  <img src="../assets/img/footer-youtube.png" alt="img logo youtube">
                  <img src="../assets/img/footer-pinterest.png" alt="img logo pinterest">
                  <img src="../assets/img/footer-periscope.png" alt="img logo periscope">

                </div>
            </div>
        </div>
        <!-- <div class="bottom-footer d-flex">
        </div> -->
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
  }

  .left-side-top-footer {
    padding-top: 30px;
    width: 40%;
  }

  .d-flex {
    display: flex;
    justify-content: space-between;
  }
 
 .d-flex-center {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 80px;
  }

 .wrap {
   flex-wrap: wrap;
 }

 .image {
    width:400px;
    height:300px;
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
 }

div {
  color: white;
  font-weight: 700;
  font-size: 15px;
}

ul {
  list-style-type: none;
  padding: 10px 0;
}

li {
  color: grey;
  font-size: 10px;
  padding: 4px 0;
}

.middle-footer {
  background-color: hsl(0deg 0% 19%);
  border-bottom: 20px solid hsl(0deg 0% 5%);
}

button {
  background-color: hsl(0deg 0% 19%);
  color: white;
  padding: 10px;
  justify-self: center;
  border: 2px solid hsl(209deg 98% 49%);
  font-weight: 500;
}

#followus {
  color: hsl(209deg 98% 49%);
  font-weight: 700;
  align-self: center;
}

.icons-footer * {
  padding: 5px;
}

/* .bottom-footer {
  max-height: 159px;
  height: 159px;
  background-color: hsl(0deg 0% 5%);
} */

</style>