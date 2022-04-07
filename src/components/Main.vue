//HTML
<template>
    <main>
        <div class="container70">
            <!-- we gonna create a single comic for each element in the data dc-comics -->
            <SingleComic v-for="(comic,index) in comics" :key="'comic'+index"/>
            
        </div>
    </main>
</template>

//JS
<script>

//here we import a single comic with his info
import SingleComic from '@/components/subcomponents/SingleComic.vue'

  export default {
      name: "ComponentMain",
      props: {
          comics: Array
      },
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