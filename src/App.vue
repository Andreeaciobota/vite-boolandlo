<script >
import header from './components/header.vue';
import main from './components/main.vue';
import footer from './components/footer.vue';

export default{
name: 'App',
components: {
 header,
 main,
 footer
}
}

</script>

<template>
 
    <header/>
    <main/>
    <footer/>

</template>

<style lang="scss">
  @use './scss/main.scss';
 
</style>

