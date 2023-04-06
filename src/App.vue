<script setup>
//import { RouterLink, RouterView } from 'vue-router'
//import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="my-0 py-0">
    <v-row class="my-0 py-0 pl-3" id="headerr">
      <v-col class="my-0 py-0" style="line-height: 0"
        ><img alt="Vue logo" src="@/assets/logo.png" width="65" height="65"
      /></v-col>
      <v-col class="my-0 py-0 text-button"
        ><v-container class="text-right"
          >MENU<v-icon class="px-4" size="x-small" icon="mdi-menu" /></v-container
      ></v-col>
    </v-row>
    <v-row style="height: 90vh" class="my-0 py-0">
      <v-img
        cover
        alt="Vue logo"
        src="https://www.odetterestaurant.com/wp-content/uploads/2017/03/odette-home-desktop-bg-1.jpg"
      />
    </v-row>
  </div>
</template>

<style scoped>
#headerr {
  background-color: #dec7b6;
  color: #ffffff;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

/*
nav {
  width: 100%;
  font-size: 12px;
  text-align: center;

}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}


@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
*/
</style>
