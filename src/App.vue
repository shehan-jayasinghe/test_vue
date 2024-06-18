<script >
   export default {
     name:"App",
     data(){
       return{
         name:"shehan",
         vText:"v-text",
         vHtml:"<h1><b>Hello World</b></h1>"
       }
     }
   }
</script>

<template>
  <div class="pinkBG">Hell {{name}}</div>
  <div v-text="vText"></div>
  <div v-html="vHtml"></div>
</template>

<style scoped>
.pinkBG {
  background-color: lightpink;
}
</style>
