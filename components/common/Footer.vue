<template>
  <v-bottom-navigation grow fixed>
    <v-btn to="/" height="56px" nuxt>
      <div>HOME</div>
      <v-icon large>home</v-icon>
    </v-btn>

    <v-btn to="profile" height="56px">
      <div>Profile</div>
      <v-icon large>account_circle</v-icon>
    </v-btn>

    <v-btn to="skills" height="56px">
      <div>Skill</div>
      <v-icon large>computer</v-icon>
    </v-btn>

    <v-btn to="products" height="56px">
      <div>Product</div>
      <v-icon large>web</v-icon>
    </v-btn>

    <v-btn to="account" height="56px">
      <div>Account</div>
      <v-icon large>contact_mail</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  data() {
    return {
      bottomNav: "recent",
      activeBtn: 1
    };
  }
};
</script>

<style scoped>
.v-bottom-navigation {
  padding-bottom: 80px;
}
</style>