<script lang="ts">
  import init, { greet } from "hello-wasm";
  import { onMount } from "svelte";

  onMount(async () => {
    await init();
    greet();
  });
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
