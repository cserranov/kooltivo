<template>
  <div class="container-main">
    <div class="container-video" style="text-align: center">
      <video controls autoplay muted class="video-element">
        <source src="@/assets/videos/Bella.mp4" type="video/mp4"/>
      </video>
    </div>
    <div class="image-container"></div>
  </div>
</template>

<style scoped>
.container-main {
  margin-top: 8%;
}

.container-video {
  width: 100%;
}

.video-element {
  height: 45vw;

}

.image-container {
  width: 100%;
  height: 50vw;
  background-image: url(@/assets/img/protectorDeUnPerrito/1.png);
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}


</style>
