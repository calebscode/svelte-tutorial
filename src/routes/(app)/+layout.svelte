<script>
  import '../../styles/global.css'
  import Title from '$lib/title.svelte'
</script>

<header>
  <Title title="Caleb's Gaming Guides"/>
</header>
<main>
  <slot />
</main>
<footer>
  <p>Copyright 2023 Caleb's Gaming Guides</p>
</footer>

<style>
  header {
    display: flex;
    justify-content: center;
  }

  main {
    max-width: 960px;
    margin: 20px auto;
  }

  footer {
    text-align: center;
  }

</style>