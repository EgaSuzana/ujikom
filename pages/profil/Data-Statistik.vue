<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Statistik Data <b>SMKN 4 TASIKMALAYA</b>
          </h5>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
            <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink>/ Statistik Data
          </p>
        </div>
        <!-- Statistik Data -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center">Statistik Data</h5>
          </div>
          <div class="card-body">
            <div class="row">
              <!-- Jumlah Siswa -->
              <div class="col-md-6 mb-3">
                <div class="card bg-success text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Siswa</h6>
                    <h3>1610</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Rombel -->
              <div class="col-md-6 mb-3">
                <div class="card bg-danger text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Rombel</h6>
                    <h3>41</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Guru -->
              <div class="col-md-6 mb-3">
                <div class="card bg-warning text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Guru</h6>
                    <h3>82</h3>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi -->
              <div class="col-md-6 mb-3">
                <div class="card bg-info text-white text-center">
                  <div class="card-body">
                    <h6>Jumlah Tenaga Administrasi</h6>
                    <h3>12</h3>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
