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
input {
	transition: 180ms ease-in-out;
	background-color: rgb(222, 222, 222);
	width: 100%;
	padding: 12px 20px;
	margin: 8px 0;
	box-sizing: border-box;
	border-radius: 15px;
	border: 3px solid rgb(0, 0, 0);
	box-shadow: -5px 5px 27px -2px rgba(0, 0, 0, 0.5)
}

input:focus {
	background-color: rgb(255, 255, 255);
	border: 5px solid rgb(52, 52, 168);
	outline: 3px solid transparent;
}

input[type="submit"] {
	background-color: rgb(255, 255, 255);
	width: 60%;
}

label {
	font-size: 1.25em;
}

form {
	display: flex;
	width: 80%;
	height: 100%;
	align-items: center;
	flex-direction: column;
	margin-top: 5%;
}

#Login {
	position: absolute;
	margin-bottom: 120%;
	font-size: 5em;
}

.LoginMain {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	background-color: var(--color-background-soft);
	height: 25%;
	width: 18%;
	position: absolute;
	border-radius: 2%;
	box-shadow: -15px 16px 11px -4px rgba(12, 12, 12, 0.5);
}
</style>