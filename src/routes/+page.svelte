<script lang="ts">
	import Chat from '$lib/components/Chat.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import Stats from '$lib/components/Stats.svelte';
	import HeroCards from '$lib/components/HeroCards.svelte';
	import Countdown from '$lib/components/Countdown.svelte';
	import Drawer from '$lib/components/Drawer.svelte';
	import Card from '$lib/components/Card.svelte';
</script>

<div>
	<div class="">
		<div class="">
			<Hero />
		</div>

	</div>
	<div class="container mx-auto">
		<Stats />
		<Chat />

		<div class="my-10">
			<HeroCards />
		</div>


	</div>
</div>
