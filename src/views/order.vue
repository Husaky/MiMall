<template>
  <div class="order">
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
// @ is an alias to /src

import NavFooter from "@/components/NavFooter";
import NavHeader from "@/components/NavHeader";
export default {
  name: 'order',
  components: {
    NavHeader,
    NavFooter
  }
}
</script>
