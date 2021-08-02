<script>
  import Another from './Another.svelte';


	const pkg = {
		name: "Svelte",
		version: 3,
		speed: "blazing",
		website: "https://svelte.dev"
	}
</script>

<Another { ...pkg } />

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
