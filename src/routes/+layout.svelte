<script>

  let {children} = $props()

</script>

  <div style='background-color: #f0f0f0; padding-inline: .42em; max-width: 800px; margin-inline: auto; height: 100vh;'>
    
    <div style="padding: .42em 1em;">
      <a data-sveltekit-reload href="/">Home Page</a> 
      <a data-sveltekit-reload href="/app">Another Page</a>
    </div>
    
    {@render children()} 
  </div>


<style>

  a{
    padding-inline: 1em;
  }

</style>