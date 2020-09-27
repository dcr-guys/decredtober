<template>
  <div id="app">
    <b-navbar centered fixed-top type="is-primary">
      <template slot="start">
        <router-link tag="b-navbar-item" to="/">
          About
        </router-link>
        <router-link tag="b-navbar-item" to="/code">
          Code
        </router-link>
        <router-link tag="b-navbar-item" to="/ink">
          Ink
        </router-link>
      </template>
    </b-navbar>
    <router-view/>
  </div>
</template>

<style lang="scss">
// Set your colors

$turquoise: #2970FF;
$blue: #2DD8A3;
$cyan: #091440;
$green: #41BE53;
$yellow: #FFC84E;
$red: #ED6D47;

$text: $cyan;
$link: $turquoise;

// Import Bulma and Buefy styles
@import "~bulma";
@import "~buefy/src/scss/buefy";
</style>
