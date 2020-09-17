<template>
  <div id="app">
    <div id="nav">
      <!-- <div class="left-nav">
        <a href="" class="brand"><img src="./assets/Logo.png" alt=""></a>
        <ul class="nav">
          <li><a href="">Program</a></li>
          <li><a href="">Artikel</a></li>
          <li><a href="">Tentang Kami</a></li>
          <li><a href="">Kolaborasi</a></li>
          <li><a href="">Bantuan</a></li>
        </ul>
      </div>
      <ul class="right-nav nav">
        <li><a href="" class="login">Masuk</a></li>
        <li><a href="" class="register">Daftar</a></li>
      </ul>-->

      <b-navbar toggleable="lg" type="light" variant="light">
        <b-navbar-brand>
          <img src="./assets/Logo.png" alt="Logo" />
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-nav-item-dropdown style="list-style: none;" text="Program" left>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-navbar-nav>
            <b-nav-item>Artikel</b-nav-item>
            <b-nav-item>Tentang Kami</b-nav-item>
            <b-nav-item>Kolaborasi</b-nav-item>
          </b-navbar-nav>
          <b-nav-item-dropdown style="list-style: none;" text="Bantuan" left>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>

          <b-navbar-nav class="ml-auto">
            <b-nav-item class="login">Masuk</b-nav-item>
            <b-nav-item class="register">Daftar</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <router-view />
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";

export default {};
</script>

<style lang="scss">
@import "node_modules/bootstrap/scss/bootstrap";
@import "node_modules/bootstrap-vue/src/index.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 100%!important;
}

// #nav {
// padding: 0 60px;
// display: flex;
// background-color: #745444;
// justify-content: space-between;

// a{
//   margin-left: 5px;
//   display: block;
//   padding: 10px 15px;
//   text-decoration: none;
//   font-size: 10pt;
//   color: black;
// }
// }

// .left-nav{
//   display: flex;
//   justify-content: space-around;
// }

// .nav{
//   list-style: none;
//   display: flex;
//   justify-content: space-evenly;

  .login{
    color: #FC8047!important;
  }
  .register{
    color: white!important;
    background-color: #FC8047;
    border-radius: 20px;
    padding: 0 15px;
  }
// }
</style>
