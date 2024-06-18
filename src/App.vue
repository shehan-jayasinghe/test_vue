<script >
   export default {
     name:"App",
     data(){
       return{
         name:"shehan",
         vText:"v-text"
       }
     }
   }
</script>

<template>
  <div class="pinkBG">Hell {{name}}</div>
  <div v-text="vText"></div>
</template>

<style scoped>
.pinkBG {
  background-color: lightpink;
}
</style>
