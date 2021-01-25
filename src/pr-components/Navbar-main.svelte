<script>
  let links = ['home', 'contact', 'about'];
</script>

<nav>
  {#each links as link}
    <a href="#">{link}</a>
  {/each}
</nav>
