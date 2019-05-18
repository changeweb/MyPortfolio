<template>
  <div class="tech">
    <h2>I can work with</h2>
    <article class="message">
      <div class="message-body">
        <div class="m-title">OS:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-ubuntu"></i>
            </span>
            ubuntu
          </li>
        </ul>
        <div class="m-title">FrameWorks:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-laravel"></i>
            </span>
            Laravel
          </li>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-vuejs"></i>
            </span>
            Vue.js
          </li>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-react"></i>
            </span>
            React.js
          </li>
          <li>Bulma</li>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-bootstrap"></i>
            </span>
            Bootstrap
          </li>
        </ul>

        <div class="m-title">Source Control:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-github-square"></i>
            </span>
            Github
          </li>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-bitbucket"></i>
            </span>
            Bitbucket
          </li>
        </ul>

        <div class="m-title">Continuous Integration:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-travisci"></i>
            </span>
            Travis CI
          </li>
        </ul>

        <div class="m-title">Unit test:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-travisci"></i>
            </span>
            PHPUnit
          </li>
        </ul>

        <div class="m-title">Container:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-docker"></i>
            </span>
            Docker
          </li>
        </ul>

        <div class="m-title">Payment Api:</div>
        <ul>
          <li>
            <span class="icon has-text-danger">
              <i class="fab fa-stripe"></i>
            </span>
            Stripe
          </li>
        </ul>
      </div>
    </article>
  </div>
</template>
<script>
export default {
  name: "TechFrame",
  props: {
    msg: String
  }
};
</script>

<style scoped>
.tech {
  background-color: #000;
}
.m-title {
  font-size: 20px;
  font-weight: bold;
}
</style>
