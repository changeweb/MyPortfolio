<template>
  <div class="skill">
    <div class="card">
      <div class="card-content">
        <div class="content">
          <h2>Open Source Projects</h2>
          <p>
            <ul>
              <li>
                <a href="https://github.com/changeweb/Unifiedtransform">
                  Unifiedtransform
                </a>
                <div>A School Management Project</div>
              
                <iframe src="https://ghbtns.com/github-btn.html?user=changeweb&repo=Unifiedtransform&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="10px"></iframe>
              </li>
              <li>
                <a href="https://github.com/Exyht/exyht">
                  Exyht
                </a>
                <div>Express your thought</div>

                <iframe src="https://ghbtns.com/github-btn.html?user=Exyht&repo=Exyht&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="10px"></iframe>
              </li>
            </ul>
          </p>
        </div>
      </div>
    </div>

    
  </div>
</template>
<script>
export default {
  name: "SkillWork",
  props: {
    msg: String
  }
};
</script>

<style scoped>
iframe {
  height: 50px;
}
.card{
  border-radius: 200px;
  margin-top: 10%;
}
</style>


