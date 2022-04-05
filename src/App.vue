<template>
  <div id="app">
    <div class="header">
      <router-link to="/">Home</router-link> |
      <router-link to="/baljeet">Baljeet</router-link> |
      <router-link to="/buford">Buford</router-link>
    </div>
    <div class="content">
      <router-view/>
    </div>
    <div class="footer">
      <a href="https://github.com/GitLlamma/creative_project_3"><img class="github" src="./assets/GitHub_Logo.png"></a>
    </div>
  </div>
</template>

<style>

#app {
  text-align: center;
}

body {
  margin: 10px 100px;
  background-color: #c5d5cb;
}

.content {
  min-height: 525px;
}

.header {
  font-family: 'Harrington';
  padding: 10px;
  font-size: 24pt;
  background-color: #eeeeee;
}

a {
  text-decoration: none;
  color: black;
}

.footer {
  padding: 10px;
  background-color: #eeeeee;
}

.github {
  height: 60px;
}

.profileImageContainer {
  border: 10px solid black;
  margin-top: 10px;
}

.profilePic {
  margin-left: auto;
  margin-right: auto;
  width: 300px;
  height: auto;
}

.description {
  margin-top: 10px;
  font-family: "Segoe Print";
  font-size: 14pt;
}

</style>
