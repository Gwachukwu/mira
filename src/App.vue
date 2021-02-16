<template>
  <div>
    <header class="header">
      <div class="logo">
        <img src="./assets/cloudbank Logo.svg" alt="Logo" />
      </div>
      <div class="left-header">
        <i class="far fa-bell"></i>
        <img src="./assets/Profile-pic.png" alt="profile picture" />
        <p class="name">Ezekwesili Obinna</p>
      </div>
    </header>
    <div class="main">
      <div id="nav">
        <router-link to="/"><i class="home-icon"></i>Home</router-link>
        <router-link to="/"><i class="money-icon"></i>Send Money</router-link>
        <router-link to="/about"
          ><i class="money-icon"></i>Investment</router-link
        >
        <router-link to="/"
          ><i class="Transaction-icon"></i>Transactions
          <i class="far fa-angle-down"></i
        ></router-link>
        <router-link to="/"><i class="fal fa-cog"></i>Settings</router-link>
        <router-link to="/"
          ><i class="fal fa-power-off"></i>Log out</router-link
        >
      </div>
      <router-view />
    </div>
  </div>
</template>

<style>
body {
  background-color: #e5e5e5;
  margin: 0;
  padding: 0;
  font-family: "Roboto", Arial, Helvetica, sans-serif;
}

.header {
  background-color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0.6rem 6rem 0.3rem;
  box-shadow: 2px 5px 20px #b9adad;
}

.left-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.fa-bell {
  margin-right: 2rem;
  color: #828282;
}

.name {
  margin-left: 1rem;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #333333;
}

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
} */

.main {
  display: flex;
  justify-content: space-evenly;
}

#nav {
  padding: 30px;
  width: 11.25rem;
  display: flex;
  flex-direction: column;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.home-icon {
  content: url("./assets/Home Icon.svg");
}

.Transaction-icon {
  content: url("./assets/Transaction.svg");
}

.money-icon {
  content: url("./assets/Money.svg");
}
</style>
