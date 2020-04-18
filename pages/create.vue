<template>
  <div>
    <h1>create</h1>
  </div>
</template>

<script>
import NavBar from "~/components/NavBar.vue";
export default {
  head() {
    // used by vue-meta
    return {
      title: "Create an Event",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Where you can create an events",
        },
      ],
    };
  },
  components: {
    NavBar,
  },
};
</script>
