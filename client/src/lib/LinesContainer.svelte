<script>
  import Line from "./Line.svelte";
</script>

<div>
  <Line translate="0" />
  <Line translate="-20px" />
</div>

<style>
  div {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>