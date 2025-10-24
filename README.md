<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman Home</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #aeceff; /* abu muda lembut */
            color: #333;
        }
        nav {
            background-color: #1e90ff; /* biru cerah */
            padding: 12px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 16px;
        }
        nav a:hover {
            color: #ffeb3b; /* kuning saat hover */
        }
        h1 {
            color: #0d47a1; /* biru gelap */
        }
        section {
            padding: 25px 40px;
            background-color: white;
            margin: 20px auto;
            max-width: 900px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(224, 214, 214, 0.1);
        }
        blockquote {
            background-color: #e3f2fd; /* biru muda lembut */
            border-left: 5px solid #1e90ff;
            padding: 10px 15px;
            font-style: italic;
        }
        img {
            margin-top: 10px;
            border-radius: 8px;
        }
    </style>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home DKV SMK N 2 Balikpapan</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #f9f9f9;
    }

    /* NAVBAR */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #111;
      color: white;
      padding: 10px 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    .logo-container {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo {
      width: 50px;
      height: 50px;
      border-radius: 50%;
    }

    .judul {
      font-weight: 600;
      font-size: 18px;
      letter-spacing: 1px;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 30px;
    }

    .nav-links a {
      text-decoration: none;
      color: white;
      transition: 0.3s;
    }

    .nav-links a:hover {
      color: #00bfff;
    }

    /* HERO SECTION */
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(to right, #00bfff, #4e54c8);
      color: white;
    }

    .hero h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.1em;
    }
  </style>
</head>
<body>
  <nav class="navbar">
    <div class="logo-container">
      <img src="logo dkv bulat.png" alt="Logo DKV" class="logo">
      <span class="judul">Desain Komunikasi Visual</span>
    </div>
    <ul class="nav-links">
      <li><a href="home2.html">Home</a></li>
      <li><a href="#profil">Profil</a></li>
      <li><a href="#galeri">Galeri</a></li>
      <li><a href="#kontak">Kontak</a></li>
    </ul>
  </nav>
</body>
</html>
    <section id="home">
        <h1>Anyeong Yareobun! Welcome To My Web</h1>
        <h2>Halo semuanya 👋</h2>
        <p>
            Perkenalkan, nama saya <b>Widi Anindya Ditias</b>  
            atau akrab dipanggil Widi.  
        </p>
        <p>
            Ini adalah <em>halaman Home sederhana</em> yang dibuat hanya dengan HTML.  
            Yuk, kita belajar web development dari dasar! 🚀
        </p>
        <hr>

        <!-- Contoh teks -->
        <h2>Contoh Teks</h2>
        <p>
            Ini contoh untuk tulisan <strong>TEBAL</strong>.  
            Kalau ini contoh buat tulisan <em>MIRING</em>.
        </p>

        <p>
            Contoh <cite>kutipan miring</cite>, 
            atau menggunakan <q>tanda petik</q>, dan juga kutipan panjang:
        </p>

        <blockquote>
            "HTML adalah bahasa markup standar untuk membuat halaman web."
        </blockquote>

        <p>
            Contoh <mark>teks yang disorot</mark>, 
            <small>teks kecil</small>, 
            <abbr title="HyperText Markup Language">HTML</abbr>
        </p>
        <hr>

        <!-- List -->
        <h2>Hal-hal Yang Saya Suka</h2>

        <h3>Minuman Favorit (Ordered List)</h3>
        <ol>
            <li>Kopi</li>
            <li>Matcha</li>
            <li>Nomor 1 & 2</li>
        </ol>

        <h3>Makanan Favorit (Unordered List)</h3>
        <ul>
            <li>Ayam Penyet Bu Ria</li>
            <li>Ayam Ganje Mas Indra</li>
            <li>Gacoan WKWK</li>
        </ul>

        <h3>Description List</h3>
        <dl>
            <dt>HTML</dt>
            <dd>Bahasa markup untuk membuat struktur web</dd>
            <dt>CSS</dt>
            <dd>Bahasa untuk mendesain tampilan web</dd>
        </dl>

        <h3>Nested List</h3>
        <ul>
            <li>Buah-buahan
                <ul>
                    <li>Apel</li>
                    <li>Pisang</li>
                    <li>Jeruk</li>
                </ul>
            </li>
            <li>Sayuran
                <ol>
                    <li>Bayam</li>
                    <li>Wortel</li>
                    <li>Kangkung</li>
                </ol>
            </li>
        </ul>
        <hr>

        <!-- Hyperlink & Gambar -->
        <h2>Hyperlink dan Gambar</h2>
        <p>
            Follow Instagram aku ya! hihi 
            <a href="https://www.instagram.com/aanindya.st?igsh=N3d6cWw3NWI3Mzh2" target="_blank">
                @aanindya.st
            </a>.
        </p>

        <p>Berikut contoh gambar:</p>
        <img src="logo dkv bulat.png" alt="Logo DKV" width="200">

        <p>
            Halaman Web <b>Widi Anindya Ditias</b> &copy; 2025.
        </p>

