<template>
    <div class="card">
      <div class="card-body">
        <img :src="bottomImageSrc" alt="Bottom Image" class="img-fluid mb-3">
        <div class="d-flex justify-content-between align-items-center mb-3">
          <h2 class="card-title mb-0">{{ title }}</h2>
          <img :src="imageSrc" alt="Image" class="img-fluid" style="max-width: 100px;">
        </div>
        
        <div class="border p-2 text-center">
          Ce texte ne peut pas être changé
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
  