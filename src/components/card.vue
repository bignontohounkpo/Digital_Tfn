<template>
    <div class="border p-2 rounded-4">
        <img :src="bottomImageSrc" alt="Bottom Image" class="img-fluid py-1 rounded-4 ">
      <div class="card-body">
        
        <div class="d-flex justify-content-between align-items-center py-2 ">
          <p class="card-title">{{ title }}</p>
          <img :src="imageSrc" alt="Image" class="img-fluid ">
        </div>
        
        <div class="border p-2 text-center rounded-3">
            Place a Bid
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ImageCard',
    props: {
      title: {
        type: String,
        required: true
      },
      imageSrc: {
        type: String,
        required: true
      },
      bottomImageSrc: {
        type: String,
        required: true
      }
    }
  }
  </script>
  
  <style scoped>
  /* Aucun style supplémentaire requis puisque Bootstrap est utilisé */
  </style>
  