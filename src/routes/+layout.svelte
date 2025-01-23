<script lang="ts">
	let {children} = $props();
</script>

<nav>
	<a href="/">home</a>
	<a href="/about">about</a>
  <a href="/plot">plot</a>
</nav>

{@render children()}
