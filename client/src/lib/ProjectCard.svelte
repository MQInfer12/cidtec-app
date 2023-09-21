<script lang="ts">
export var name: string;
export var imgSrc: string;
</script>

<article>
  <img src={imgSrc} alt={name} />
  <div class="bg">
    <p>{name}</p>
  </div>
</article>

<style>
  article {
    width: 560px;
    height: 248px;
    background-color: var(--primary500);
    border-radius: 16px;
    overflow: hidden;
    position: relative;
  }
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
  }
  .bg {
    z-index: 1;
    position: absolute;
    inset: 0;
    background: linear-gradient(270deg, var(--primary500) 31.77%, rgba(0, 0, 0, 0.00) 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    padding-left: 40%;
  }
  p {
    color: var(--white);
    letter-spacing: 8px;
    text-transform: uppercase;
    text-align: center;
    font-size: 16px;
  }
</style>