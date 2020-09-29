<script>
	import Kanan from "./Kanan.svelte";
</script>

<style>
  :global(body) {
    background: rgb(6, 26, 26);
    color: #fffddb;
    font-family: "Cousine", monospace;
  }
  main {
    font-family: sans-serif;
    text-align: center;
  }
  p{
display: flex;
flex: 1 3 100px;
justify-content: center;
  }
</style>

<main>
	<h2>Hello Everyone</h2>
	<p>My Name is Nisa, I Love the Logic Thinks about User-Interface and User-Experience</p>
	<Kanan />
	<Kanan />
	<Kanan />
</main>