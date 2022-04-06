//HTML
<template>
    <footer>
        <div class="container70 d-flex">
            <div class="left-side-footer d-flex wrap">
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

  .left-side-footer {
    padding-top: 30px;
    width: 40%;
  }

  .d-flex {
    display: flex;
    justify-content: space-between;
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

</style>