<template>
  <section class="sidebar" id="sidebar">
    <aside class="menu">
  <p class="menu-label">
    General
  </p>
  <ul class="menu-list">
    <li><a>Dashboard</a></li>
    <!-- <li><a>Customers</a></li> -->
  </ul>
  <p class="menu-label">
    Overview
  </p>
  <ul class="menu-list">
    <li>
      <a>Elements</a>
      <ul>
        <li><router-link to="/buttons">Buttons</router-link></li>
        <li><router-link to="/progress">Progress Bars</router-link></li>
        <li><router-link to="/checkbox">Checkbox</router-link></li>
        <li><router-link to="/radio">Radio buttons</router-link></li>
      </ul>
    </li>
    <li>
      <a class="is-active ">Page Samples</a>
      <ul>
        <li><router-link to="/cards">Cards</router-link></li>
        <li><router-link to="/message">Messages</router-link></li>
        <li><router-link to="/notifications">Notifications</router-link></li>
      </ul>
    </li>
    <li><router-link to="/forms">Forms</router-link></li>
    <li><router-link to="/charts">Charts and Graphs</router-link></li>
    <li><router-link to="/train">Kiosk Demo</router-link></li>
    <li><a>POS Demo</a></li>
    <li><a>Authentication</a></li>
  </ul>
  <p class="menu-label">
    Integrations and Custom Development
  </p>
  <ul class="menu-list">
    <li><a>NodeJS</a></li>
    <li><a>Spring Boot</a></li>
    <li><a>Kafka</a></li>
    <li><a>Mulesoft</a></li>
    <li><a>SMS Alerts</a></li>
  </ul>
</aside>
    <!-- <div class="block">
      <b-field grouped group-multiline>
        <div class="control">
          <b-switch v-model="overlay">Overlay</b-switch>
        </div>
        <div class="control">
          <b-switch v-model="fullheight">Fullheight</b-switch>
        </div>
        <div class="control">
          <b-switch v-model="fullwidth">Fullwidth</b-switch>
        </div>
        <div class="control">
          <b-switch v-model="right">Right</b-switch>
        </div>
      </b-field>
    </div> -->
    
  </section>
</template>
<script>

export default {
  data() {
    return {
      open: false,
      overlay: true,
      fullheight: true,
      fullwidth: false,
      right: false
    };
  }
};
</script>


<style scoped>


</style>