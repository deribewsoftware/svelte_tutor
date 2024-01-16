
<script>
  import Hero from "../components/Hero.svelte"
</script>



<style>
  h1{color: red;}
  .main{
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    gap: 20px;

  }
  .main main{
    flex-grow: 1;
    
    display: flex;
    flex-direction: column;
    gap: 10px;
  }
</style>


<div class="main">
  <header>Navbar</header>
  <main>
    <Hero/>
    <div class="">hero</div>
    

  </main>
  <footer>footer</footer>
</div>
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" width="50" height="50" fill="currentColor">
  <circle cx="50" cy="50" r="40" stroke="red" stroke-width="3"  fill="blue"/>
  <rect width="80" height="60" x="60" y="30" stroke="black"/>
</svg>
