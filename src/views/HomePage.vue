<template>
  <div class="home">
    <div>
      <img class="robot" src="../assets/robot-home.png" aria-hidden="true" />
    </div>
    <div class="get-started">
      <a href="">Get Started</a> building u r first robot!
    </div>
  </div>
</template>
<script>
export default {
  name: "HomePage",
  props: {
    msg: String
  }
};
</script>

<style>
.home {
  text-align: center;
}

.robot {
  height: 300px;
}
</style>
