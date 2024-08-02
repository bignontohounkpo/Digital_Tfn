<template>
  <div class="">
    <div class="carde p-3 rounded-4">
      <img :src="backgroundImage" class=" p-2 rounded-2" alt="background image" style="background-color: #0E1218 " />
      <h6 class=" fw-bold fs-5 pt-3">{{ title }}</h6>
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
.carde {
    background: #B8BABE;

}
</style>
  