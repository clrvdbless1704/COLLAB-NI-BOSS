<h1>Laporan Praktikum Kelompok: Membuat Layout website menggunakan HTML</h1>

<h3>Anggota Kelompok:</h3>
<ul>
  <li>Cevyn Eduard Imanuel Dapa Talu (42430055)</li>
  <li>Gabriel Jehuda Tamedo (42430007)</li>
</ul>

<h2>Project membuat layout website toko gitar menggunakan HTML</h2>
<h3>The Guitar Hub - Website Toko Gitar</h3>
<p>Website e-commerce untuk toko gitar "The Guitar Hub" yang dibangun menggunakan HTML dan HTML Semantik. Website ini menampilkan berbagai jenis gitar akustik dan elektrik dengan informasi produk yang lengkap.</p>

<h3>Deskripsi Proyek</h3>
<p>The Guitar Hub adalah website toko gitar online yang kami rancang menggunakan HTML. Website ini menampilkan beberapa Halaman seperti Home, Product, About, Contact, dan Detail Product.</p>

<h3>Fitur Utama</h3>
<ul>
  <li><b>Halaman Home</b> - Menampilkan produk terlaris dan kategori gitar</li>
  <li><b>Halaman Products</b> - Katalog lengkap semua produk gitar</li>
  <li><b>Halaman About</b> - Informasi tentang perusahaan dan visi misi</li>
  <li><b>Halaman Contact</b> - Form kontak untuk konsultasi dengan customer service</li>
  <li><b>Halaman Detail Produk</b> - Informasi lengkap setiap produk dengan spesifikasi detail</li>
</ul>

<h3>Struktur Proyek</h3>

<h4>Dokumen HTML</h4>
<ul>
  <li>index.html - Halaman Utama</li>
  <li>about.html - Halaman Tentang Perusahaan</li>
  <li>product.html - Halaman Katalog Produk</li>
  <li>contact.html - Halaman Kontak</li>
  <br>
  <li>A1.html - Halaman Detail Produk Gitar Akustik 1</li>
  <li>A2.html - Halaman Detail Produk Gitar Akustik 2</li>
  <li>A3.html - Halaman Detail Produk Gitar Akustik 3</li>
  <li>A4.html - Halaman Detail Produk Gitar Akustik 4</li>
  <br>
  <li>E1.html - Halaman Detail Produk Gitar Elektrik 1</li>
  <li>E2.html - Halaman Detail Produk Gitar Elektrik 2</li>
  <li>E3.html - Halaman Detail Produk Gitar Elektrik 3</li>
  <li>E4.html - Halaman Detail Produk Gitar Elektrik 4</li>
</ul>

<h4>Dokumen Gambar</h4>
<ul>
  <li>logo.png - Logo Perusahaan</li>
  <li>F.png - Icon Facebook</li>
  <li>T.png - Icon Twitter</li>
  <li>I.png - Icon Instagram</li>
  <li>PIC1.png - Banner Utama</li>
  <li>PIC2.png - Banner Akustik</li>
  <li>PIC3.png - Banner Elektrik</li>
  <br>
  <li>A1.png - Gambar Produk Akustik 1</li>
  <li>A2.png - Gambar Produk Akustik 2</li>
  <li>A3.png - Gambar Produk Akustik 3</li>
  <li>A4.png - Gambar Produk Akustik 4</li>
  <br>
  <li>E1.png - Gambar Produk Elektrik 1</li>
  <li>E2.png - Gambar Produk Elektrik 2</li>
  <li>E3.png - Gambar Produk Elektrik 3</li>
  <li>E4.png - Gambar Produk Elektrik 4</li>
</ul>

