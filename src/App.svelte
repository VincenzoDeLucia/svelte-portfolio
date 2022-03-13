<script>
	
</script>

<main>
	<header>
		<div class="logo">
			<img src="" alt=""/>
		</div>

		<button class="nav-toggle" aria-label="toggle navigation">
			<span class="hamburger"></span>
		</button>
		<nav class="nav">
			<ul class="nav__list">
				<li class="nav__item"><a href="#home">Home</a></li>
				<li class="nav__item"><a href="#services">My Services</a></li>
				<li class="nav__item"><a href="#">About me</a></li>
				<li class="nav__item"><a href="#">My Work</a></li>
			</ul>
		</nav>
	</header>

	<section class="intro" id="home"> 
		<h1 class="section__title section__title--intro">Hi, I am <strong>Vincenzo De Lucia</strong></h1>
		<p class="section__subtitle section__subtitle--intro">front-end developer and UX/UI designer</p>
		<img src="" alt="Vincenzo De Lucia">
	</section>

	<section class="my-services" id="services">
		<h2 class="section__title section__title--services">What I do</h2>
		<div class="services">
			<div class="service">
				<h3></h3>
				<p></p>
			</div>
			<div class="service">
				<h3></h3>
				<p></p>
			</div>
			<div class="service">
				<h3></h3>
				<p></p>
			</div>
		</div>

		<a href="#work" class="btn">My work</a>
	</section>


</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>