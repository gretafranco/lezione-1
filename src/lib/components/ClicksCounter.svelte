<script>
  let { initialCount : count = $bindable() } = $props()

  let doubled = $derived(count * 2)
//  console.log('Hello, Svelte!'); 
</script>

<h3>Clicks Counter</h3>

<button onclick={() => count++}>
  clicks:{count}
</button>

<span>doubled is {doubled}</span>