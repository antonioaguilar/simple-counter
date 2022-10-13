<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
  setInterval(increment, 250);
</script>

<style>
   .counter {
    width: 150px;
    height: 50px;
    background-color: purple;
    color: white;
    font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
    font-size: 3em;
    line-height: 24px;
    font-weight: 400;
    text-align: center;
    margin: 15px;
    padding: 20px;
    border-radius: 25px;
  }
</style>

<svelte:options tag="simple-counter"></svelte:options>
<div class="counter">{count}</div>
