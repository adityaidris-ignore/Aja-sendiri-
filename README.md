
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Anime Profile</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background: #101010;
  color: white;
  font-family: Arial, sans-serif;
}

header {
  text-align: center;
  padding: 35px 15px;
  background: #1b1b1b;
  border-bottom: 2px solid #555;
}

header h1 {
  color: #ccc;
  font-size: 30px;
}

header p {
  color: #aaa;
  margin-top: 10px;
}

.container {
  max-width: 900px;
  margin: auto;
  padding: 20px;
}

.card {
  background: #1b1b1b;
  border: 1px solid #383838;
  border-radius: 15px;
  padding: 20px;
  margin-bottom: 20px;
  text-align: center;
}

h2 {
  color: #ddd;
  margin-bottom: 15px;
}

p {
  color: #bbb;
  line-height: 1.7;
}

img {
  max-width: 100%;
  object-fit: cover;
  border-radius: 12px;
}

.profile-img {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  border: 3px solid #777;
  margin-bottom: 15px;
}

.waifu-img {
  width: 100%;
  max-width: 350px;
  max-height: 400px;
  margin-bottom: 15px;
}

.hero-img {
  width: 100%;
  max-width: 350px;
  margin-bottom: 15px;
}

audio {
  width: 100%;
  margin-top: 15px;
}

button {
  background: #444;
  color: white;
  border: 1px solid #777;
  padding: 12px 22px;
  border-radius: 8px;
  cursor: pointer;
  margin-top: 15px;
}

button:hover {
  background: #666;
}

footer {
  text-align: center;
  padding: 25px;
  color: #777;
}
</style>
</head>

<body>

<header>
  <h1>MY PERSONAL WEBSITE</h1>
  <p>Welcome to my anime world</p>
</header>

<div class="container">

  <!-- DATA DIRI -->
  <section class="card">
    <h2>About Me</h2>

    <img src="yinix.jpg"
         alt="Foto saya"
         class="profile-img">

    <p>Nama: Aditya idris</p>
    <p>Umur: 17 tahun</p>
    <p>Hobi: Gaming, Anime, dan Musik</p>
    <p>Game Favorit: Mobile Legends</p>
    <p>Waifu: Sistine Fibel</p>
  </section>

  <!-- WAIFU -->
  <section class="card">
    <h2>My Waifu</h2>

    <img src="waifu gua.jpg"
         alt="Foto waifu"
         class="waifu-img">

    <h3>Sistine Fibel</h3>
    <p>My favorite anime character ❤️</p>
  </section>

  <!-- MUSIK -->
  <section class="card">
    <h2>one direction 18</h2>

    <p>Dengarkan lagu favoritku di sini 🎵</p>

    <audio controls loop>
      <source src="18.mp3" type="audio/mpeg">
      Browser kamu tidak mendukung audio.
    </audio>
  </section>

  <!-- MOBILE LEGENDS -->
  <section class="card">
    <h2>Mobile Legends</h2>

    <img src="sun.jpg"
         alt="Hero Mobile Legends favorit"
         class="hero-img">

    <h3>Hero Favorit: Sun</h3>

    <p>
      Game favoritku adalah Mobile Legends.
      Aku suka bermain bersama teman dan
      menggunakan hero favoritku.
    </p>
  </section>

<!-- VIDEO MP4 -->
<section class="card">
  <h2>My hero mlbb</h2>

  <video controls width="100%" 
         style="max-width:500px; border-radius:12px;">
    <source src="sun starlight.mp4" type="video/mp4">
    Browser kamu tidak mendukung video.
  </video>

</section>

</div>

<footer>
  <p>© 2026 My Personal Website</p>
  <p>Made with ❤️ by Nama Kamu</p>
</footer>

</body>
</html>
