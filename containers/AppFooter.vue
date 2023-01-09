<template>
  <footer class="py-5">
    <div class="container d-flex justify-content-between align-items-center">
      <small>&copy; 2021 MoovieTime. All rights reserved</small>
      <b-img
        class="img-grey"
        src="../assets/img/MoovieTime-Logo-Grey@2x.png"
      ></b-img>

      <small>Made with NuxtJS and Bootstrap-Vue</small>
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style>
footer {
  background-color: #15191e;
}

small {
  font-weight: 400;
  font-size: 13px;
  line-height: 15.85px;
  color: #929292;
}

.img-grey {
  width: 88.1px;
  height: 24.36px;
}
</style>
