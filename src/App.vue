<template>
  <div>
    <span>Selecione o exercício:</span>
    <select name="Selecione o Exercício" @change="onChangeSelect($event)">
      <option value="0">Exercício Tabela</option>
      <option value="1">Exercício 01</option>
      <option value="2">Exercício 02</option>
      <option value="3">Exercício 03</option>
      <option value="4">Exercício 04</option>
    </select>
  </div>

  <div class="exercise-container">
    <div :class="{ active: this.exercise == 0 }">
      <ProductTable />
    </div>
    <div :class="{ active: this.exercise == 1 }">
      <Exercise01 />
    </div>

    <div :class="{ active: this.exercise == 2 }">
      <Exercise02 />
    </div>

    <div :class="{ active: this.exercise == 3 }">
      <Exercise03 />
    </div>

    <div :class="{ active: this.exercise == 4 }">
      <Exercise04 />
    </div>
  </div>

  <div class="github-repo">
    <a href="https://github.com/lucaszambam/web-dev-unidavi" target="_blank">
      <img src="./assets/svg/github-mark.svg" alt="GitHub Repository" />
    </a>
  </div>
</template>

<script>
import ProductTable from './components/ProductTable.vue'
import Exercise01 from './components/Exercise01.vue'
import Exercise02 from './components/Exercise02.vue'
import Exercise03 from './components/Exercise03.vue'
import Exercise04 from './components/Exercise04.vue'

export default {
  name: 'App',
  components: {
    ProductTable,
    Exercise01,
    Exercise02,
    Exercise03,
    Exercise04
  },
  data() {
    return {
      exercise: 0,
    }
  },
  methods: {
    onChangeSelect(event) {
      this.exercise = event.target.value;
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

.exercise-container > div:not(.active) {
  display: none;
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
