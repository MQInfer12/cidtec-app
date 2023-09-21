<script>
  import Line from "./Line.svelte";
</script>

<div>
  <Line translate="0" delay="400ms" />
  <Line translate="75px" delay="0" />
  <Line translate="130px" delay="800ms" />
  <Line translate="105px" delay="200ms" inverse />
  <Line translate="30px" delay="1000ms" inverse />
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