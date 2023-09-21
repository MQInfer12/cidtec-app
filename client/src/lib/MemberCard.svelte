<script lang="ts">
  import BG from '../assets/images/cardBG.jpeg'
</script>

<article>
  <img class="img-bg" src={BG} alt={`member-background`} />
  <div class="bottom">
    <img class="img-pr" src="https://media.discordapp.net/attachments/909979656520888351/1126345765955055686/IMG_0986.jpg?width=667&height=500" alt={`member-profile`} />
    <h3>Mauricio Molina</h3>
    <p>Full Stack Developer</p>
  </div>
</article>

<style>
  article {
    width: 310px;
    background-color: var(--bg700);
    border-radius: 16px;
    overflow: hidden;
  }
  .img-bg {
    height: 168px;
    width: 100%;
    object-fit: cover;
  }
  .bottom {
    padding: 80px 20px 55px;
    display: flex;
    flex-direction: column;
    gap: 24px;
    align-items: center;
    color: var(--white);
    position: relative;
  }
  .img-pr {
    height: 136px;
    width: 136px;
    object-fit: cover;
    border-radius: 50%;
    position: absolute;
    top: -16px;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  h3 {
    font-size: 20px;
  }
</style>