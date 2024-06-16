<script>
  import Login from './Login.svelte';
  import Footer from './Footer.svelte';
  import Landing from './Landing.svelte'
  import Preloader from './Preloader.svelte';
</script>

<div class="site-layout--landing">
  <div class="site-wrapper">
    <Login />
	<Footer />
	<Landing />
  </div>
</div>

  <Preloader />
<style>
  /* .site-wrapper {
    min-height: 100vh;
  }

  .site-layout--landing .site-wrapper {
    position: absolute;
    overflow: hidden;
    display: none;
    flex-direction: column;
    justify-content: space-between;
  } */
</style>
