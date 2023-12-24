<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>
<!-- In public/index.html -->
<!-- <script src="https://code.jquery.com/jquery-3.1.1.min.js" integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script>
<script src="path_to_your_local_semantic.min.js"></script> -->

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="avatar">

		<div class="w-24 rounded-full">
		  <img alt="avatar" src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg" />
		</div>
	  </div>
	<button class="btn">@nguyenthieuluan</button>

	<h1 class="text-3xl font-bold underline">
		Hello world! I'm Luan
	  </h1>
	  
<!-- 
	<h2>
		try editing <strong>src/routes/+page.svelte</strong>
	</h2> -->

	<!-- <Counter /> -->
</section>

<style  lang="postcss">
	/* :global(html) {

  } */
  
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
