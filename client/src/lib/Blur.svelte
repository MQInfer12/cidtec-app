<script lang="ts">
  export var top: string;
  export var left: string;
</script>

<div style={`top: ${top}; left: ${left}`} />

<style>
  div {
    position: absolute;
    width: 350px;
    height: 350px;
    background-color: var(--primary500);
    border-radius: 50%;
    filter: blur(160px);
    opacity: 1;
    transform: translate(-50%, -50%);

    animation: aparecer 2s forwards;
    opacity: 0;
  }

  @keyframes aparecer {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }
</style>