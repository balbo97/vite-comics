<script>

export default {
  name: 'AppHeader',
  data() {
    return {
      links: [
        {
          label: 'Charaters',
          url: '#',
          current: false
        },
        {
          label: 'Comics',
          url: '#',
          current: false
        },
        {
          label: 'Movies',
          url: '#',
          current: false
        },
        {
          label: 'Tv',
          url: '#',
          current: false
        },
        {
          label: 'Games',
          url: '#',
          current: false
        },
        {
          label: 'Collectibles',
          url: '#',
          current: false
        },
        {
          label: 'Videos',
          url: '#',
          current: false
        },
        {
          label: 'Fans',
          url: '#',
          current: false
        },
        {
          label: 'News',
          url: '#',
          current: false
        },
        {
          label: 'Shop',
          url: '#',
          current: false
        },

      ]
    }
  },

}
</script>

<template lang="">
  <header>
    <div class="container-sm">
      <div class="row">
        <div class="col">
          <div class="navbar">
            <a href="#" class="brand">
              <img src="../assets/img/favicon.ico" alt="dc">
            </a>
            
            <ul class="d-flex list-unstyled">
              <li v-for="(link, index) in links" :key="index">
                <a :class="link.current ? 'active': ''" :href="link.url" class="link-underline link-underline-opacity-0 text-black">
                  {{link.label}}
                </a>
              </li>
            </ul>
           
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  height: 75px;


  li {
    margin-left: 15px;
    text-transform: uppercase;
  }

}
</style>