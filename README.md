<div align="center">
  <h1>KEBOCORAN DATA KPU/PEMILU 2025 INDONESIA</h1>
  <p>Disusun guna memenuhi tugas pada mata kuliah Etika Profesi (B) <br>
Dosen Pengampu: Adi Wahyu Pribadi, S.Si., M.Kom
    <br>
    <img width="328" height="328" alt="image" src="https://github.com/user-attachments/assets/ae7bc7a6-b686-40be-b29d-43621470408c">
    <br>

Disusun Oleh Kelompok 2:
| Nama | NPM |
|----------|----------|
| Riziq Wijaya  | 4524210091   |
| Shandika Aldino Gunawan  | 4524210097   |
| Fatih Miftahul Rizky  | 4524210107   |
| Muhamad Ibnul Fida  | 4524210112   |
| Andrian Marningot Pasaribu  | 4524210120   |
</p>
<h2>PROGRAM STUDI TEKNIK INFORMATIKA <br>
UNIVERSITAS PANCASILA <br>
2025/2026
</h2>
</div>

<div align="center">
<h2>BAB I <br>
PENDAHULUAN</h2>
</div>
<br>

<div align="justify">
<h2>1.1 Latar Belakang</h2><br>

<p>Perkembangan teknologi informasi telah mendorong digitalisasi berbagai layanan publik, termasuk dalam penyelenggaraan pemilu. Dalam proses tersebut, penyelenggara negara mengelola data pemilih dalam skala nasional melalui Daftar Pemilih Tetap (DPT). DPT bukan sekadar data administratif, tetapi memuat informasi identitas dan lokasi warga negara yang memiliki hak pilih. Oleh karena itu, perlindungan data pemilih menjadi aspek yang sangat penting, baik dari sisi privasi individu maupun dari sisi kepercayaan terhadap proses demokrasi.

Munculnya dugaan kebocoran data DPT dalam konteks Pemilu 2024 menimbulkan perhatian luas di masyarakat. Isu tersebut menjadi serius karena kebocoran data dalam jumlah besar dapat berdampak pada penyalahgunaan identitas, meningkatnya risiko penipuan, hingga menurunnya kepercayaan publik terhadap institusi penyelenggara pemilu. Dalam demokrasi, kepercayaan publik merupakan fondasi legitimasi. Oleh sebab itu, setiap dugaan kebocoran data harus dianalisis secara objektif dan komprehensif.

Selain aspek teknis keamanan informasi, isu ini juga berkaitan erat dengan tanggung jawab penyelenggara negara dan kewajiban hukum sebagaimana diatur dalam Undang-Undang Nomor 27 Tahun 2022 tentang Pelindungan Data Pribadi (UU PDP). Regulasi tersebut menegaskan bahwa setiap pengendali data pribadi wajib menjamin keamanan pemrosesan data serta melakukan pemberitahuan apabila terjadi kegagalan pelindungan data pribadi.

Dengan demikian, analisis terhadap dugaan kebocoran DPT tidak hanya penting dari sisi teknis, tetapi juga dari perspektif tata kelola pemerintahan yang baik (good governance), kepatuhan hukum, serta perlindungan hak warga negara.</p>

<h2>1.2 Rumusan Masalah</h2><br>
<p>Berdasarkan latar belakang tersebut, rumusan masalah dalam laporan ini adalah: <br>
  
1. Mengapa data DPT termasuk kategori data yang sensitif dan berisiko tinggi jika terjadi kebocoran? <br>
2. Bagaimana kemungkinan skenario teknis dan aktor ancaman dalam kebocoran data skala besar? <br>
3. Apa tanggung jawab penyelenggara negara menurut prinsip tata kelola yang baik dan UU PDP? <br>
4. Apa dampak kebocoran data terhadap privasi individu dan kepercayaan terhadap demokrasi? <br>
</p>
</div>

<div align="center">
<h2>BAB II <br>
PEMBAHASAN</h2>
</div>
<br>

