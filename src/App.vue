<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue';
import ReadMe from './components/ReadMe.vue';
</script>

<template>
	<div>
		<a href="https://vitejs.dev" target="_blank"> Vite </a>
		<a href="https://vuejs.org" target="_blank"> Vue </a>
	</div>
	<HelloWorld msg="Vite + Vue" />
	<ReadMe />
</template>

<style>
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
}
.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
