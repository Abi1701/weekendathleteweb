<template>
	<link rel="stylesheet" href="/src/assets/LandingPage.css" />
	<div class="container">
		<header class="nav">
			<img src="/src/assets/walogo.png" alt="Logo" class="logo" />
			<nav class="navigation">
				<a href="#">Schedule</a>
				<a href="#">About Us</a>
			</nav>
		</header>
		<main class="content">
			<h1>
				FUN FIRST<br />
				SKILL MORE!
			</h1>
			<div class="stats">
				<div><strong>200+</strong> Peoples on WhatsApp</div>
				<div><strong>420+</strong> Peoples on Instagram</div>
			</div>
		</main>
	</div>
</template>

<style>
.container {
	position: relative;
	min-height: 100vh;
	background-image: url('/weekendathlete/src/assets/background.jpg');
	background-size: cover;
	background-position: center;
	color: #e7e8cd;
	font-family: Arial, sans-serif;
}

.nav {
	position: absolute;
	top: 20px;
	left: 20px;
	display: flex;
	align-items: center;
	gap: 20px;
}

.nav .logo {
	width: 40px;
	height: 40px;
}

.nav a {
	color: #e7e8cd;
	text-decoration: none;
	font-weight: bold;
	text-transform: uppercase;
	font-size: 14px;
}

.nav a:hover {
	text-decoration: underline;
}

.content {
	height: 100vh;
	display: flex;
	flex-direction: column;
	justify-content: center;
	padding-left: 60px;
}

.content h1 {
	font-size: 64px;
	line-height: 1.2;
	font-weight: 800;
	margin-bottom: 30px;
}

.stats {
	font-size: 20px;
	font-weight: bold;
}

.stats div {
	margin-bottom: 10px;
}
</style>