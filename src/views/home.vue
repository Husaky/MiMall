<template>
  <div class="home">
    <nav-header></nav-header>
    home
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
// @ is an alias to /src

import NavFooter from "@/components/NavFooter";
import NavHeader from "@/components/NavHeader";
export default {
  name: 'Home',
  components: {
    NavHeader,
    NavFooter
  }
}
</script>
