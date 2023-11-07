<script setup lang="ts">

</script>

<template>
	<div class="LoginMain">
		<h1 id="Login">Login</h1>
		<form>
			<label>
				<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path fill-rule="evenodd" clip-rule="evenodd"
						d="M3.00977 5.83789C3.00977 5.28561 3.45748 4.83789 4.00977 4.83789H20C20.5523 4.83789 21 5.28561 21 5.83789V17.1621C21 18.2667 20.1046 19.1621 19 19.1621H5C3.89543 19.1621 3 18.2667 3 17.1621V6.16211C3 6.11449 3.00333 6.06765 3.00977 6.0218V5.83789ZM5 8.06165V17.1621H19V8.06199L14.1215 12.9405C12.9499 14.1121 11.0504 14.1121 9.87885 12.9405L5 8.06165ZM6.57232 6.80554H17.428L12.7073 11.5263C12.3168 11.9168 11.6836 11.9168 11.2931 11.5263L6.57232 6.80554Z"
						fill="currentColor" />
				</svg>Mail
			</label>
			<input type="email" placeholder="okpvysxct@gmail.com">
			<label>
				<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
					<path fill-rule="evenodd" clip-rule="evenodd"
						d="M6 8C4.34315 8 3 9.34315 3 11V13C3 14.6569 4.34315 16 6 16C7.65685 16 9 14.6569 9 13H15V15H17V13H18V15H20V11H9C9 9.34315 7.65685 8 6 8ZM7 13V11C7 10.4477 6.55228 10 6 10C5.44772 10 5 10.4477 5 11V13C5 13.5523 5.44772 14 6 14C6.55228 14 7 13.5523 7 13Z"
						fill="currentColor" />
				</svg>Password</label>
			<input type="password" placeholder="***** ***">
			<input type="submit">
		</form>
	</div>
</template>

<style scoped>
label {
	display: flex;
}

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
	border-radius: 5%;
	box-shadow: -15px 15px 12px -4px rgba(12, 12, 12, 0.5);
}
</style>