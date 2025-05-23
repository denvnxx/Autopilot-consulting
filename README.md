# Autopilot-consulting
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Autopilot Consulting</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; background: #fff; color: #000;
  }
  header {
    background-color: #000; color: #fff;
    padding: 20px 0; text-align: center;
    font-size: 2rem; font-weight: bold; letter-spacing: 1.5px;
  }
  nav {
    background-color: #111;
    display: flex; justify-content: center; padding: 10px 0;
  }
  nav a {
    color: #fff; text-decoration: none;
    margin: 0 20px; font-weight: 600; font-size: 1.1rem;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #888;
  }
  main {
    max-width: 900px; margin: 30px auto; padding: 0 20px;
  }
  section {
    margin-bottom: 50px;
  }
  h2 {
    color: #000;
    border-bottom: 3px solid #000;
    padding-bottom: 8px; margin-bottom: 20px;
  }
  ul.services {
    list-style-type: none; padding-left: 0;
  }
  ul.services li {
    background-color: #eee;
    margin-bottom: 12px; padding: 12px 18px;
    border-radius: 6px;
    font-size: 1.05rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
    color: #000;
  }
  ul.services li:hover {
    background-color: #ccc;
  }
  form label {
    display: block; margin-bottom: 6px; font-weight: 600;
  }
  form input[type="text"],
  form input[type="email"],
  form input[type="number"],
  form input[type="date"],
  form select,
  form textarea {
    width: 100%; padding: 10px; margin-bottom: 15px;
    border-radius: 5px; border: 1px solid #000;
    font-size: 1rem; box-sizing: border-box; resize: vertical;
    background: #fff; color: #000;
  }
  form button {
    background-color: #000; color: white; border: none;
    padding: 12px 25px; font-size: 1.1rem;
    border-radius: 5px; cursor: pointer;
    transition: background-color 0.3s ease;
  }
  form button:hover {
    background-color: #444;
  }
  footer {
    background-color: #111; color: white;
    text-align: center; padding: 15px 20px;
    position: fixed; bottom: 0; width: 100%;
    font-size: 0.9rem;
  }
  @media (max-width: 600px) {
    nav {
      flex-direction: column;
    }
    nav a {
      margin: 10px 0;
    }
    footer {
      position: static;
    }
  }
  section { display: none; }
  section.active { display: block; }
  .back-btn {
    background-color: #888;
    color: #000;
    border: none;
    padding: 8px 15px;
    border-radius: 5px;
    cursor: pointer;
    margin-bottom: 20px;
    font-weight: 600;
  }
  .back-btn:hover {
    background-color: #555;
    color: #fff;
  }
  .illustration3d {
    max-width: 400px;
    margin: 20px auto 40px;
    display: block;
    border-radius: 20px;
    box-shadow: 0 6px 24px rgba(0,0,0,0.08);
  }
  ul.bengkel-list {
    list-style-type: none;
    padding-left: 0;
  }
  ul.bengkel-list li {
    background-color: #f0f0f0;
    margin-bottom: 10px;
    padding: 12px 15px;
    border-radius: 6px;
    font-size: 1rem;
  }
  ul.bengkel-list li a {
    color: #000;
    text-decoration: none;
    font-weight: 600;
  }
  ul.bengkel-list li a:hover {
    text-decoration: underline;
  }
</style>
</head>
<body>
<header>Autopilot Consulting</header>
<nav>
  <a href="#" data-target="home">Beranda</a>
  <a href="#" data-target="services">Layanan</a>
  <a href="#" data-target="bengkel">Bengkel Authorized</a>
  <a href="#" data-target="article">Artikel</a>
  <a href="#" data-target="consultation">Konsultasi</a>
  <a href="#" data-target="contact">Kontak</a>
</nav>
<main>
  <!-- Home -->
  <section id="home" class="active">
  <h2>Selamat Datang di Autopilot Consulting</h2>
  <p>
    Autopilot Consulting hadir sebagai mitra terpercaya Anda dalam dunia otomotif, khususnya dalam memberikan solusi konsultasi kendaraan mobil yang profesional dan menyeluruh. Kami memahami bahwa setiap kendaraan memiliki karakteristik unik dan kebutuhan perawatan yang berbeda-beda. Oleh karena itu, kami berkomitmen untuk menyediakan layanan konsultasi yang tidak hanya cepat dan tepat, tetapi juga personal sesuai dengan kondisi dan kebutuhan kendaraan Anda.
  </p>
  <p>
    Dengan pengalaman dan pengetahuan mendalam di bidang otomotif, tim kami siap membantu Anda dalam berbagai aspek, mulai dari diagnosis masalah teknis, estimasi biaya perbaikan dan servis, hingga rekomendasi bengkel authorized yang terpercaya di wilayah Jabodetabek. Kami percaya bahwa informasi yang akurat dan konsultasi yang tepat dapat membantu Anda menghindari biaya perbaikan yang tidak perlu dan menjaga kendaraan Anda tetap dalam performa terbaik.
  </p>
  <p>
    Selain itu, kami juga menyediakan berbagai artikel edukasi otomotif yang dirancang khusus untuk meningkatkan pemahaman Anda tentang pentingnya perawatan kendaraan secara rutin. Kami ingin memastikan Anda tidak hanya mendapatkan layanan konsultasi, tetapi juga pengetahuan yang berguna agar dapat merawat kendaraan dengan lebih baik dan bijak.
  </p>
  <p>
    Bergabunglah dengan ribuan pelanggan kami yang telah merasakan manfaat dari layanan kami. Autopilot Consulting adalah solusi terbaik untuk menjaga kendaraan Anda tetap prima, aman, dan nyaman digunakan setiap hari. Mari wujudkan pengalaman berkendara yang menyenangkan dan bebas khawatir bersama kami.
  </p>
  <img src="https://cdn.pixabay.com/photo/2021/09/15/20/14/car-6627578_1280.png" alt="Ilustrasi 3D Konsultasi Mobil" class="illustration3d" />
