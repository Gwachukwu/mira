<template>
  <div class="transaction-container">
    <div class="transaction-left">
      <div class="transaction-left_header">
        <p>Transaction</p>
        <p>View all</p>
      </div>
      <div class="transaction-left_details">
        <p class="transaction-left_days">TODAY</p>
        <div>
          <div class="transaction-left_desc add-border">
            <div class="big-dot"></div>
            <div class="transaction-right_account">
              <p>Bank Transfer</p>
              <p>Account funding</p>
            </div>
            <p class="transaction-left_amount">&#8358;1,000.00</p>
          </div>
        </div>
        <div>
          <div class="transaction-left_desc">
            <div class="big-dot"></div>
            <div class="transaction-right_account">
              <p>CB user transfer</p>
              <p>Account funding</p>
            </div>
            <p class="transaction-left_amount">&#8358;1,000.00</p>
          </div>
        </div>
        <p class="transaction-left_days">YESTERDAY</p>
        <div>
          <div class="transaction-left_desc">
            <div class="big-dot"></div>
            <div class="transaction-right_account">
              <p>Card</p>
              <p>Account withdrawal</p>
            </div>
            <p class="transaction-left_amount red-text">&#8358;900.00</p>
          </div>
        </div>
      </div>
    </div>
    <div class="transaction-right">
      <div class="transaction-right_header">
        <p class="header-left">Breakdown</p>
        <p class="header-right">
          Yesterday
        </p>
        <p class="up-down"><span> &#9650;</span><span>&#9660;</span></p>
      </div>
      <DonutChart/>
      <div>
        <p>Total Money Received</p>
        <p>&#8358;2,000.00</p>
        <p>Total Money Spent</p>
        <p>&#8358;900.00</p>
      </div>
    </div>
  </div>
</template>

<script>
import DonutChart from "@/components/DonutChart.vue";

export default {
  name: "Transaction",
  components:{
    DonutChart
  }
};
</script>

<style scoped>
.transaction-container {
  display: flex;
  justify-content: space-between;
  margin-top: 2.5rem;
}
.transaction-left {
  width: 612px;
  background: #ffffff;
  border-radius: 10px;
}
.transaction-right {
  width: 300px;
}
.transaction-left,
.transaction-right {
  background: #ffffff;
  border-radius: 10px;
  height: 392px;
}
.transaction-left_header {
  display: flex;
  justify-content: space-between;
  margin: 1rem 2rem 0rem 2rem;
}
.transaction-left_details {
  margin-left: 2rem;
  margin-right: 2rem;
}
.transaction-left_days {
  font-size: 14px;
  font-variant: small-caps;
  color: #333333;
  margin: 0rem;
}
.big-dot {
  width: 20px;
  height: 20px;
  background: #008080;
  border-radius: 50%;
  align-self: center;
}
.transaction-left_desc {
  display: flex;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  color: #333333;
}
.transaction-left_amount {
  margin-left: auto;
  align-self: flex-end;
  color: #219653;
}
.transaction-right_account {
  align-self: center;
  margin-left: 1.5rem;
}
.red-text {
  color: #db261b;
}
.add-border {
  border-bottom: 1px solid #e0e0e0;
}
.transaction-right > * {
  margin-left: 1rem;
  margin-right: 1rem;
}
.transaction-right_header {
  display: flex;
}
.header-right {
  margin-left: auto;
  display: inline;
  align-self:center;
  font-size: 14px;
line-height: 16px;
color: #313E3E;
}
.header-left{
  align-self:center;
  font-size: 18px;
line-height: 21px;
color: #313E3E;
}
.up-down {
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
  margin-left: 0.5rem;
}
</style>