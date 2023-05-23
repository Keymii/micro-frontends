<script>
import Header from 'vue3_mf/Header';

export default {
  name: "app",
  components: {
    Header,
  },
};
</script>
<template>
  <div class="mt-10 text-3xl mx-auto max-w-6xl">
This header came from vue micro-frontend
<Header></Header>

  </div>
</template>