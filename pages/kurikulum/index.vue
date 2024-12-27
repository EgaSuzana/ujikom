<template>
  <div class="kompetensi-container">
    <div class="header">
      <h2>📚 Kompetensi Keahlian</h2>
    </div>
    <div class="main-card">
      <div class="grid-container">
        <!-- Card 1 -->
        <div class="kompetensi-card">
          <div class="icon">
            <img src="/assets/image/tkj.png" alt="icon" />
          </div>
          <div class="content">
            <h3>Teknik Komputer dan Jaringan</h3>
            <strong>Sarana pendukung pembelajaran:</strong>
            <ul>
              <li>Bengkel TKJ</li>
              <li>Network Simulator</li>
              <li>Techno Park</li>
            </ul>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="kompetensi-card">
          <div class="icon">
            <img src="/assets/image/logo pplg.png" alt="icon" />
          </div>
          <div class="content">
            <h3>Pengembangan Perangkat Lunak Dan Gim</h3>
            <strong>Sarana pendukung pembelajaran:</strong>
            <ul>
              <li>Rps Pplg</li>
              <li>Gedung Pplg</li>
            </ul>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="kompetensi-card">
          <div class="icon">
            <img src="/assets/image/tbsm.png" alt="icon" />
          </div>
          <div class="content">
            <h3>Teknik Bisnis Sepeda Motor</h3>
            <strong>Sarana pendukung pembelajaran:</strong>
            <ul>
              <li>Bengkel Tbsm</li>
              <li>Kamera Profesional</li>
              <li>Lab Animasi</li>
            </ul>
          </div>
        </div>

        <!-- Card 4 -->
        <div class="kompetensi-card">
          <div class="icon">
            <img src="/assets/image/camera.png" alt="icon" />
          </div>
          <div class="content">
            <h3>Desain Komunikasi Visual</h3>
            <strong>Sarana pendukung pembelajaran:</strong>
            <ul>
              <li>Technopark</li>
              <li>Kamera Profesional</li>
              <li>Lab IoT</li>
            </ul>
          </div>
        </div>

        <!-- Card 5 -->
        <div class="kompetensi-card">
          <div class="icon">
            <img src="/assets/image/toi.png" alt="icon" />
          </div>
          <div class="content">
            <h3>Teknik Otomasi Industri</h3>
            <strong>Sarana pendukung pembelajaran:</strong>
            <ul>
              <li>Bengkel Mesin</li>
              <li>Simulator CNC</li>
              <li>Peralatan Las</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        <button class="btn btn-primary">Selengkapnya</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .kompetensi-container {
    font-family: Arial, sans-serif;
    padding: 20px;
    background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
  }

  .header h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
    font-size: 2em;
  }

  .main-card {
    border: 2px solid #ccc;
    border-radius: 12px;
    padding: 20px;
    background: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 20px;
    justify-items: center;
    align-items: start;
  }

  .kompetensi-card {
    border: none;
    border-radius: 12px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    background: linear-gradient(135deg, #ffffff, #e6e9f0);
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .kompetensi-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
  }

  .kompetensi-card .icon img {
    width: 50px;
    height: 50px;
    margin-bottom: 15px;
    border-radius: 50%;
    border: 2px solid #ddd;
  }

  .kompetensi-card .content h3 {
    font-size: 1.4em;
    margin: 15px 0;
    color: #333;
  }

  .kompetensi-card ul {
    list-style: none;
    padding: 0;
    text-align: left;
  }

  .kompetensi-card ul li {
    margin: 5px 0;
    color: #555;
  }

  .footer {
    text-align: center;
    margin-top: 20px;
  }

  .footer .btn {
    background-color: #007bff;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-size: 1em;
  }

  .footer .btn:hover {
    background-color: #0056b3;
  }

  .h4 {
    font-size: 1.4em;
    margin: 15px 0;
    color: #333;
  }
</style>
