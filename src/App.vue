<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> -->

  <RouterView />
  <footer>
    <RouterLink to="/bodystatus">
      <img src="@/assets/bodystatus.svg" alt="">
    </RouterLink>
    <RouterLink to="/workoutlist">
      <img src="@/assets/workoutlist.svg" alt="">
    </RouterLink>
    <RouterLink to="/schedules">
      <img src="@/assets/schedules.svg" alt="">
    </RouterLink>
    <RouterLink to="/friends">
      <img src="@/assets/friends.svg" alt="">
    </RouterLink>
    <RouterLink to="/etc">
      <img src="@/assets/etc.svg" alt="">
    </RouterLink>
  </footer>
</template>

<style scoped>

</style>
