<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>友情链接</h2>
    <ul>
      <li>
        <a
          href="https://github.com/Pace2Car"
          target="_blank"
          >
          我的github
        </a>
      </li>
      <li>
        <a
          href="http://127.0.0.1:8000"
          target="_blank"
        >
          我的网站
        </a>
      </li>
    </ul>
    <h2>推荐链接</h2>
    <ul>
      <li>
        <a
          href="http://www.hao123.com"
          target="_blank"
          >
          导航网站
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '欢迎使用我的系统'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
</style>
