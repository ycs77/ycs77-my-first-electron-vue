<template>
  <div class="my-video embed-responsive embed-responsive-16by9">
    <video class="embed-responsive-item" controls>
      <source src="static/videos/因為有你.mp4" type="video/mp4">
    </video>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="scss">
.my-video {
  max-width: 800px;
  margin: auto;
}
</style>