<h3>Penjelasan Baris Kode</h3>
<h4>Struktur HTML (Element)</h4>
  <ul>
    <li>!DOCTYPE html</li>
      <p>!DOCTYPE html kami pakai karena doctype dipakai sebagai acuan aturan agar halaman HTML dianggap valid. Dan sekarang fungsinya lebih ke memastikan dokumen jalan dengan benar.</p>
    <li>html /html</li>
      <p>Elemen ini kami pakai karena berfungsi sebagai pembungkus seluruh konten halama dan sekaligus menentukan bahasa utama dokumen lewat atribut lang (html lang="en") </p>
    <li>head /head</li>
      <p>Elemen ini kami pakai untuk menjadi wadah informasi penting yang nggak langsung tampil ke pengunjung, seperti keyword dan deskripsi agar halaman lebih mudah dikenali di hasil pencarian.
    <li>meta charset="utf-8"</li>
      <p>Elemen ini kamu pakai karena dengan ini dokumen bisa menampilkan hampir semua karakter dari berbagai bahasa, jadi aman dipakai untuk konten teks apa pun.</p>
    <li>meta name="viewport" content="width=device-width"</li>
      <p>Kami memakai elemen ini supaya halaman bisa menyesuaikan lebar layar perangkat, khususnya di mobile, jadi tampilannya gak melebar berlebihan dan tetap nyaman dibaca.</p>
    <li>title /title</li>
      <p>Kami memakai elemen ini untuk memunculkan judul di tab browser dan juga dipakai sebagai deskripsi saat halaman dibookmark, jadi penting buat identitas juga.</p>
    <li>body /body</li>
      <p>Kami pakai elemen ini karena di sinilah semua konten utama yang ingin ditampilkan ke pengguna ditempatkan, mulai dari teks, gambar, video, sampai elemen interaktif lainnya.</p>
  </ul>

  <h4>Tag Semantik HTML5</h4>
    <ul>
      <li>header</li>
        <p>Kami memakai tag ini karena berfungsi sebagai wadah untuk bagian kepala, seperti judul, logo, atau pencarian, dan bisa dipakai bukan cuma di atas halaman tapi juga sebagai header di bagian atau article tertentu.</p>
      <li>footer</li>
        <p>Kami pakai tag ini karena berguna sebagai bagian kaki halaman untuk menampilkan info penting seperti hak cipta, kontak, atau tautan ke dokumen terkait.</p>
      <li>article</li>
        <p>Kami memakai tag ini karena cocok untuk menampilkan konten mandiri yang bisa dibagikan atau dipakai ulang, misalnya digunakan pada halaman detail produk.</p>
      <li>section</li>
        <p>Kami pakai tag ini karena berfungsi untuk membagi konten ke dalam bagian yang punya tema tertentu, sehingga lebih terstruktur dan biasanya disertai judul agar jelas maknanya.</p>
      <li>nav</li>
        <p>Kami pakai tag ini karena berfungsi sebagai wadah navigasi utama, biasanya berisi daftar link menu atau tabel isi supaya pengunjung mudah berpindah antarbagian halaman.</p>
    </ul>

  <h4>Tag Dasar</h4>
    <ul>
      <li>heading (h1,h2,h3,h4,h5,h6)</li>
        <p>Kami memakai heading (h1) sampai (h6) karena berguna untuk memberi struktur pada konten, menandai judul utama hingga subjudul.</p>
      <li>paragraphs (p)</li>
        <p>Kami pakai tag ini karena berfungsi untuk membagi teks jadi paragraf yang rapi dan mudah dibaca, dengan jarak otomatis antarparagraf sehingga konten lebih terstruktur dan enak dilihat.</p>
      <li>Lists (ul, li)</li>
        <p>Kami memakai elemen daftar (ul, li) karena membantu menyajikan konten dalam bentuk poin yang lebih terstruktur. <ul> dipakai kalau urutan tidak penting,dan <li> untuk setiap item dalam daftar.</p>
      <li>Images (img)</li>
        <p>Kami memakai tag ini karena bisa menampilkan gambar di halaman web, bikin tampilan lebih menarik, memperjelas informasi, serta tetap ramah aksesibilitas lewat atribut seperti src, alt, dan pengaturan ukuran (width/height).</p>
      <li>Links (a)</li>
        <p>Kami pakai tag ini karena berfungsi sebagai tautan (anchor) yang jadi inti dari web, memungkinkan pengunjung berpindah ke halaman lain atau bagian tertentu dengan mudah.</p>
    </ul>

<h4>Form (Element)</h4>      
    <li>form /form(a)</li>
      <p>Kami memakai elemen ini karena dapat menjadi wadah utama untuk membuat formulir HTML seperti pada halaman contact, dan dapat menyatukan semua input di dalamnya, serta memudahkan browser dan teknologi bantu mengenali serta mengolah formulir dengan baik.</p>
    <li>label /label(a)</li>
      <p>Kami pakai elemen ini karena berfungsi memberi keterangan jelas pada input formulir, bikin lebih mudah dipahami oleh pengguna biasa maupun pembaca layar, sehingga formulir jadi lebih ramah dan aksesibel.</p>


<h3>Kesimpulan</h3>
<p>Berdasarkan proyek pembuatan website toko gitar The Guitar Hub, dapat disimpulkan bahwa tujuan utama telah tercapai dengan berhasil dibangunnya website menggunakan HTML dan HTML Semantik. Website ini memiliki struktur lengkap dengan halaman-halaman utama seperti Home, Products, About, Contact, serta halaman detail produk untuk setiap gitar yang ditawarkan. Penerapan elemen-elemen semantik HTML5 seperti (header) (footer), (article), (section), dan (nav) juga sudah dilakukan dengan tepat, sehingga tidak hanya memperbaiki struktur dokumen tetapi juga membuat kode lebih mudah dipahami, dirawat, dan lebih aksesibel bagi semua pengguna. Navigasi pada website dirancang konsisten di setiap halaman, dengan header yang menampilkan logo serta menu navigasi seragam sehingga memberikan pengalaman pengguna yang profesional dan terintegrasi. Selain itu, presentasi produk ditampilkan secara informatif dengan mencantumkan gambar, deskripsi, spesifikasi teknis, dan harga, bahkan penggunaan tabel pada spesifikasi membuat informasi lebih rapi dan mudah dibaca.</p>

