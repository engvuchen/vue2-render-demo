<script type="text/javascript">
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
  render: function(createElement) {
    return createElement('div', [
      createElement(
      'h1',
      {},
      this.msg,
    ),
    createElement(
      'h2',
      {},
      this.msg,
    )
    ])
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
