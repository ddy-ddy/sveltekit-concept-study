<script>
  export let title = "ddy-ddy";
</script>

<div class="title">
  <img src="/logo.svg" alt="site log" />
  <h1>{title}</h1>
</div>

<style>
  .title {
    display: flex;
  }
  .title img {
    display: inline-block;
    filter: invert(98%) sepia(18%) saturate(886%) hue-rotate(199edg)
      brightness(100%) contrast(90%);
  }
  .title h1 {
    margin-left: 10px;
  }
</style>
