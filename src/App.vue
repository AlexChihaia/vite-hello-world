<script >
import FooterComponent from './components/FooterComponent.vue';
export default {
  data() {
    return {
      title: 'Hello Vite!',
      subtitle: 'Pleasure to meet you'
    }
  },
  components: {
    FooterComponent
  },
}
</script>

<template>
  <div class="container">
    <h1>{{ title }}</h1>
    <h3>{{ subtitle }}</h3>
    <FooterComponent />
  </div>
</template>


<style scoped>
.container {
  width: 1000px;
  text-align: center;
  background-color: bisque;
  height: 900px;
  margin: auto;
}

.container h1 {
  color: cadetblue;
}

.container h3 {
  color: blueviolet;
}
</style>
