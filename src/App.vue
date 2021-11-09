<template>
  <div id="app">
     <div class="navbar">
    <img src="./views/logo.jpeg" height="50px" width="120px" style="float:left; margin-left:180px; margin-top:10px;"/>
  <a href="" style="float:left; margin-left:60px; font-size:15px; color:white;margin-top:5px;">About</a>
  <a  href="" style="float:left;margin-left:30px;font-size:15px; color:white;margin-top:5px;">Features</a>
  <a href="#contact" style="float:left;margin-left:30px;font-size:15px; color:white;margin-top:5px;">Roadmap</a>
  <a href="#contact" style="float:left;margin-left:30px;font-size:15px; color:white;margin-top:5px">Team</a>
  <a href="#contact" style="float:left;margin-left:30px;font-size:15px; color:white;margin-top:5px;">Faq</a>
  <button style="float:right;background-color:rgba(59,130,246,0.5); font-size:20px;padding:10px 26px;color:white;margin-right:150px; margin-top:10px; border-radius:30px;">Connected</button>
</div>
    <router-view/>
    <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Roboto:400,500,700,400italic|Material+Icons">
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.navbar {
  overflow: hidden;
  height: 65px;
  background-color:black;
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
  margin-bottom: 3px;
  box-shadow: rgb(0 0 0 / 10%) 0px 0px 20px !important;
}
/* Links inside the navbar */
.navbar a {
  display: inline-block;
  display: block;
  color: rgb(209, 209, 209);
  padding: 14px 16px;
  text-decoration: none;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 10px;
  
}
/* Change background on mouse-over */
.navbar a:hover {
  background:rgb(62, 62, 117);
  border-radius: 25px;
  color: #fd115c;
}
</style>
