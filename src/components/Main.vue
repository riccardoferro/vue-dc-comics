//HTML
<template>
    <main>
        <span class="title"> 
            CURRENT SERIES
        </span>
        <div class="container70 d-flex-cards">
            <!-- we gonna create a single comic for each element in the data dc-comics
                so we gonna create an other sub-component and send him the single comic (object)
             -->
            <!-- with the prop "fumetto" we send the single comic to the sub component SingleComic -->
            <!-- we need the key to identify uniquely the the single comic book -->
            <SingleComic v-for="(comic,index) in comics" :key="'comic'+index" :fumetto="comic"/>
            
        </div>
        <div class="container70 d-flex-center pb-30">
            <span class="text-box ">LOAD MORE</span>
        </div>
    </main>
</template>

//JS
<script>

//here we import a single comic with his info
import SingleComic from '@/components/subcomponents/SingleComic.vue'

  export default {
      name: "ComponentMain",

      //proposition
      props: {

          //here this variable take the datas of the comics books with his info
          comics: Array
      },

      //components
      components: {
          SingleComic,
      }
  }
</script>

//CSS
<style lang="scss" scoped>

main {
    min-height: 80px;
    font-weight: 1000;
    color: white;
    background-color: hsl(0deg 0% 11%);
    padding-top: 30px;
    position: relative;
}

.d-flex-cards {
    padding: 20px 0;
    display: flex;
    flex-wrap: wrap;
}

.d-flex-center {
    display: flex;
    align-items: center;
    justify-content: center;
}

.pb-30 {
    padding-bottom: 30px;
}

.text-box {
    background-color: hsl(209deg 98% 49%);
    padding: 10px 70px;
    font-size: 12px;
}

.title {
    background-color: hsl(209deg 98% 49%);
    position: absolute;
    top: 0;
    left: 225px;
    transform: translateY(-50%);
    padding: 10px 15px;
}

</style>