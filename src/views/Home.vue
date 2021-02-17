<template>
  <div class="home">
  <h1>Obinna,</h1>
    <p class="greeting">Good morning, it’s a good day to save 🤑</p>
    <Dashboard/>
    <Announcement/>
    <Transaction/>
  </div>
</template>

<script>
// @ is an alias to /src
import Dashboard from "@/components/Dashboard.vue";
import Announcement from "@/components/Announcement.vue";
import Transaction from "@/components/Transaction.vue";

export default {
  name: 'Home',
  components: {
   Dashboard,
   Announcement,
   Transaction,
  }
}
</script>

<style scoped>
.home {
  width:57.75rem;
  color: #333333;
}
h1{
  font-style: normal;
font-size: 34px;
line-height: 40px;
margin-top: 5rem;
}
.greeting{
  font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 1px;
}
</style>