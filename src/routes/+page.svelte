<script>
  let title = 'Poll Party'

  const updateTitle = () => {
    title == 'Poll Party' ? title = 'Not Poll Party' : title = 'Poll Party'
  }
</script>

<div class="index">
  <h2>{title}</h2>
  <p>Create, vote, and delete polls with this incredible sample application created with Svelte and SvelteKit!</p>

  <p>This button can change the title above. Try it out!</p>
  <button on:click={updateTitle}>Change Title</button>

  <br>
  <br>

  <p>This text input's value field has been <strong>BOUND</strong> to the title above.</p>
  <input type="text" bind:value={title}>
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>