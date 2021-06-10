<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Ko :title="title"/>
  </div>
</template>


<script>
import Ko from "@/components/Ko.vue"

export default {
  components : {
    Ko
  },
  data() {
    return {
      title : 'ABOUT_TITLE'
    }
  }
}
</script>