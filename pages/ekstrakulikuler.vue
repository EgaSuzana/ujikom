<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Ekstrakulikuler <b>SMKN 4 TASIKMALAYA</b>
          </h5>
        </div>

        <section class="gallery text-center">
      <div class="gallery-item">
        <img src="/assets/image/futsal.png" alt="Upacara Bendera" class="gallery-image" />
        <p class="gallery-caption">Futsal</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/paskib.png" alt="Lomba Futsal" class="gallery-image" />
        <p class="gallery-caption">Paskibra</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/sepakbola.png" alt="Kunjungan Industri" class="gallery-image" />
        <p class="gallery-caption">Sepak Bola</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/pks1.png" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Pks</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/pramuka.png" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Pramuka</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/safetyriding.png" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Pks</p>
      </div>
    </section>

    </div>
  </div>
</template>

<style scoped>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
  margin: 20px 0;
}

.gallery-item {
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 10px;
  transition: transform 0.3s;
}

.gallery-item:hover {
  transform: scale(1.05);
}

.gallery-image {
  max-width: 100%;
  border-radius: 8px;
}

.gallery-caption {
  color: #000000;
  margin-top: 20px;
} 
</style>