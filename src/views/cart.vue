<template>
  <div id="cart">
    <order-header></order-header>
    cart
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import orderHeader from "@/components/orderHeader";
import NavFooter from "@/components/NavFooter";
export default {
  name: "cart",
  components: {
    orderHeader,
    NavFooter
  }
}
</script>

<style scoped>

</style>
