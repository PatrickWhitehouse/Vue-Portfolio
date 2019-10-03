<template>
  <section class="h-screen flex flex-col items-center justify-center">
    <h1 class="text-3xl">Patrick Whitehouse</h1>
    <h2>Front end developer based in Manchester, UK</h2>
  </section>
</template>
<script>
import Testimonials from '~/components/Testimonials'
export default {
  components:{
    Testimonials
  },
  head(){
    return{
      title: 'Patrick Whitehouse - Front end developer based in Manchester, UK'
    }
  }
}
</script>