<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="nes-container is-centered">
      <p>
        For a guide and recipes on how to configure / customize this project.
      </p>
      <p><a class="nes-btn" href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a></p>
    </div>
    <div class="nes-container with-title is-centered mt20">
      <p class="title">Installed CLI Plugins</p>
      <ul>
        <li><a class="nes-btn is-primary" href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
        <li><a class="nes-btn is-primary" href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
      </ul>
    </div>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>

    <div class="nes-container is-centered is-rounded mt20">
      <a href="https://nostalgic-css.github.io/NES.css/" target="_blank" rel="noopener" class="nes-badge">
        <span class="is-dark">NES.css</span>
      </a>
      <p>
          <!-- controllers -->
        <i class="nes-logo"></i>
        <i class="nes-jp-logo"></i>
        <i class="snes-logo"></i>
        <i class="snes-jp-logo"></i>

        <!-- octocat -->
        <i class="nes-octocat"></i>

        <!-- Copyright Nintendo -->
        <i class="nes-mario"></i>
        <i class="nes-kirby"></i>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.mt20 {
  margin-top: 20px;
}
</style>
