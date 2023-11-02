<script setup lang="ts">

</script>

<template>
	<div class="LoginMain">
		<h1 id="Login">Login</h1>
		<form>
			<label>Mail</label>
			<input type="email">
			<label>Password</label>
			<input type="password">
			<input type="submit">
		</form>
	</div>
</template>

<style scoped>
label {
	font-size: 1.25em;
}

form {
	display: flex;
	width: 80%;
	height: 70%;
	align-items: center;
	flex-direction: column;
	margin-bottom: 50%;
}

#Login {
	margin-bottom: 10%;
	font-size: 3em;
}

.LoginMain {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	background-color: var(--color-background-soft);
	height: 50%;
	width: 22%;
	position: absolute;
	border-radius: 2%;
	box-shadow: -15px 16px 11px -4px rgba(12, 12, 12, 0.5);
}
</style>