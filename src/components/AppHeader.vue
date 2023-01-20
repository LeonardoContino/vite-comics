<script>
export default {
    name: 'AppHeader',
    data() {
        return{
            ListNav: [
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  }
]}
}};
</script>

<template>
<header>
    <figure>
        <img src="../assets/img/dc-logo.png" alt="">
    </figure>

</header>

</template>

<style scoped>
header{
    height: 100px;
}
img{
    width: 80px;
}
</style>