# Ipa-uas<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Materi IPA SMP</title>
  <style>
    :root{
      --bg:#f5f5f5;
      --card:#ffffff;
      --text:#222;
      --primary:#2c7be5;
    }

    body.dark{
      --bg:#121212;
      --card:#1e1e1e;
      --text:#eaeaea;
      --primary:#6ea8ff;
    }

    body {
      font-family: Arial;
      margin:0;
      background:var(--bg);
      color:var(--text);
      transition:0.3s;
    }

    header {
      background:var(--primary);
      color:white;
      padding:20px;
      text-align:center;
    }

    nav {
      position:sticky;
      top:0;
      background:var(--card);
      padding:10px;
      display:flex;
      gap:10px;
      overflow-x:auto;
      box-shadow:0 2px 5px rgba(0,0,0,0.1);
    }

    nav a {
      text-decoration:none;
      color:var(--primary);
      font-weight:bold;
      white-space:nowrap;
    }

    .toggle {
      margin-left:auto;
      cursor:pointer;
      background:var(--primary);
      color:white;
      border:none;
      padding:5px 10px;
      border-radius:5px;
    }

    section {
      background:var(--card);
      margin:15px;
      padding:15px;
      border-radius:10px;
      box-shadow:0 2px 5px rgba(0,0,0,0.1);
    }

    h2 { color:var(--primary); }
  </style>
</head>
<body>

<header>
  <h1>Ringkasan Materi IPA SMP</h1>
</header>

<nav>
  <a href="#besaran">Besaran</a>
  <a href="#gaya">Gaya</a>
  <a href="#energi">Energi</a>
  <a href="#zat">Zat</a>
  <a href="#kalor">Kalor</a>
  <a href="#cahaya">Cahaya</a>
  <a href="#tekanan">Tekanan</a>
  <a href="#listrik">Listrik</a>
  <a href="#makhluk">Makhluk Hidup</a>
  <a href="#astro">Astronomi</a>
  <button class="toggle" onclick="toggleDark()">🌙</button>
</nav>

<section id="besaran">
  <h2>Ukuran & Besaran</h2>
  <p>Besaran adalah sesuatu yang dapat diukur.</p>
</section>

<section id="gaya">
  <h2>Gaya & Gerak</h2>
  <p>Gaya adalah tarikan/dorongan.</p>
</section>

<section id="energi">
  <h2>Energi & Usaha</h2>
  <p>Energi adalah kemampuan melakukan usaha.</p>
</section>

<section id="zat">
  <h2>Zat & Perubahannya</h2>
  <p>Zat bisa padat, cair, gas.</p>
</section>

<section id="kalor">
  <h2>Kalor & Pemuaian</h2>
  <p>Kalor adalah energi panas.</p>
</section>

<section id="cahaya">
  <h2>Cahaya (Optik)</h2>
  <p>Cahaya merambat lurus.</p>
</section>

<section id="tekanan">
  <h2>Tekanan & Fluida</h2>
  <p>Tekanan = gaya / luas.</p>
</section>

<section id="listrik">
  <h2>Listrik & Magnet</h2>
  <p>Listrik adalah aliran muatan.</p>
</section>

<section id="makhluk">
  <h2>Makhluk Hidup</h2>
  <p>Bernapas, tumbuh, berkembang biak.</p>
</section>

<section id="astro">
  <h2>Astronomi</h2>
  <p>Mempelajari benda langit.</p>
</section>

<script>
function toggleDark(){
  document.body.classList.toggle("dark");
}
</script>

</body>
</html>
