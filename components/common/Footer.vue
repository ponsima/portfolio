<template>
  <!-- <v-bottom-navigation grow fixed> -->
  <v-bottom-navigation grow fixed>
    <v-btn to="/" :height="btn_size" nuxt>
      <div>HOME</div>
      <v-icon :size="logo_size">home</v-icon>
    </v-btn>

    <v-btn to="profile" :height="btn_size">
      <div>Profile</div>
      <v-icon :size="logo_size">account_circle</v-icon>
    </v-btn>

    <v-btn to="skills" :height="btn_size">
      <div>Skill</div>
      <v-icon :size="logo_size">computer</v-icon>
    </v-btn>

    <v-btn to="products" :height="btn_size">
      <div>Product</div>
      <v-icon :size="logo_size">web</v-icon>
    </v-btn>

    <v-btn to="account" :height="btn_size">
      <div>Account</div>
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
</style>