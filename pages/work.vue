<template>
  <section>
    <h1 class="text-3xl">Latest projects</h1>
    <div>
      <p>Have a look below at my latest projects. I'm always keen to build my portfolio, so give me a shout if you have a project in mind!</p>
    </div>
    <Projects v-for="project in myWork" :key="project.id" :client="project.client" :url="project.link"/>
  </section>
</template>

<script>
import Projects from "~/components/Projects";
import Work from "~/assets/work";
export default {
  head() {
    return {
      title:
        "Work - Patrick Whitehouse - Front end developer based in Manchester, UK"
    };
  },
  data() {
    return {
      myWork: Work.projects
    }
  },
  components: {
    Projects
  }
}
</script>