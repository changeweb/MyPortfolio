<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div>
      <h3>Hello! My name is
        <b style="font-size: 25px;">Hasib Mahmud</b>
      </h3>
    </div>
    <div>
      A Fullstack Developer
    </div>
    <div style="margin-top: 3%;">
      <h2>#---$---#</h2>
      <ul>
        <li>Intelligent , Nahh!</li>
        <li>Love Memes</li>
        <li>IQ 399</li>
        <li>I brush my teeth</li>
        <li>Email: <u>robinmilford870@gmail.com</u></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello {
  background-color: #000;
}
h3 {
  margin: 40px 0 0;
}
a {
  color: #42b983;
}
</style>
