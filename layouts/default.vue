<template>
  <div>
    <Navigation />
    <nuxt/>
  </div>
</template>

<script>
import Navigation from '~/components/Navigation'
export default {
  components:{
    Navigation
  },
  head(){
    return{
      bodyAttrs: {
        class: 'bg-gray-100 text-gray-800 p-6 leading-loose'
      }
    }
  }
}
</script>
