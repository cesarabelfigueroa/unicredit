<template>
  <div id="header-navbar">
    <div class="container">
      <b-nav medium align="right">
        <b-nav-item v-for="section in sections" v-bind:key="section.id">{{section.name}}</b-nav-item>
      </b-nav>
    </div>
  </div>
</template>

<style>
</style>



<script>
export default {
  name: "Header",
  data: function() {
    return {
      sections: [
        { id: 0, name: "Home" },
        { id: 1, name: "About Us" },
        { id: 2, name: "Services" },
        { id: 3, name: "Team" },
        { id: 4, name: "Contact" }
      ]
    };
  }
};
</script>

<style scoped>
#header-navbar {
  height: 110px;
  transition: all 0.5s;
  z-index: 997;
  transition: all 0.5s;
  padding: 20px 0;
  position: fixed;
  left: 0;
  top: 0;
  right: 0;
  transition: all 0.5s;
  z-index: 997;
}
</style>
