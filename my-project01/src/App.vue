<template>
  <div id="app">
    <FormComponent />
  </div>
</template>

<script>
import FormComponent from './components/FormComponent.vue';

export default {
  name: 'App',
  components: {
    FormComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
