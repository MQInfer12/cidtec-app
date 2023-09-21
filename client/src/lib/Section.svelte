<script lang="ts">
export var title: string;
</script>

<section>
  <h2>{title}</h2>
  <slot />
</section>

<style>
  section {
    display: flex;
    flex-direction: column;
    gap: 80px;
    padding: 88px 64px;
  }
  h2 {
    font-weight: 400;
    letter-spacing: 6px;
    color: var(--white);
    text-transform: uppercase;
    font-size: 32px;
  }
</style>