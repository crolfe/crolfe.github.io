<template>
  <div>
    <main>
      <blog-nav />
      <blog-post />
    </main>
    <blog-footer />
  </div>
</template>

<script>
import BlogPost from "./BlogPost.vue";
import BlogNav from "./BlogNav.vue";
import BlogFooter from "./BlogFooter.vue";

export default {
  name: "blog",
  components: {
    BlogPost,
    BlogNav,
    BlogFooter,
  },
};
</script>
