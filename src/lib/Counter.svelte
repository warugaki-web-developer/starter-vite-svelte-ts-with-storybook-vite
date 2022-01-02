<script lang="ts">
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  Clicks: {count}
</button>

<style>
  button {
    width: 200px;
    padding: 1em 2em;
    font-family: inherit;
    font-size: inherit;
    font-variant-numeric: tabular-nums;
    color: #ff3e00;
    cursor: pointer;
    background-color: rgb(255 62 0 / 10%);
    border: 2px solid rgb(255 62 0 / 0%);
    border-radius: 2em;
    outline: none;
  }

  button:focus {
    border: 2px solid #ff3e00;
  }

  button:active {
    background-color: rgb(255 62 0 / 20%);
  }
</style>
