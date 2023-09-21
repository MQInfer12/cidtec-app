<script lang="ts">
  export var translate: string;
</script>

<div style={`transform: rotate(25deg) translateY(${translate});`} />

<style>
  div {
    width: 4000px;
    height: 1px;
    position: absolute;
    background-color: var(--primary400);
  }
</style>