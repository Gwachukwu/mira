<template>
  <div class="announcment-conatainer">
    <p class="announcment-header">Announcement</p>
    <div class="announcment">
      <div class="small-circle"></div>
      <p>Finish your KYC</p>
    </div>
    <div class="announcment">
      <div class="small-circle"></div>
      <p>Follow us on our social media platforms</p>
    </div>
    <div class="announcment">
      <div class="small-circle"></div>
      <p>Request for a CloudBank mastercard</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Announcement",
};
</script>

<style scoped>
.announcment-header{
    margin-top: 2rem;
}
.announcment-conatainer {
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #333333;
}

.small-circle {
  width: 25px;
  height: 25px;
  background: #ffffff;
  border: 2px solid #008080;
  box-sizing: border-box;
  border-radius: 50%;
  display: inline-block;
  margin-left: 1rem;
}
.announcment {
  width: 924px;
  height: 55px;
  display: flex;
  align-items: center;
  gap: 1rem;
  background: #ffffff;
  border-radius: 10px;
  margin-bottom: 1rem;
}
</style>