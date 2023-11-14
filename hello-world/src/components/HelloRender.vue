<script type="text/javascript">
export default {
  name: 'HelloRender',
  // functional: true,
  props: {
    msg: String,
  },
  render(createElement) {
    return createElement(
      'h1',
      {},
      this.msg,
      createElement('p', {}, [
        'For a guide and recipes on how to configure / customize this project,<br/>check out the',
        createElement(
          'a',
          {
            href: 'https://cli.vuejs.org',
            target: '_blank',
            rel: 'noopener',
          },
          'vue-cli documentatio'
        ),
      ])
    );
  },
};
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
</style>
