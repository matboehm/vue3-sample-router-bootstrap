<template>
 <SimpleNav/>
  <!-- route outlet -->
  <!-- component matched by the route will render here -->
  <div class="container">
      <div class="vertical-center">
        <div>
          <router-view></router-view>
        </div>
      </div>
    </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import SimpleNav from './components/SimpleNav.vue'

export default {
  name: 'App',
  components: {
    SimpleNav,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
