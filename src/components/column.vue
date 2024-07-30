<template>
  <div class="card">
    <img :src="backgroundImage" class="card-img" alt="background image" />
    <div class="card-img-overlay">
      <h5 class="card-title">{{ title }}</h5>
      <p class="card-text">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate
        libero et velit interdum, ac aliquet odio mattis.
      </p>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "ImageCard",
  props: {
    backgroundImage: {
      type: String,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
  },
};
</script>
  
  <style scoped>
.card-img-overlay {
    background: #E8E9EA;

}
</style>
  