<template>
  <!-- <v-bottom-navigation grow fixed> -->
  <v-bottom-navigation grow fixed>
    <v-btn to="/" :height="btn_size" nuxt>
      <div class="title">HOME</div>
      <v-icon :size="logo_size">home</v-icon>
    </v-btn>

    <v-btn to="profile" :height="btn_size">
      <div class="title">Profile</div>
      <v-icon :size="logo_size">account_circle</v-icon>
    </v-btn>

    <v-btn to="skills" :height="btn_size">
      <div class="title">Skill</div>
      <v-icon :size="logo_size">computer</v-icon>
    </v-btn>

    <v-btn to="products" :height="btn_size">
      <div class="title">Product</div>
      <v-icon :size="logo_size">web</v-icon>
    </v-btn>

    <v-btn to="account" :height="btn_size">
      <div class="title">Account</div>
      <v-icon :size="logo_size">contact_mail</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  data() {
    return {
      bottomNav: "recent",
      activeBtn: 1,
      btn_size: "65px",
      logo_size: "40px"
    };
  }
};
</script>

<style scoped>
.v-bottom-navigation {
  padding-bottom: 80px;
}

.title {
  font-size: 1.5em;
}
</style>