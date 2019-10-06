<template>
  <div class="project">
      <h2>{{client}}</h2>
      <a :href=url>{{url}}</a>
  </div>
</template>

<script>
export default {
    name: 'Projects',
    props: ['client', 'url']
}
</script>