</section>

  <!-- Services -->
  <section id="services">
    <h2>Layanan Kami</h2>
    <ul class="services">
      <li data-service="konsultasi-teknis">Konsultasi Masalah Teknis Kendaraan</li>
      <li data-service="estimasi-biaya">Estimasi Biaya Perbaikan dan Servis</li>
      <!-- Rekomendasi bengkel dihapus dari sini -->
      <li data-service="artikel-edukasi">Artikel Edukasi Otomotif Terbaru</li>
    </ul>
  </section>

  <!-- Service Detail & Form -->
  <section id="service-detail">
    <button class="back-btn" onclick="showSection('services')">← Kembali ke Layanan</button>
    <h2 id="service-title"></h2>
    <p id="service-description"></p>

    <form id="service-form">
      <!-- Form akan berubah sesuai layanan -->
    </form>
  </section>

  <!-- Bengkel Authorized -->
  <section id="bengkel">
    <h2>Rekomendasi Bengkel Authorized di Jabodetabek</h2>

    <h3>Toyota</h3>
    <ul class="bengkel-list">
      <li><a href="https://www.auto2000.co.id/" target="_blank" rel="noopener">Auto2000 Toyota Siliwangi (Jakarta)</a></li>
      <li><a href="https://www.auto2000.co.id/" target="_blank" rel="noopener">Auto2000 Toyota Yasmin (Bogor)</a></li>
    </ul>

    <h3>Honda</h3>
    <ul class="bengkel-list">
      <li><a href="https://hondafatmawati.co.id/" target="_blank" rel="noopener">Honda Fatmawati (Jakarta Selatan)</a></li>
      <li><a href="https://www.hondacengkareng.com/" target="_blank" rel="noopener">AHASS Cengkareng (Jakarta Barat)</a></li>
    </ul>

    <h3>BMW</h3>
    <ul class="bengkel-list">
      <li><a href="https://anugrahmotor.co.id/" target="_blank" rel="noopener">Anugrah Motor (Jakarta Selatan, Kemayoran, Tangerang Selatan)</a></li>
      <li><a href="https://www.karuniajayaabadi.com/" target="_blank" rel="noopener">Karunia Jaya Abadi Motor (Jakarta Selatan)</a></li>
      <li><a href="https://primabmw.com/" target="_blank" rel="noopener">Prima BMW & MINI Cooper (Jakarta Selatan)</a></li>
    </ul>

    <h3>MINI</h3>
    <ul class="bengkel-list">
      <li><a href="https://mini-indonesia.com/plaza-mini-pondok-indah-jakarta/" target="_blank" rel="noopener">Plaza MINI Pondok Indah (Jakarta Selatan)</a></li>
    </ul>
  </section>

  <!-- Article -->
  <section id="article">
    <h2>Kenapa Merawat Kendaraan Itu Penting?</h2>
    <p>Merawat kendaraan secara rutin bukan hanya soal menjaga penampilan, tapi juga memastikan performa dan keamanan Anda di jalan. Kendaraan yang dirawat dengan baik akan:</p>
    <ul>
      <li>Meningkatkan efisiensi bahan bakar sehingga hemat biaya operasional.</li>
      <li>Mencegah kerusakan besar yang bisa menyebabkan pengeluaran mahal.</li>
      <li>Menjamin kenyamanan dan keselamatan selama berkendara.</li>
      <li>Memperpanjang umur kendaraan sehingga nilai jual tetap tinggi.</li>
      <li>Mengurangi emisi gas buang yang berbahaya bagi lingkungan.</li>
    </ul>
    <p>Dengan melakukan servis berkala sesuai rekomendasi pabrikan, Anda membantu menjaga kondisi mesin, sistem rem, kelistrikan, dan komponen penting lainnya dalam kondisi optimal. Jangan tunda perawatan kendaraan Anda, karena investasi kecil hari ini akan memberikan manfaat besar di masa depan.</p>
  </section>

  <!-- Consultation -->
  <section id="consultation">
    <h2>Formulir Konsultasi Umum</h2>
    <form onsubmit="alert('Terima kasih, konsultasi Anda telah terkirim!'); return false;" enctype="multipart/form-data">
      <label for="name">Nama Lengkap:</label>
      <input type="text" id="name" name="name" required />
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />
      
      <label for="issue">Masalah Kendaraan:</label>
      <textarea id="issue" name="issue" rows="5" required></textarea>
      
      <label for="attachment">Upload Foto/Video (opsional):</label>
      <input type="file" id="attachment" name="attachment" accept="image/*,video/*" />
      
      <button type="submit">Kirim Konsultasi</button>
    </form>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Kontak Kami</h2>
    <p>Email: <a href="mailto:info@autopilotconsulting.com" style="color:#000;">info@autopilotconsulting.com</a></p>
    <p>Telepon: +62 21 1234 5678</p>
    <p>Alamat: Jl. Otomotif No. 45, Jakarta, Indonesia</p>
  </section>
