
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Pribadi Anime</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: #101010;
  color: white;
  font-family: Arial, sans-serif;
}

header {
  background: #202020;
  padding: 20px;
  text-align: center;
  border-bottom: 2px solid #555;
}

header h1 {
  color: #aaa;
  margin: 0;
}

nav {
  text-align: center;
  padding: 15px;
  background: #181818;
}

nav a {
  color: white;
  margin: 10px;
  text-decoration: none;
}

.container {
  max-width: 900px;
  margin: auto;
  padding: 20px;
}

.card {
  background: #1c1c1c;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 12px;
  border: 1px solid #383838;
}

h2 {
  color: #ccc;
  border-bottom: 1px solid #444;
  padding-bottom: 10px;
}

img, video {
  width: 100%;
  border-radius: 10px;
}

.hero {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
}

.song {
  background: #292929;
  padding: 12px;
  margin: 10px 0;
  border-radius: 8px;
}

button {
  background: #555;
  color: white;
  border: none;
  padding: 10px 15px;
  border-radius: 8px;
  cursor: pointer;
}

button:hover {
  background: #777;
}

footer {
  text-align: center;
  padding: 20px;
  color: #888;
}

@media(max-width:600px) {
  .hero {
    grid-template-columns: 1fr;
  }
}
</style>
</head>

<body>

<header>
  <h1>MY WEBSITE</h1>
  <p>Welcome to my personal website</p>
</header>

<nav>
  <a href="#profil">Profil</a>
  <a href="#musik">Musik</a>
  <a href="#waifu">Waifu</a>
  <a href="#game">Game</a>
</nav>

<div class="container">

  <!-- PROFIL -->
  <section class="card" id="profil">
    <h2>👤 Tentang Saya</h2>

    <img src="yinix.jpg"
         alt="Foto saya"
         style="max-width:200px">

    <p>Nama: Aditya idris</p>
    <p>Hobi: Anime, Gaming, dan Musik</p>
    <p>Game Favorit: Mobile Legends</p>
  </section>

  <!-- VIDEO OTOMATIS -->
  <section class="card">
    <h2>🎬 Video Favorit</h2>

    <video autoplay muted loop playsinline controls>
      <source src="sun starlight.mp4" type="video/mp4">
      Browser tidak mendukung video.
    </video>

    <p>Video akan diputar otomatis tanpa suara.</p>
  </section>

  <!-- MUSIK -->
  <section class="card" id="musik">
    <h2>🎵 Music Player</h2>

    <p>♫ Pilih lagu favoritmu</p>

    <div class="song">
      <p>🎵 Lagu 1 - one direction 18</p>
      <button onclick="playSong(0)">▶ Putar</button>
    </div>

    <div class="song">
      <p>🎵 Lagu 2 - my sweetie</p>
      <button onclick="playSong(1)">▶ Putar</button>
    </div>

    <div class="song">
      <p>🎵 Lagu 3 - beauty and a beat</p>
      <button onclick="playSong(2)">▶ Putar</button>
    </div>

    <div class="song">
      <p>🎵 Lagu 4 - as it was</p>
      <button onclick="playSong(3)">▶ Putar</button>
    </div>

    <div class="song">
      <p>🎵 Lagu 5 - payphone</p>
      <button onclick="playSong(4)">▶ Putar</button>
    </div>

    <audio id="music" controls style="width:100%"></audio>

    <p id="status">Belum ada lagu yang diputar.</p>
  </section>

  <!-- WAIFU -->
  <section class="card" id="waifu">
    <h2>💖 My Waifu</h2>

    <img src="waifu gua.jpg" alt="Foto waifu">

    <p>Waifu favoritku adalah karakter anime yang gua sukai karena dia tsundere,imut dan perhatian.</p>
  </section>

  <!-- GAME -->
  <section class="card" id="888">
    <h2>🎮 Mobile Legends</h2>

    <p>Game favorit dan hero andalanku.</p>

    <div class="hero">

      <div>
        <img src="sun.jpg" alt="Hero favorit">
        <h3>Hero Favorit 1</h3>
      </div>

    </div>
  </section>

</div>

<footer>
  <p>© 2026 My Anime Website</p>
</footer>

<script>
const songs = [
  "18.mp3",
  "my sweetie.mp3",
  "beauty and a beat.mp3",
  "as it was.mp3",
  "payphone.mp3"
];

const music = document.getElementById("music");
const status = document.getElementById("status");

function playSong(index) {
  music.src = songs[index];
  music.play();

  status.textContent =
    "Sedang memutar Lagu " + (index + 1);
}
</script>

</body>
</html>
