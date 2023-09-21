<script>
  import MemberCard from "./MemberCard.svelte";
</script>

<div>
  <MemberCard />
  <MemberCard />
  <MemberCard />
</div>

<style>
  div {
    width: 100vw;
    display: flex;
    justify-content: center;
    gap: 80px;
  }
</style>