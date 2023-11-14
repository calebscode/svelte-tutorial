<script>
  import '../../styles/global.css'
  import Title from '$lib/title.svelte'
</script>

<header>
  <nav>
    <Title title="Caleb's Gaming Guides"/>
    <div class="links">
      <a href="/">Home</a>
      <a href="/about">About</a>
      <a href="/guides">Guides</a>
    </div>
  </nav>
</header>

<main>
  <slot />
</main>

<footer>
  <p>Copyright 2023 Caleb's Gaming Guides</p>
</footer>

<style>
  header {
    padding: 0 10px;
    text-align: center;
    background: rgba(0, 0, 0, 0.1);
  }

  nav {
    display: flex;
    align-items: center;
    max-width: 960px;
    margin: 0 auto;
  }

  main {
    max-width: 960px;
    margin: 20px auto;
  }

  footer {
    text-align: center;
  }

  .links {
    margin-left: auto;
  }

  a {
   margin-left: 10px;
  }

</style>