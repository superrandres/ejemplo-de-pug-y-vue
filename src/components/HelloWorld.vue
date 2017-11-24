<template lang="pug">
  .hello
    h1 {{ msg }}
    h2 Essential Links
    ul
      li
        a(href='https://vuejs.org', target='_blank') Core Docs
      li
        a(href='https://forum.vuejs.org', target='_blank') Forum
      li
        a(href='https://chat.vuejs.org', target='_blank') Community Chat
      li
        a(href='https://twitter.com/vuejs', target='_blank') Twitter
      br
      li
        a(href='http://vuejs-templates.github.io/webpack/', target='_blank') Docs for This Template
    h2 Ecosystem
    include HelloWorld/list.pug
</template>

<script>

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
