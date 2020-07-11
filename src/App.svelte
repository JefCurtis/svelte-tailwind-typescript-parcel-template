<script lang="typescript">
  import Loader from "./components/loader.svelte";
  const text = "Hello world!";
</script>

<div class="m-4 flex justify-center">
  <Loader {text} />
</div>
