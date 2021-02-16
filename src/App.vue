<template>
  <div>
    <header class="header">
      <div class="logo">
        <img src="./assets/cloudbank Logo.svg" alt="Logo" />
      </div>
      <div class="left-header">
        <i class="bell-icon"></i>
        <img src="./assets/Profile-pic.png" alt="profile picture" />
        <p class="name">Ezekwesili Obinna</p>
      </div>
    </header>
    <div class="main">
      <div id="nav">
        <router-link to="/"
          ><i class="home-icon"></i><span>Home</span></router-link
        >
        <p><i class="money-icon"></i><span>Send Money</span></p>
        <router-link to="/investment"
          ><i class="money-icon"></i><span>Investment</span></router-link
        >
        <p>
          <i class="Transaction-icon"></i><span>Transaction</span>
          <i class="far fa-angle-down"></i>
        </p>
        <p><i class="settings-icon"></i><span>Settings</span></p>
        <p><i class="logout-icon"></i><span class="logout">Log out</span></p>
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

.bell-icon {
  content: url("./assets/bell.svg");
  margin-right: 2rem;
}

.name {
  margin-left: 1rem;
  font-style: normal;
  font-weight: normal;
  font-size: 1.25rem;
  line-height: 1.313rem;
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
  margin-top: 1.2rem;
}

#nav a,
#nav p {
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 21px;
  color: #333333;
  text-decoration: none;
  display: flex;
  padding: 0.5rem 1rem;
  align-items: center;
  gap: 0.7rem;
}

#nav a.router-link-exact-active {
  background: #ffffff;
  box-shadow: 0px 4px 5px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
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

.settings-icon {
  content: url("./assets/settings.svg");
}

.logout-icon {
  content: url("./assets/Log out.svg");
}

.logout{
  color:#DB261B;
}
</style>
