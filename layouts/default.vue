<template>
  <div>
    <nuxt />
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from "~/components/common/Footer";
import "material-design-icons-iconfont/dist/material-design-icons.css";

export default {
  components: {
    Footer
  }
};
</script>

<style>
#wrapper {
  background-color: #fff;
}

#contents {
  padding: 100px 0;
}
</style>

