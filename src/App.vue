<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default{
    name: 'GeneralApp',
    components: {AppHeader, AppMain, AppFooter}
}


</script>

<template>
 <div class="container border">
    <AppHeader></AppHeader>
</div>
    <AppMain></AppMain>
    <AppFooter></AppFooter>
 
  
</template>

<style>
body {
  font-family: "Open Sans", sans-serif;
  
  
}
.container{
    width: 1200px;
    margin: auto;
    
}
.border{
    border: 2px dashed black;
}
</style>