<div align="justify">
<h2>2.1 DPT sebagai Data Pribadi yang Sensitif</h2><br>

<p>Daftar Pemilih Tetap (DPT) merupakan daftar resmi warga negara yang berhak mengikuti pemilu. Dalam praktiknya, DPT dapat memuat informasi seperti nama, nomor identitas, dan informasi wilayah atau alamat administratif. Kombinasi identitas dan lokasi menjadikan data ini sangat sensitif.

Risiko utama dari kebocoran DPT terletak pada kemudahan penyalahgunaan identitas. Data identitas dasar bersifat relatif permanen dan tidak mudah diubah. Berbeda dengan kata sandi yang dapat diganti, nomor identitas atau alamat tidak dapat dengan mudah dimodifikasi. Jika data tersebut bocor, dampaknya dapat berlangsung dalam jangka panjang.

Selain itu, data DPT berpotensi dikombinasikan dengan data lain yang mungkin juga pernah bocor dari platform berbeda. Proses ini dikenal sebagai data correlation, yaitu penggabungan berbagai sumber data untuk membentuk profil individu yang lebih lengkap. Hal ini meningkatkan risiko penipuan yang lebih terarah dan meyakinkan.</p>

<h2>2.2 Skenario Kebocoran dan Model Ancaman</h2><br>

<p>Dalam analisis keamanan informasi, penting untuk memahami aset yang dilindungi, aktor ancaman, serta kemungkinan jalur serangan (threat model).

Aset yang berisiko tidak hanya database utama, tetapi juga sistem pendukung seperti API, panel administrator, file cadangan (backup), kredensial akses, serta layanan vendor pihak ketiga. Banyak insiden kebocoran data besar justru berasal dari kesalahan konfigurasi atau lemahnya kontrol akses pada komponen pendukung tersebut.

Beberapa skenario teknis yang umum terjadi antara lain: <br>

1. Penggunaan kata sandi yang lemah atau tanpa autentikasi multi-faktor (MFA). <br>
2. Celah pada aplikasi atau API yang memungkinkan akses tanpa otorisasi yang memadai. <br>
3. Kesalahan konfigurasi pada layanan cloud atau penyimpanan yang membuat data dapat diakses publik. <br>
4. Risiko dari pihak ketiga (vendor) atau insider yang memiliki akses sah tetapi tidak diawasi dengan ketat. <br>
5. Aktor ancaman dapat berupa peretas eksternal, broker data yang memperjualbelikan dataset, maupun pihak internal yang menyalahgunakan akses. Motifnya bisa bersifat finansial (penjualan data, pemerasan), maupun non-finansial seperti membangun narasi tertentu atau mempengaruhi opini publik.</p>

<h2>2.3 Dampak terhadap Privasi dan Keamanan Individu</h2><br>

<p>Kebocoran data identitas dapat berdampak langsung pada individu. Pelaku kejahatan siber dapat menggunakan data tersebut untuk melakukan pencurian identitas, penipuan berbasis rekayasa sosial (social engineering), atau phishing yang lebih meyakinkan karena menyertakan informasi pribadi korban.

Sebagai contoh, seseorang dapat menerima pesan yang mengatasnamakan instansi resmi dan mencantumkan data pribadinya secara akurat. Hal ini meningkatkan kemungkinan korban mempercayai pesan tersebut dan menyerahkan informasi sensitif tambahan seperti kode OTP.

Selain itu, kebocoran alamat atau lokasi administratif dapat memunculkan risiko doxxing atau ancaman terhadap keamanan personal. Dalam skala besar, potensi kerugian ekonomi akibat penipuan juga meningkat secara signifikan.</p>

<h2>2.4 Dampak terhadap Demokrasi dan Kepercayaan Publik</h2><br>

<p>Dalam konteks pemilu, perlindungan data tidak hanya menyangkut hak privasi, tetapi juga legitimasi demokrasi. Dugaan kebocoran data dapat menurunkan tingkat kepercayaan masyarakat terhadap kemampuan penyelenggara dalam menjaga keamanan sistem.

