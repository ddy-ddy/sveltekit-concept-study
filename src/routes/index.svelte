<script>
  let title = "ddy-ddy";
  const updateTitle = () => {
    title = "this is my first title.";
  };
</script>

<div class="index">
  <h2>{title}</h2>
  <p>这就是爱啊啊啊啊啊啊啊</p>
  <button on:click={updateTitle}>change title</button>
  <input type="text" bind:value={title} />
  <a href="/guides">View Guides</a>
  <a href="/about">About</a>
</div>

<style>
  .index {
    text-align: center;
    display: block;
    margin: 30px auto;
  }
</style>
