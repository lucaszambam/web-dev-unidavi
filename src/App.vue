<template>
  <ProductTable />
  <div class="github-repo">
    <a href="https://github.com/lucaszambam/web-dev-unidavi" target="_blank">
      <img src = "./assets/svg/github-mark.svg" alt="GitHub Repository"/>
    </a>
  </div>
</template>

<script>
import ProductTable from './components/ProductTable.vue'

export default {
  name: 'App',
  components: {
    ProductTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
.github-repo {
	position: fixed;
    bottom: 10px;
    right: 20px;
}
.github-repo a img {
	scale: 0.45;
    opacity: 0.5;
	transition: all .25s;
}
.github-repo a img:hover {
	opacity: 1;
	scale: 0.5;
}
</style>