Walaupun kebocoran data tidak secara otomatis berarti manipulasi hasil pemilu, persepsi publik yang negatif dapat melemahkan legitimasi proses demokrasi. Selain itu, data berbasis lokasi berpotensi dimanfaatkan untuk penyebaran disinformasi yang ditargetkan pada wilayah atau kelompok tertentu (micro-targeting), yang dapat meningkatkan polarisasi sosial.

Oleh karena itu, transparansi dan komunikasi publik yang jelas menjadi bagian penting dari manajemen krisis agar tidak terjadi kepanikan atau penyebaran informasi yang menyesatkan.</p>

<h2>2.5 Tanggung Jawab Penyelenggara dan Perspektif UU PDP</h2><br>

<p>Dalam kerangka UU Pelindungan Data Pribadi, lembaga yang menentukan tujuan dan cara pemrosesan data berperan sebagai Pengendali Data Pribadi. Pengendali memiliki kewajiban untuk menjamin keamanan pemrosesan data melalui langkah teknis dan organisatoris yang memadai.

UU PDP juga mengatur bahwa dalam hal terjadi kegagalan pelindungan data pribadi, pengendali wajib melakukan pemberitahuan kepada subjek data dan otoritas terkait paling lambat 3×24 jam sejak diketahui terjadinya insiden. Notifikasi tersebut seharusnya memuat jenis data yang terdampak, potensi risiko, serta langkah mitigasi yang dapat dilakukan oleh masyarakat.

Dari perspektif tata kelola pemerintahan yang baik (good governance), penyelenggara negara harus menerapkan prinsip kehati-hatian (duty of care) yang tinggi. Ini mencakup penerapan kontrol akses berbasis least privilege, penggunaan autentikasi multi-faktor, audit dan pemantauan aktivitas sistem, manajemen risiko vendor, serta kesiapan prosedur respons insiden.

Perlindungan data publik harus dilakukan secara menyeluruh (end-to-end), mulai dari perancangan sistem, operasional harian, hingga evaluasi berkala dan audit independen.

</p>
</div>

<div align="center">
<h2>BAB III <br>
PENUTUP</h2>
</div>
<br>

<div align="justify">
<h2>3.1 Kesimpulan</h2><br>

<p>DPT merupakan data pribadi yang sangat sensitif karena memuat identitas dan informasi lokasi warga negara dalam skala nasional. Dugaan kebocoran data pemilih tidak hanya berpotensi menimbulkan risiko penipuan dan pencurian identitas, tetapi juga dapat memengaruhi tingkat kepercayaan publik terhadap institusi penyelenggara pemilu.

Dari perspektif keamanan informasi, kebocoran data dapat terjadi melalui berbagai jalur, termasuk kelemahan kredensial, celah aplikasi, kesalahan konfigurasi sistem, maupun risiko pihak ketiga. Oleh karena itu, pendekatan perlindungan harus bersifat komprehensif dan tidak terbatas pada satu aspek teknis saja.

Dalam perspektif hukum, UU PDP mewajibkan pengendali data untuk menerapkan langkah pengamanan yang memadai serta melakukan notifikasi apabila terjadi kegagalan pelindungan data pribadi. Kepatuhan terhadap regulasi ini merupakan bagian dari tanggung jawab negara dalam melindungi hak privasi warga.

Secara keseluruhan, perlindungan data pemilih merupakan bagian dari perlindungan demokrasi itu sendiri. Keamanan data, transparansi, dan akuntabilitas harus berjalan beriringan untuk menjaga legitimasi proses pemilu dan kepercayaan masyarakat.</p>
</div>

<div align="left">
<h2>REFERENSI</h2>
https://journal.widyatama.ac.id/index.php/justinfo/article/view/1793 <br>
https://www.ojs.daarulhuda.or.id/index.php/MHI/article/view/823 <br>
https://dinastirev.org/JIHHP/article/view/2155 <br>
</div>

