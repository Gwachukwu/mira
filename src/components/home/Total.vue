<template>
  <div class="total-container">
    <div class="total-container_left">
      <div class="big-circle"><span class="total-text">Total</span><p></p>&#8358;2909.98</div>
      <div class="bullet-container">
      <div class="bullet-points">
        <div class="small-circle"></div>
        <p class="bullet-text">Savings</p>
      </div>
      <div class="bullet-points">
        <div class="small-circle red-circle"></div>
        <p class="bullet-text">Business</p>
      </div>
      <div class="bullet-points">
        <div class="small-circle ash-circle"></div>
        <p class="bullet-text">Investment</p>
      </div>
      </div>
    </div>
    <div class="total-left">
      <div>
        <p class="right-text">Savings</p>
        <p class="green-text">&#8358;2909</p>
      </div>
      <div>
        <p class="right-text">Business</p>
        <p class="green-text">&#8358;0.00</p>
      </div>
      <div>
        <p class="right-text">Investment</p>
        <p class="green-text">&#8358;9.98</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name:"Total"
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.total-container {
  height: 345px;
  width: 924px;
  background-color: #fff;
  margin-top: 2rem;
  margin-bottom: 2rem;
  border-radius: 10px;
  display: flex;
}
.total-container_left{
    display: flex;
    gap: 1rem;
    justify-content:center;
    align-items: center;
    padding: 4rem;
    flex-direction: column;
}
.big-circle{
    width: 190px;
height: 190px;
background: #FFFFFF;
border: 20px solid #008080;
box-sizing: border-box;
border-radius:50%;
display:flex;
justify-content:center;
align-items: center;
flex-direction:column;
color: #313E3E;
font-size: 24px;
line-height: 28px;
}
.total-text{
    font-size: 12px;
line-height: 14px;
}
.small-circle{
    width: 15px;
height: 15px;
background: #008080;
border-radius: 50%;
}
.red-circle{
   background-color: #DB261B;
}
.ash-circle{
    background: #658383;
}
.bullet-points{
    display: flex;
}
.bullet-text{
    font-size: 12px;
line-height: 14px;
color: #828282;
margin-left: 0.5rem;
align-self: center;
}
.bullet-container{
    display: flex;
    gap:1rem;
}
.green-text{
    font-size: 14px;
line-height: 16px;
color: #219653;
margin-top: 1rem;
}
.right-text{
    font-size: 18px;
line-height: 21px;
color: #333333;
}
.total-left{
    display:flex;
    flex-direction: column;
    gap: 1.5rem;
    justify-content:center;
    margin-left: 2rem;
}
</style>