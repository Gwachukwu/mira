<template>
  <div class="home">
  <h1>Obinna,</h1>
    <p class="greeting">Good morning, it’s a good day to save 🤑</p>
    <Dashboard/>
    <Announcement/>
    <Transaction/>
    <Total/>
  </div>
</template>

<script>
// @ is an alias to /src
import Dashboard from "@/components/home/Dashboard.vue";
import Announcement from "@/components/home/Announcement.vue";
import Transaction from "@/components/home/Transaction.vue";
import Total from "@/components/home/Total.vue";

export default {
  name: 'Home',
  components: {
   Dashboard,
   Announcement,
   Transaction,
   Total,
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