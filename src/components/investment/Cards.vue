<template>
  <div class="card-container">
    <div class="card">
      <p class="card-title">Silver</p>
      <p class="card-interest">12<span class="percent">% P/A</span></p>
      <p class="card-days">30 Days</p>
      <div class="card-features-container">
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatically Renewable
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatic Renewal Options
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Cancel Renewal Anytime
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Fast Automated Payout
        </p>
        <p class="card-button">Make Investment</p>
      </div>
    </div>
    <div class="card">
      <p class="card-title">Gold</p>
      <p class="card-interest">13<span class="percent">% P/A</span></p>
      <p class="card-days">90 Days</p>
      <div class="card-features-container">
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatically Renewable
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatic Renewal Options
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Cancel Renewal Anytime
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Fast Automated Payout
        </p>
        <p class="card-button">Make Investment</p>
      </div>
    </div>
    <div class="card">
      <p class="card-title">Diamond</p>
      <p class="card-interest">13.5<span class="percent">% P/A</span></p>
      <p class="card-days">180 Days</p>
      <div class="card-features-container">
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatically Renewable
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatic Renewal Options
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Cancel Renewal Anytime
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Fast Automated Payout
        </p>
        <p class="card-button">Make Investment</p>
      </div>
    </div>
    <div class="card">
      <p class="card-title">Platinum</p>
      <p class="card-interest">15<span class="percent">% P/A</span></p>
      <p class="card-days">12 Months</p>
      <div class="card-features-container">
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatically Renewable
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatic Renewal Options
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Cancel Renewal Anytime
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Fast Automated Payout
        </p>
        <p class="card-button">Make Investment</p>
      </div>
    </div>
    <div class="card">
      <p class="card-title">Bond</p>
      <p class="card-interest">19.50<span class="percent">% P/A</span></p>
      <p class="card-days">18 Months</p>
      <div class="card-features-container">
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatically Renewable
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Automatic Renewal Options
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Cancel Renewal Anytime
        </p>
        <p class="card-feature">
          <i class="fas fa-check"></i>Fast Automated Payout
        </p>
        <p class="card-button">Make Investment</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cards",
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.card-container {
  display: flex;
  text-align: center;
  flex-wrap: wrap;
  gap: 1rem;
  margin: 2rem 0;
}
.card {
  width: 294px;
  height: 351px;
  background: #ffffff;
  border-radius: 10px;
  background-image: url("../../assets/card-deco.png");
  background-repeat: no-repeat;
  background-position: top;
  color: #ffffff;
  margin-bottom: 3rem;
}
.card-title {
  font-weight: 500;
  font-size: 14px;
  line-height: 16px;
  margin-top: 1rem;
}
.card-interest {
  font-weight: 500;
  font-size: 36px;
  line-height: 42px;
}
.card-interest,
.card-days {
  margin-top: 0.5rem;
}
.card-days,
.card-feature,
.card-button {
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
}
.card-features-container {
  margin-top: 3rem;
}
.card-feature {
  color: #7c7c7c;
  margin-top: 1rem;
}
.card-button {
  height: 46px;
  width: 176px;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #008080;
  box-shadow: 0px 4px 5px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  margin-top: 1rem;
}
.fas {
  color: #3bb54a;
  font-size: 10px;
  margin-right: 0.3rem;
}
.percent{
    font-size:24px;
}
</style>