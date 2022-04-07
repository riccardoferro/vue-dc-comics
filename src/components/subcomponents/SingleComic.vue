<template>
  <div class="card">
      <img :src="fumetto.thumb" alt="img of the comic book">
      <div>{{fumetto.series}}</div>
  </div>
</template>

<script>
export default {
    name: "Single_Comic",


    /*This is the single comic
       {
            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
            "price": "$19.99",
            "series": "Action Comics",
            "type": "comic book"
       },
    */

    props: {
         //here we receive the single comic that have type object
        fumetto: Object
    }
}
</script>

<style lang="scss" scoped>

  .card {
    width: calc(100% / 6);
    color: white;
    font-weight: normal;
    font-size: smaller;
    text-transform: uppercase;
    padding-bottom: 50px;

    img {
      width: 75%;
    }
}

</style>