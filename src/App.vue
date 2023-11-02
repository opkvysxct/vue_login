<script setup lang="ts">
import HeaderComponent from './components/HeaderComponent.vue';
import LoginComponent from './components/LoginComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
</script>

<template>
	<HeaderComponent />
	<div class="LoginBase">
		<LoginComponent />
	</div>
	<FooterComponent />
</template>

<style scoped>
.LoginBase {
	display: flex;
	align-items: center;
	justify-content: center;
	height: 100%;
	width: 100%;
	position: absolute;
}
</style>