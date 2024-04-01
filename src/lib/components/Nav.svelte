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
		<li><a href="/about">About</a></li>
		<li><a href="/services">Services</a></li>
		<li><a href="/subjects">Subjects</a></li>
		<li><a href="/contact">Contact</a></li>

		</ul>
	</div>
</div>