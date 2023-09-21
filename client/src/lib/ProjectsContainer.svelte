<script>
  import ProjectCard from "./ProjectCard.svelte";
</script>

<div>
  <ProjectCard 
    name="Psicotest" 
    imgSrc="https://media.discordapp.net/attachments/909979656520888351/1154214103741632642/image.png?width=1015&height=500" 
  />
  <ProjectCard 
    name="Plataforma turismo Cocha" 
    imgSrc="https://media.discordapp.net/attachments/909979656520888351/1154221901951017122/image.png?width=1019&height=500" 
  />
  <ProjectCard 
    name="Cubierto" 
    imgSrc="https://media.discordapp.net/attachments/909979656520888351/1154222571408080986/image.png?width=1021&height=500" 
  />
  <ProjectCard 
    name="Pesquizas" 
    imgSrc="https://cemp.es/wp-content/uploads/2022/03/estudiar-trabajar-laboratorio-clinico.jpg.webp" 
  />
</div>

<style>
  div {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap: 72px;
    column-gap: 200px;
  }
</style>