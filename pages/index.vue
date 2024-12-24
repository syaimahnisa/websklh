<template>
    <link rel="stylesheet" href="style.css">
    <div class="image-container">
      <img src="~/assets/img/4.png" alt="SMKN 4 Kota Tasikmalaya">
      <div class="overlay-text">
        <div>Selamat Datang di Website</div>
        <div>SMKN 4 Kota Tasikmalaya</div>
      </div>
      <div class="container">
        <div class="profile">
            <img src="~/assets/img/sekolah.png" alt="Kepala Sekolah">
            <div class="profile-text">
                <h1>Sambutan kepala sekolah</h1>
                <p>Assalamu’alaikum Wr. Wb</p>
                <p>Segala puji dan syukur kehadirat Allah SWT, semoga kita semua dalam lindungan-Nya. dan atas ijin beliau kami dapat menyajikan website SMK Negeri 4 Tasikmalaya ini.
                    Kami berharap dengan adanya web site di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita bersama.
                    Tiada gading yang tak retak, web site kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
                    Akhirnya, saya mengucapkan terimakasih yang sebesar- besarnya kepada semua pihak yang tidak dapat disebutkan satu persatu atas segala bantuan dan fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi masyarakat.
                    Wassalamu’alaikum Wr, Wb</p>
                <p><strong>Kepala Sekolah</strong><br>Kurniawan, S.Pd., M.Pd.</p>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="section">
            <h2>Profile</h2>
            <h3>Visi Dan Misi</h3>
            <h3>Visi</h3>
            <p>TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA </p>
            <p>(CAKAP BERIMTAK)</p>

            <h3>Misi</h3>
            <ul class="list-group-numbered">
                <li class="list-group-item">Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</li>
                <li class="list-group-item">Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.</li>
                <li class="list-group-item">Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.</li>
                <li class="list-group-item">Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non akademik..</li>
                <li class="list-group-item">Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan..</li>
                <li class="list-group-item">Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.</li>
                <li class="list-group-item">Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</li>
                <li class="list-group-item">Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</li>
                <li class="list-group-item">Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</li>
            </ul>
        </div>
    </div>
    <div class="container">
  <h2 class="text-center my-4">Kompetensi Keahlian</h2>
  <p class="text-center">SMKN 4 Kota Tasikmalaya saat ini mempunyai Lima Kompetensi Keahlian</p>

  <div class="row justify-content-center">
    <!-- Card 1 -->
    <div class="col-md-3 my-3">
      <div class="card">
        <img src="~/assets/img/tsm.png" alt="TBSM">
        <h5 class="mt-3">TBSM</h5>
        <p>Teknik dan Bisnis Sepeda Motor</p>
      </div>
    </div>
    <!-- Card 2 -->
    <div class="col-md-3 my-3">
      <div class="card">
        <img src="~/assets/img/rpl.png" alt="PPLG">
        <h5 class="mt-3">PPLG</h5>
        <p>Pengembangan Perangkat Lunak dan Gim</p>
      </div>
    </div>
    <!-- Card 3 -->
    <div class="col-md-3 my-3">
      <div class="card">
        <img src="~/assets/img/tkj.png" alt="TKJ">
        <h5 class="mt-3">TKJ</h5>
        <p>Teknik Komputer dan Jaringan</p>
      </div>
    </div>
  </div>

  <!-- Baris Kedua -->
  <div class="row justify-content-center">
    <!-- Card 4 -->
    <div class="col-md-3 my-3">
      <div class="card">
        <img src="~/assets/img/dkv.png" alt="DKV">
        <h5 class="mt-3">DKV</h5>
        <p>Desain Komunikasi Visual</p>
      </div>
    </div>
    <!-- Card 5 -->
    <div class="col-md-3 my-3">
      <div class="card">
        <img src="~/assets/img/toi.png" alt="TOI">
        <h5 class="mt-3">TOI</h5>
        <p>Teknik Otomasi Industri</p>
      </div>
    </div>
  </div>
</div>

    </div>
</template>

<style>
.image-container img {
  width: 100vw; /* Gunakan lebar penuh viewport */
  height: auto; /* Otomatis sesuaikan tinggi */
  display: block; /* Hilangkan ruang kosong di bawah gambar */
}

/* Container untuk gambar */
.image-container {
  position: relative; /* Untuk posisi teks overlay */
  width: 100vw; /* Lebar penuh viewport */
}

.image-container .overlay-text {
  position: absolute; /* Membuat teks melayang di atas gambar */
  top: 10%; /* Posisi di tengah secara vertikal */
  color: white; /* Warna teks */
  font-size: 3em; /* Ukuran font */
  font-weight: bold; /* Menebalkan teks */
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); /* Bayangan teks */
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.profile {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    gap: 20px;
}

.profile img {
    margin-top: 50px;
    max-width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-text {
    margin-top: 50px;
    max-width: 600px;
    text-align: justify;
}

.section h2 {
    font-size: 20px;
    margin-bottom: 10px;
    border-bottom: 2px solid #007bff;
    display: inline-block;
    margin-top: 50px;
    font-size: 50px;
    display: flex;
    justify-content: center; /* Horizontal rata tengah */
}

.section h3 {
    display: flex;
    justify-content: center; /* Horizontal rata tengah */
    margin-bottom: 30px;
}

.section p {
    display: flex;
    justify-content: center; /* Horizontal rata tengah */
}

.kompetensi-keahlian {
  text-align: center;
  padding: 50px 20px;
}

.kompetensi-keahlian h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

.kompetensi-keahlian p {
  font-size: 1.2em;
  margin-bottom: 30px;
}

.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.card {
  background: #fff;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s, box-shadow 0.3s;
  text-align: center;
  display: flex; /* Tambahkan */
  flex-direction: column; /* Pastikan konten tersusun vertikal */
  align-items: center; /* Pusatkan secara horizontal */
  justify-content: center; /* Pusatkan secara vertikal */
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.card img {
  max-width: 100px;
  margin-bottom: 20px;
  display: block; /* Tambahkan untuk memastikan gambar sebagai blok */
}

.card h3 {
  font-size: 1.5em;
  margin: 10px 0;
}

.card p {
  font-size: 1em;
  color: #666;
}
</style>