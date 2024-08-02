<template>
    <div class="border p-2 rounded-4 border-secondary">
        <img :src="bottomImageSrc" alt="Bottom Image" class="img-fluid py-1 rounded-4 w-100">
      <div class="card-body">
        
        <div class="d-flex justify-content-between align-items-center py-2 ">
          <p class="card-title fw-bold">{{ title }}</p>
           <p class="fw-bold"> <img :src="imageSrc" alt="Image" class="img-fluid "> 68 </p>
        </div>
        
        <div class="border p-2 text-center rounded-3 border-dark fw-semibold">
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
  