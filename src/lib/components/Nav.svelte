<script lang="ts">
	import { page } from '$app/stores';
	import '$lib/app.css';
	import Drawer from './Drawer.svelte';



</script>



<div class="navbar bg-base-100">
	<div class="flex-1">
		<a class="btn btn-ghost text-xl" href="/">▢ Square Tutors</a>
	</div>
	<div class="flex-2">
		<ul class="menu menu-horizontal px-1">
		<li><a href="/about" class=" hidden md:block text-sm sm:text-md md:text-lg">About</a></li>
		<li><a href="/services" class="text-sm sm:text-md md:text-lg">Services</a></li>
		<li><a href="/subjects" class="hidden md:block text-sm sm:text-md md:text-lg">Subjects</a></li>
		<li><a href="/contact" class="text-sm sm:text-md md:text-lg">Contact</a></li>

		</ul>
	</div>
</div>