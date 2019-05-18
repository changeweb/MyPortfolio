<template>
  <div id="app">
    <div class="container" style="padding-top: 3%;">
      <div class="columns">
        <div class="column">
          <img
            width="40%"
            src="./assets/hasib.png"
            style="border-radius: 5%; padding: 2%; background-color: #fff;"
          >
          <HelloWorld/>
        </div>
        <div class="column">
          <SkillWork/>
        </div>
        <div class="column">
          <TechFrame/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import SkillWork from "./components/SkillWork";
import TechFrame from "./components/TechFrame";

export default {
  name: "App",
  components: {
    HelloWorld,
    SkillWork,
    TechFrame
  }
};
</script>

<style>
body {
  background-color: #000;
}
#app {
  height: 100vh;
  background-color: #000;
  font-family: "Satisfy", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgba(255, 255, 255, 0.685);
  font-size: 20px;
}
</style>
