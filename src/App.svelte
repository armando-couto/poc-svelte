<script>
	import Nested from './Nested.svelte';
	import Click from './Click.svelte';
	import DomEvents from './DomEvents.svelte';
</script>

<p>These styles...</p>
<Nested/>
<hr/>
<Click/>
<hr/>
<DomEvents/>

<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>