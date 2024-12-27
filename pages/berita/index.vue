<template>
  <div id="app">
    <div class="container-fluid">
      <div class="row">
        <div class="header">
          <h2 class="text-white text-center">Berita Terbaru</h2>
        </div>
        <!-- Berita Terbaru -->
        <div class="col-md-6 p-3">
          <div class="card">
            <div class="card-header bg-primary text-white text-center">
              <h5>Berita</h5>
            </div>
            <div class="card-body">
              <div class="berita-item">
                <div class="d-flex">
                  <img src="" alt="Icon" class="icon mr-3">
                  <div>
                    <h6 class="text-danger">Pengumuman Kelulusan Siswa Tahun Pelajaran 2023/2024</h6>
                    <p class="mb-1 text-muted">06-06-2024 - SMKN 4 Tasikmalaya</p>
                  </div>
                </div>
                <hr />
                <div class="d-flex">
                  <img src="" alt="Icon" class="icon mr-3">
                  <div>
                    <h6 class="text-danger">Hasil Seleksi PPDB Tahap 2 Tahun 2020</h6>
                    <p class="mb-1 text-muted">08-07-2020 - Taufik Hidayat</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card-footer text-center">
              <button class="btn btn-primary">Indeks Berita</button>
            </div>
          </div>
        </div>

        <!-- Pengumuman Terbaru -->
        <div class="col-md-6 p-3">
          <div class="card">
            <div class="card-header bg-danger text-white text-center">
              <h5>Pengumuman Terbaru</h5>
            </div>
            <div class="card-body">
              <div class="pengumuman-item">
                <div class="d-flex">
                  <img src="" alt="Icon" class="icon mr-3">
                  <div>
                    <h6>Konfirmasi Kunjungan Industri 2020</h6>
                    <p class="mb-1 text-muted">03-01-2020 - Kepada Siswa</p>
                  </div>
                </div>
                <hr />
                <div class="d-flex">
                  <img src="" alt="Icon" class="icon mr-3">
                  <div>
                    <h6>Hasil Gladi Bersih UNBK 2020</h6>
                    <p class="mb-1 text-muted">22-01-2020</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card-footer text-center">
              <button class="btn btn-danger">Indeks Pengumuman</button>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

.header {
  background-color: #555;
  text-align: center;
}

.container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 20px;
}

/* Slider */
.slider {
  flex: 3;
  position: relative;
  background-color: #fff;
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  overflow: hidden;
}

.slider-content {
  padding: 20px;
  text-align: center;
}

.slider-content h2 {
  font-size: 18px;
  background-color: rgba(0, 0, 0, 0.7);
  color: #fff;
  padding: 10px;
  border-radius: 5px;
}

.slider-content p {
  margin: 10px 0;
  font-size: 14px;
  color: #555;
}

.slider-image {
  width: 100%;
  height: auto;
  margin: 10px 0;
}

.slider-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.btn-berita {
  background-color: #007bff;
  color: #fff;
  padding: 8px 15px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.btn-berita:hover {
  background-color: #0056b3;
}
</style>
