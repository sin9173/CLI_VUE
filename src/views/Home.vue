<template>
  <div>
    <h1>This is Home page</h1>
    <p>{{ name }} </p>

    <Ko title="HOME_TITLE"/>
  </div>
</template>

<script>
import Ko from "@/components/Ko.vue";

export default {
  components : {
    Ko
  },
  data() {
    return {
      name: 'co'
    }
  }
}
</script>


<style scoped>
h1 {
  color : red;
  font-size : 20px;
}
</style>
