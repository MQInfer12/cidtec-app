<script lang="ts">
import Blur from "./lib/Blur.svelte";
  import EmpresaContainer from "./lib/EmpresaContainer.svelte";
import Landing from "./lib/Landing.svelte";
  import Line from "./lib/Line.svelte";
  import LinesContainer from "./lib/LinesContainer.svelte";
import Nav from "./lib/Nav.svelte";
  import ProjectsContainer from "./lib/ProjectsContainer.svelte";
  import Section from "./lib/Section.svelte";
  import TeamContainer from "./lib/TeamContainer.svelte";
</script>

<main>
  <Blur top="50vh" left="0" />
  <Blur top="25vh" left="100vw" />
  <LinesContainer />
  <Nav />
  <Landing />
  <Section title="Proyectos">
    <ProjectsContainer />
  </Section>
  <Section title="Empresa">
    <EmpresaContainer />
  </Section>
  <Section title="Equipo">
    <TeamContainer />
  </Section>
</main>

<style>
  main {
    width: 100vw;
    background-color: var(--bg800);
    position: relative;
    overflow: hidden;
  }
</style>
