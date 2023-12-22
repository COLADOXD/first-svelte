<script>
  import Interior from "./Interior.svelte";
  export let nombre;

  let momento = "dia";
  //comment
</script>

<Interior />
<h1>Hola Mundo</h1>
<p>{momento} {nombre} {[1, "jarjar", "bens"]}</p>

<style>
  h1 {
    font-size: x-small;
  }
</style>
