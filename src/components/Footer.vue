<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Footer",
};
</script>

<template>
<footer class = "text-white p-3">
  <div class = "d-flex justify-content-around">
    <p>&copy; Quran</p>
  </div>
</footer>
</template>


<style scoped>
footer{
  font-family: Roboto;
  background: linear-gradient(50deg, #82954B, #446A46);
  animation: hue-rotate 5s linear infinite alternate;
  border-color: white;
  alignment: center;
}
@keyframes hue-rotate {
  to{filter: hue-rotate(90deg);}
}
</style>