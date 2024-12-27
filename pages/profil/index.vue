<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
          <h5 style="background-color: black;" class="text-white text-center rounded-3 p-2 m-3">
            Profil <b>SMKN 4 TASIKMALAYA</b>
          </h5>
        </div>
        <div class="col-lg-12">
          <p style="background-color: whitesmoke;" class="rounded-3 p-1 m-3 text-secondary">
            <NuxtLink to="/profil" class="text-decoration-none">Profil</NuxtLink>
          </p>
        </div>
        <div class="row mt-3">
        
        <!-- Teknik Komputer dan Jaringan -->
        <!-- Sejarah -->
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Sejarah SMK Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body">
              <p>
                Sejalan dengan Program Pemerintah dibidang pendidikan Menengah Kejuruan pada saat itu yakni 
                pemerataan akses ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya
                SMK Negeri di daerah Kecamatan Purbaratu Kota  Tasikmalaya, terutama untuk menampung tamatan
                dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah
                di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan
                Pemerintah Provinsi Jawa Barat, agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
              </p>
              <!-- Tombol Aksi -->
              <div class="text-center">
                <NuxtLink to="/profil/sejarah">
                  <button class="btn btn-primary me-2">Read More</button>
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
        
        <!-- Visi dan Misi -->
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Visi dan Misi SMK Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body text-center">
              <h5 class="col-12">Visi:</h5><p class="text-center">Dengan Berlandaskan Iman dan Taqwa Menghasilkan Tamatan yang Cerdas, Akhlak Mulia, Kreatif, Aktif, Produktif (CAKAP)</p>
              <h5>Misi:</h5>
              <p class="text-center">1. Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.<br>
                2. Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.<br>
                3. Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.
              </p>
              <!-- Tombol Aksi -->
              <div class="text-center">
                <NuxtLink to="profil/Visi-Misi">
                  <button class="btn btn-primary me-2">Read More</button>
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
  
        <!-- Identitas Sekolah -->
        <div class="col-lg-12 mb-3">
          <div class="card">
            <div class="card-header bg-light">
              <h5 class="text-center"> Identitas Sekolah Menengah Kejuruan Negeri 4 Tasikmalaya</h5>
            </div>
            <div class="card-body">
              <table class="n4table tableidentitas">
            <tbody>
              <tr>
                <td><b>a.</b></td>
                <td><b>Nama Sekolah</b></td>
                <td>:</td>
                <td>SMK Negeri 4 Kota Tasikmalaya</td>
              </tr>
              <tr>
                <td><b>b.</b></td>
                <td><b>NPSN</b></td>
                <td>:</td>
                <td>20276063</td>
              </tr>
              <tr>
                <td><b>c.</b></td>
                <td><b>Nomor Statistik Sekolah</b></td>
                <td>:</td>
                <td>401327810004</td>
              </tr>
              <tr>
                <td><b>d.</b></td>
                <td><b>Alamat</b></td>
                <td>:</td>
                <td></td>
              </tr>
              <tr>
                <td></td>
                <td>Jalan</td>
                <td>:</td>
                <td>Jl Depok RT 02 RW 05</td>
              </tr>
              <tr>
                <td></td>
                <td>Kelurahan</td>
                <td>:</td>
                <td>Sukamenak</td>
              </tr>
              <tr>
                <td></td>
                <td>Kecamatan</td>
                <td>:</td>
                <td>Purbaratu</td>
              </tr>
              <tr>
                <td></td>
                <td>Kota</td>
                <td>:</td>
                <td>Tasikmalaya</td>
              </tr>
            </tbody>
          </table>
              <!-- Tombol Aksi -->
              <!-- <div class="text-center">
                  <button class="btn btn-primary me-2">Read More</button>
              </div> -->
            </div>
          </div>
        </div>
  
        <!-- Pendidik dan Tenaga Kependidikan -->
        <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center"> Pendidik dan Tenaga Kependidikan</h5>
          </div>
          <div class="card-body">
            <div class="row">
              <!-- Jumlah Guru PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-primary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 7 orang</p>
                    <p>Perempuan: 3 orang</p>
                    <p>Total: 10 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Guru Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-secondary text-white">
                    <h6 class="text-center mb-0">Jumlah Guru Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 20 orang</p>
                    <p>Perempuan: 10 orang</p>
                    <p>Total: 30 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi PNS -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-success text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi PNS</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 2 orang</p>
                    <p>Perempuan: 1 orang</p>
                    <p>Total: 3 orang</p>
                  </div>
                </div>
              </div>
              <!-- Jumlah Tenaga Administrasi Honorer -->
              <div class="col-md-6 mb-3">
                <div class="card">
                  <div class="card-header bg-warning text-white">
                    <h6 class="text-center mb-0">Jumlah Tenaga Administrasi Honorer</h6>
                  </div>
                  <div class="card-body">
                    <p>Laki-laki: 3 orang</p>
                    <p>Perempuan: 2 orang</p>
                    <p>Total: 5 orang</p>
                  </div>
                </div>
              </div>
            </div>
            <!-- Tombol Aksi -->
            <!-- <div class="text-center mt-3">
              <button class="btn btn-primary">Read More</button>
            </div> -->
          </div>
        </div>
      </div>
  
      <!-- Struktur Organisasi -->
      <div class="col-lg-12 mb-3">
        <div class="card">
          <div class="card-header bg-light">
            <h5 class="text-center">Struktur Organisasi</h5>
          </div>
          <div class="card-body">
            <ul>
              <li><strong>Kepala Sekolah:</strong> Kurniawan, S.Pd., M.Pd.</li>
              <li><strong>Komite Sekolah:</strong> H. Abun Sulaeman, S.Ag</li>
              <li><strong>PLT Kasubag TU:</strong> Yaman Suryaman, S.Sos.</li>
            </ul>
            <!-- <div class="text-center mt-3">
              <button class="btn btn-primary">Read More</button>
            </div> -->
          </div>
        </div>
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
                    <h3>10</h3>
                  </div>
                </div>
              </div>
            </div>
            <div class="text-center mt-3">
              <NuxtLink to="profil/Data-Statistik">
                <button class="btn btn-primary">Read More</button>
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>

      </div>
    </div>
  </div>
  </template>
  