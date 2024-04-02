<template>

  <div class="portfolio">
    <header>
      <h1>My Portfolio</h1>
      <nav>
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Hobby</a></li> <!-- Perbaikan: "Hobby" huruf pertama menjadi kapital -->
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <img src="./assets/IMG_20230128_212308.jpg" width="400" height="300">
    <main>
      <section class="about">
        <h2>BIODATA SAYA</h2>
        <p>Perkenalkan nama saya FEBY NURHAZIZAH, saya berasal dari rokan hulu, tanggal lahir 02 februari 2003, status sebagai mahasiswa semester 4 di universitas islam riau, jurusan teknik informatika..</p>
      </section>
      <section class="projects">
        <div class="project">
          <h3>HOBBY</h3>
          <p>MEMBACA DAN MEMASAK</p>
        </div>
        <div class="project">
          <h3>PENGALAMAN</h3>
          <p>pengalaman saya selama kuliah saat ini saya pernah mengikuti salah satu program MBKM pada semester 3 yaitu program pertukaran mahasiswa di pulau sulawesi selatan yaitu di universitas dipa makassar, dan dari program tersebut saya dapat mengenal budaya yang ada disana dan saya dapat mengenal teman-teman dari berbagai pulau yang ada di Indonesia, selain itu juga saya dapat belajar di kampus lain. SEKIAN DAN TERIMAKASIH</p>
        </div>
      </section>
      <section class="contact">
        <h2>Contact Me</h2>
        <p>Email: febbynurhazizah@gmail.com</p>
        <p>Phone: 0812-7665-6817</p>
      </section>
    </main>
    <footer>
      <p>&copy; 2024 My Portfolio</p>
    </footer>
  </div>
</template>

<style scoped>
/* Styling for your portfolio */
.portfolio {
  font-family: Arial, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background: linear-gradient(to bottom right, #FFC0CB, #ADD8E6); /* Gradient merah muda ke biru */
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #ff0000; /* Warna merah */
}

main {
  margin-top: 20px;
}

section {
  margin-bottom: 40px;
}

footer {
  margin-top: 40px;
  text-align: center;
  color: #777;
}
</style>
