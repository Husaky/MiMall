<template>
  <div class="order">
    <order-header></order-header>
    order
    <router-view></router-view>
    <order-footer></order-footer>
  </div>
</template>

<script>
// @ is an alias to /src
import orderHeader from "@/components/orderHeader";
import orderFooter from "@/components/orderFooter";
export default {
  name: 'order',
  components: {
    orderHeader,
    orderFooter
  }
}
</script>
