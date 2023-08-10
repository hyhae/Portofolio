<script>
	import About from "../components/about.svelte";
  import 'normalize.css';
</script>


<head>
    <title>Hussein ElSherif</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

  
<div class="display">
    
    <div class="left-column">
      <slot name="left">
        <About></About>
      </slot>
    </div>

    <div class="right-column">
      <slot name="right">
        test
      </slot>
    </div>
  </div>

<style>
    
:root{
    background-color: rgb(15 23 42);
    font-family: sans-serif;
    color: #e2e8f0;
}

.display {
    display: flex;
    flex-direction: row;
  }

  @media (max-width: 1250px){
    .display{
      flex-direction: column;
    }
  }

</style>
