<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 <h1>Hello Vite + Vue!</h1>
 <article class="uk-article">
    <h1 class="uk-article-title">Dit is een uikit test</h1>
    <p class="uk-article-meta"></p>
</article>
<span class="uk-badge">200</span>

<div class="uk-inline">
    <button class="uk-button uk-button-default" type="button">Hover</button>
    <div uk-dropdown>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
</div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
