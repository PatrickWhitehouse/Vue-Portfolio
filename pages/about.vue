<template>
  <section>
      <h1 class="text-3xl">About Patrick</h1>
      <div class="flex flex-col md:flex-row">
        <div class="sm:w-1/2 order-2 md:order-1">
          <p>Hey 👋🏻. I'm Patrick, a Front End Developer based in sunny Manchester. My day to day job is working with Magento 2 and the occasional WordPress integration. I've always been passionate about technology and keep up to date with the latest trends by using platforms such as Twitter to follow the industries leaders.</p>
          <p>I thrive off learning new skills and believe it is important to have an extended range of knowledge, especially with the constant releases of new frameworks, whether that be front end or back end specific.</p>
        </div>
        <div class="sm:w-1/2 order-1 md:order-2">
          <img class="m-auto max-w-full w-1/2 md:w-3/4" src="~/assets/headshot.jpeg" alt="Portrait of Patrick Whitehouse">
        </div>
      </div>
  </section>
</template>

<script>
export default {
    head(){
    return{
      title: 'About - Patrick Whitehouse - Front end developer based in Manchester, UK'
    }
  }
}
</script>

<style>

</style>