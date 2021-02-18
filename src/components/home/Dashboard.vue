<template>
  <div class="dashboard-container">
    <div class="dashboard-card dashboard-card_1">
      <p class="account-title">SAVINGS ACCOUNT</p>
      <p class="amount-container">
        <span class="account-naira">&#8358;</span
        ><span class="account-amount"> 2,900.00</span>
      </p>
    </div>
    <div class="dashboard-card">
      <p class="account-title">BUSINESS ACCOUNT</p>
      <p class="amount-container">
        <span class="account-naira">&#8358;</span
        ><span class="account-amount"> 0.00</span>
      </p>
    </div>
    <div class="dashboard-card">
        <div class="dashboard-card_3">
      <p class="d-flex">
        <span>INVESTMENTS</span> <span class="blue-text">0229238715</span>
      </p>
      <p class="investment-amount">
        <span class="tiny-text tiny-text_naira">&#8358;</span
        ><span class="big-text"> 10,000.</span
        ><span class="tiny-text tiny-text_decimal">98</span>
      </p>
      <p class="d-flex d-end">
        <span class="blue-text">8.18% </span><span>29/09/2020</span>
      </p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dashboard",
};
</script>

<style scoped>
.dashboard-container {
  display: flex;
  justify-content: space-between;
}
.dashboard-card {
  width: 18.75rem;
  height: 8.125rem;
  background: #ffffff;
  border-radius: 10px;
  font-style: normal;
  font-weight: normal;
}
.account-title {
  font-size: 14px;
  line-height: 16px;
  color: #313e3e;
  margin-top: 2rem;
}
.dashboard-card p {
  margin-left: 1.2rem;
  margin-right: 1.2rem;
}
.amount-container {
  display: flex;
  gap: 0.5rem;
}
.account-naira {
  font-size: 24px;
  align-self: center;
  color: #658383;
}
.account-amount {
  font-size: 36px;
  line-height: 1px;
  color: #313e3e;
  align-self: center;
}
.d-flex {
  display: flex;
  justify-content: space-between;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
  color: #000000;
}
.blue-text {
  color: #2f80ed;
}
.d-end {
  align-items: flex-end;
}
.investment-amount {
  align-self: center;
  display: flex;
  justify-content: center;
}
.dashboard-card_3 {
  /* display: flex;
  flex-direction: column; */
  justify-content: center;
  color: #313e3e;
}
.tiny-text {
  font-size: 18px;
  color: #658383;
}
.big-text {
  font-size: 36px;
}
.tiny-text_naira {
  align-self: flex-start;
}
.tiny-text_decimal {
  align-self: flex-end;
  margin-bottom: 0.2rem;
}
</style>