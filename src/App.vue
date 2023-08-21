<template>
  <div>
    <span>Selecione o exercício:</span>
    <select name="Selecione o Exercício" @change="onChangeSelect($event)">
      <option v-for="index in this.numberOfComponents" :value="index - 1">Exercício 0{{ index - 1 }}</option>
    </select>
  </div>

  <div class="exercise-container">
    <div v-for="index in this.numberOfComponents" :class="{ active: this.exercise == index - 1 }">
      <component :is="'Exercise0' + (index - 1) "></component>
    </div>
    
  </div>

  <div class="github-repo">
    <a href="https://github.com/lucaszambam/web-dev-unidavi" target="_blank">
      <img src="./assets/svg/github-mark.svg" alt="GitHub Repository" />
    </a>
  </div>
</template>

<script>
import Exercise00 from './components/Exercise00.vue'
import Exercise01 from './components/Exercise01.vue'
import Exercise02 from './components/Exercise02.vue'
import Exercise03 from './components/Exercise03.vue'
import Exercise04 from './components/Exercise04.vue'
import Exercise05 from './components/Exercise05.vue'
import Exercise06 from './components/Exercise06.vue'
import Exercise07 from './components/Exercise07.vue'

export default {
  name: 'App',
  components: {
    Exercise00,
    Exercise01,
    Exercise02,
    Exercise03,
    Exercise04,
    Exercise05,
    Exercise06,
    Exercise07
  },
  data() {
    return {
      exercise: 0,
      numberOfComponents: 0
    }
  },
  methods: {
    onChangeSelect(event) {
      this.exercise = event.target.value;
    }
  },
  beforeMount() {
    this.numberOfComponents = Object.keys(this.$options.components).length;
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
