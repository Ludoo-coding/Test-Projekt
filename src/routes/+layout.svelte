<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="bg-slate-800">
	<nav class="container">
		<div class="flex items-center justify-between pt-6 pb-8" >
			<div class="flex items-center space-x-1 text-white">
				<h1>Hallo</h1>
			</div>
			<div class="place-content-end text-white hover:text-gray-300 hover:underline">
				<a href="wandonia.net">Wandonia.net</a>
			</div>
		</div>
	</nav>
</div>
{@render children()}
