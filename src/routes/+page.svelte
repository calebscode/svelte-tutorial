<script>
  import Title from '$lib/title.svelte'
</script>

<Title title="Caleb's Gaming Guides"/>
<div class="index">
  <a href="/about">About</a>
  <a href="/guides">Guides</a>
  <p>Explore a bunch of guides written by Caleb as a demo app using Svelte and SvelteKit!</p>
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }

  a {
    padding: 20px;
  }
</style>