<template>
  <div class="investment">
    <div class="investment-header">
      <div>
        <h1>Investment</h1>
        <p class="call-to-action">Choose from our available<br/> investment plans</p>
      </div>
      <div class="investment-tags">
        <div class="investment-tags_item">
          <p class="icon"><i class="investment-icon"></i></p>
          <p class="investment-text">investment Plans</p>
        </div>
        <div class="investment-tags_item dim">
          <p class="icon"><i class="investment-icon"></i></p>
          <p class="investment-text">Create Investment</p>
        </div>
        <div class="investment-tags_item dim">
          <p class="icon"><i class="investment-icon"></i></p>
          <p class="investment-text">Confirm Investment</p>
        </div>
      </div>
    </div>
    <Cards/>
  </div>
</template>

<script>
import Cards from "@/components/investment/Cards.vue";

export default {
  name: "investment",
  components:{
    Cards,
  }
}
</script>

<style scoped>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
.investment {
  width: 57.75rem;
}
.investment-header{
  display: flex;
  margin-top: 6rem;
}
h1{
  font-weight: 500;
font-size: 36px;
line-height: 42px;
color: #333333;
margin-bottom: 1rem;
}
.call-to-action{
  font-size: 18px;
line-height: 21px;
color: #313E3E;
}
.investment-icon{
  content: url("../assets/investment-icon.svg");
  border-radius:50%;
}
.investment-tags{
  display: flex;
  margin-top: 1.5rem;
  margin-left: 4rem;
}
.investment-tags_item{
  display: flex;
    height: 2rem;
}
.investment-text{
  align-self: center;
  margin-left:0.5rem;
  margin-right: 2rem;
  font-size: 14px;
line-height: 16px;
color: #000000;
}
.icon{
  align-self:flex-start;
}
.dim{
  opacity: 0.5;
}
</style>
