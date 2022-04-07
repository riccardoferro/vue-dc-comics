//HTML
<template>
    <main>
        <div class="container70">
            <!-- we gonna create a single comic for each element in the data dc-comics
                so we gonna create an other sub-component and send him the single comic (object)
             -->
            <!-- with the prop "fumetto" we send the single comic to the sub component SingleComic -->
            <!-- we need the key to identify uniquely the the single comic book -->
            <SingleComic v-for="(comic,index) in comics" :key="'comic'+index" :fumetto="comic"/>
            
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
<style scoped>


    main {
        min-height: 80px;
        font-weight: 1000;
        color: white;
        background-color: hsl(0deg 0% 11%);
    }

</style>