</main>
<footer>
  &copy; 2025 Autopilot Consulting. All rights reserved.
</footer>

<script>
  const navLinks = document.querySelectorAll('nav a');
  navLinks.forEach(link => {
    link.addEventListener('click', e => {
      e.preventDefault();
      const target = link.getAttribute('data-target');
      showSection(target);
    });
  });

  function showSection(id) {
    document.querySelectorAll('main > section').forEach(sec => {
      sec.classList.remove('active');
    });
    const section = document.getElementById(id);
    if(section) section.classList.add('active');
  }

  // Data layanan dan form sesuai permintaan
  const servicesData = {
    "konsultasi-teknis": {
      title: "Konsultasi Masalah Teknis Kendaraan",
      description: "Isi form berikut untuk konsultasi masalah teknis kendaraan Anda.",
      formHtml: `
        <label for="cust-name">Nama Lengkap:</label>
        <input type="text" id="cust-name" name="cust-name" required />

        <label for="cust-whatsapp">No Whatsapp untuk dihubungi:</label>
        <input type="text" id="cust-whatsapp" name="cust-whatsapp" placeholder="08123456789" required />

        <label for="car-year">Tahun Kendaraan:</label>
        <input type="number" id="car-year" name="car-year" min="1980" max="2030" required />

        <label for="car-type">Jenis Kendaraan:</label>
        <select id="car-type" name="car-type" required>
          <option value="" disabled selected>Pilih jenis kendaraan</option>
          <option value="Toyota">Toyota</option>
          <option value="Honda">Honda</option>
          <option value="MINI">MINI</option>
          <option value="BMW">BMW</option>
        </select>

        <label for="issue">Masalah yang ingin ditanyakan:</label>
        <textarea id="issue" name="issue" rows="5" required></textarea>

        <button type="submit">Kirim Permintaan Konsultasi</button>
      `
    },
    "estimasi-biaya": {
      title: "Estimasi Biaya Perbaikan dan Servis",
      description: "Isi form berikut untuk estimasi biaya penggantian komponen kendaraan Anda.",
      formHtml: `
        <label for="cust-name">Nama Lengkap:</label>
        <input type="text" id="cust-name" name="cust-name" required />

        <label for="cust-whatsapp">No Whatsapp untuk dihubungi:</label>
        <input type="text" id="cust-whatsapp" name="cust-whatsapp" placeholder="08123456789" required />

        <label for="car-year">Tahun Kendaraan:</label>
        <input type="number" id="car-year" name="car-year" min="1980" max="2030" required />

        <label for="car-type">Jenis Kendaraan:</label>
        <select id="car-type" name="car-type" required>
          <option value="" disabled selected>Pilih jenis kendaraan</option>
          <option value="Toyota">Toyota</option>
          <option value="Honda">Honda</option>
          <option value="MINI">MINI</option>
          <option value="BMW">BMW</option>
        </select>

        <label for="parts">Apa saja yang ingin diganti dalam kendaraan?</label>
        <textarea id="parts" name="parts" rows="5" required></textarea>

        <button type="submit">Kirim Permintaan Estimasi</button>
      `
    },
    "artikel-edukasi": {
      title: "Artikel Edukasi Otomotif Terbaru",
      description: "Baca artikel-artikel terbaru kami untuk menambah wawasan dan tips merawat kendaraan Anda.",
      formHtml: `<p>Silakan kunjungi bagian Artikel untuk membaca informasi lengkap.</p>`
    }
  };

  const serviceForm = document.getElementById('service-form');
  const serviceTitle = document.getElementById('service-title');
  const serviceDescription = document.getElementById('service-description');

  document.querySelectorAll('ul.services li').forEach(item => {
    item.addEventListener('click', () => {
      const key = item.getAttribute('data-service');
      const service = servicesData[key];
      if(service) {
        serviceTitle.textContent = service.title;
        serviceDescription.textContent = service.description;
        serviceForm.innerHTML = service.formHtml;
        showSection('service-detail');
        // Tambah event submit form dinamis
        serviceForm.onsubmit = function(e) {
          e.preventDefault();
          const formData = new FormData(serviceForm);
          let nama = formData.get('cust-name');
          alert(`Terima kasih, ${nama}! Permintaan Anda untuk layanan "${service.title}" telah kami terima.\nKami akan segera menghubungi Anda.`);
          serviceForm.reset();
          showSection('services');
        };
      }
    });
  });
</script>
</body>
</html>
