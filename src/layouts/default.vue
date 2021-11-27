<template>
  <div class="wrapper">
    <div id="nav">
      <router-link to="/">Home</router-link>
    </div>
  </div>

  <slot />
</template>

<style>
@import "~/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}
</style>
