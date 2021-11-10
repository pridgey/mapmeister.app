<svelte:head>
  <title>MapMeister: AI powered tabletop map maker</title>
</svelte:head>
<main>
  <img src="/MapMeisterLogo.svg" style="width: 45vw" alt="MapMeister logo" />
</main>

<style>
  main {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    gap: 15px;
    align-items: center;
    justify-content: center;
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)) 0% 0% / cover,
      url(/skeleton.png) center center;
  }
</style>
