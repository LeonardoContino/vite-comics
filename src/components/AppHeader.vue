<script>
export default {
    name: 'AppHeader',
    data() {
        return{
            lists: [
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

    <nav>
        <ul class="d-flex">
            <li v-for="list in lists"  :key="list.text" >
                <a :href="list.url" v-text="list.text" :class="{'active' : list.current}"></a>
            </li>
        </ul>
    </nav>

</header>

</template>

<style scoped>
header{
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;

}

img{
    width: 80px;
}
.d-flex{
    display: flex;
    justify-content: center;
    
}
.active{
    color: blue;
}
ul li {
    list-style: none;
    padding: 5px;
    font-size: 15px;
    text-transform: uppercase;
}
a {
        text-decoration: none;
    }
</style>