<svelte:head>
  <title>MapMeister: AI powered tabletop map maker</title>
</svelte:head>
<!-- svelte-ignore a11y-media-has-caption -->
<!-- ignoring this rule because this is a silent video -->
<video loop autoplay>
  <source src="/BgVideo.mp4" type="video/mp4" />
</video>
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
    background-color: rgba(0, 0, 0, 0.2);
  }

  video {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: -150px;
    height: 100vh;
  }
</style>
