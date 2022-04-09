<template>
  <div id="app">
		<Header></Header>
    <Todolist></Todolist>
		<Footer></Footer>
  </div>
</template>

<script>
import Todolist from './components/Todolist.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Todolist,
		Header,
		Footer,
  },
}
</script>

<style>
</style>
