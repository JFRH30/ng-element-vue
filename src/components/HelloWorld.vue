<template>
  <div>Angular Element Test on vue</div>
</template>

<script>
export default {
  name: "HelloWorld",
  // mounted() {
  //   let el = document.createElement("script");
  //   el.setAttribute("src", "assets/el.js");
  //   el.async = true;
  //   document.body.appendChild(el);
  //   let poly = document.createElement("script");
  //   poly.async = true;
  //   poly.setAttribute("src", "assets/polyfills.js");
  //   document.body.appendChild(poly);

  //   document
  //     .querySelector("#app")
  //     .appendChild(document.createElement("external-element"));
  // },
  props: {
    msg: String
  }
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
