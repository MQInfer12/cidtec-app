<script lang="ts">
  export var translate: string;
  export var delay: string;
  export var inverse: boolean = false;
</script>

<div 
  class="container" 
  style={`transform: rotate(${inverse ? "-" : ""}25deg) translateY(${translate})`}
>
  <div 
    class="bg" 
    style={`animation-delay: ${delay};`} 
  />
</div>

<style>
  .container {
    width: 4000px;
    height: 1px;
    position: absolute;
    animation: aparecer 5s forwards;
    opacity: 0;
  }
  .bg {
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, var(--bg500) 25%, var(--primary400) 55%, var(--bg500) 85%);
    animation: moverBG 3s infinite linear
  }

  @keyframes aparecer {
    from {
      opacity: 0;
    }
    to {
      opacity: 0.5;
    }
  }

  @keyframes moverBG {
    0% {
      background-position-x: -4000px;
    }
    100% {
      background-position-x: 0;
    }
  }
</style>