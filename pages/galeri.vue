<template>
  <div class="container-fluid">
    <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Galeri <b>SMKN 4 TASIKMALAYA</b>
          </h5>
        </div>

    <section class="gallery">
      <div class="gallery-item">
        <img src="/assets/image/upacara.jpg" alt="Upacara Bendera" class="gallery-image" />
        <p class="gallery-caption">Upacara Bendera</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/hariguru.jpg" alt="Lomba Futsal" class="gallery-image" />
        <p class="gallery-caption">Hari Guru</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/gedungrps.jpeg" alt="Kunjungan Industri" class="gallery-image" />
        <p class="gallery-caption">Gedung PPLG</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/rpspplg.jpeg" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">RPS PPLG</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/ruangtkj.jpeg" alt="Kunjungan Industri" class="gallery-image" />
        <p class="gallery-caption">RPS TJKT</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/ruangtbsm.jpeg" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Bengkel TBSM</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/tp.jpeg" alt="Kunjungan Industri" class="gallery-image" />
        <p class="gallery-caption">Tecknopark</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/kelas.jpeg" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Ruang Kelas</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/lapang.jpeg" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Lapangan</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/masjid.jpeg" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Masjid</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/aula.png" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Ruangan Aula</p>
      </div>
      <div class="gallery-item">
        <img src="/assets/image/wudhu.png" alt="Pentas Seni" class="gallery-image" />
        <p class="gallery-caption">Tempat Wudhu</p>
      </div>
    </section>

    <footer class="footer">
      <p>&copy; 2024 SMK Unggul. Semua hak dilindungi.</p>
    </footer>
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
  color: #555;
  margin-top: 10px;
}

.footer {
  margin-top: 20px;
  font-size: 0.9em;
  color: #555;
}
</style>
