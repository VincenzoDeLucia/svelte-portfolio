<script>
	import Intro from './Intro.svelte';
	import MyServices from './MyServices.svelte';
	import Nav from './Nav.svelte';
	import AboutMe from './AboutMe.svelte';
	import MyWork from './MyWork.svelte';
</script>

<main>
	<header>
		<div class="logo">
			<img src="" alt=""/>
		</div>

		<button class="nav-toggle" aria-label="toggle navigation">
			<span class="hamburger"></span>
		</button>
		<Nav/>
	</header>

	<Intro/>
	<MyServices/>
	<AboutMe/>
	<MyWork/>

</main>

<style>
	
</style>