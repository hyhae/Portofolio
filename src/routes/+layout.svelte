<script>
	import About from "../components/about.svelte";
</script>


<head>
    <title>Hussein ElSherif</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

  
<div class="grid grid-cols-2">
    
    <div class="left-column">
      <slot name="left">
        <About></About>
      </slot>
    </div>

    <div class="right-column">
      <slot name="right"></slot>
    </div>
  </div>

<style>
    
:root{
    padding: 0px;
    margin: 0px;
    background-color: rgb(15 23 42);
    font-family: sans-serif;
    color: white;
}

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 1rem;
    height: 100vh;
  }

</style>
