<template>
  <div>
    <div id="home">
      <first-div />
    </div>
    <second-div />
    <div id="donate">
      <donate />
    </div>
    <div id="contact">
      <contact />
    </div>
    <div id="how-to-vote">
      <how-to-vote />
    </div>
    <div id="order-lawn">
      <order-lawn />
    </div>
  </div>
</template>
<script>
import FirstDiv from '@/components/FirstDiv'
import SecondDiv from '@/components/SecondDiv'
import Contact from '@/components/Contact'
import HowToVote from '@/components/HowToVote'
import OrderLawn from '@/components/OrderLawn'
import Donate from '@/components/Donate'
export default {
  components: { FirstDiv, SecondDiv, Contact, HowToVote, OrderLawn, Donate },
  watch: {
    menu(val) {
      console.log(val)
    },
  },
}
</script>
<style>
.background {
  background-color: #bf1b2c;
}
</style>
