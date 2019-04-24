<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="test">
      阿三
      <p>阿四</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
$redcolor: red;
$bluecolor: blue;
.test {
  color: $redcolor;
  p {
    color: $bluecolor;
  }
}
</style>




