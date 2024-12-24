<template>
  <link rel="stylesheet" href="style.css">
  <header class="header">
    <div class="logo">
      <img src="~/assets/img/jabar.png" alt="Logo 1">
      <img src="~/assets/img/disdik.png" alt="Logo 2">
      <img src="~/assets/img/smk.png" alt="Logo 3">
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#profil">Profil</a></li>
        <li><a href="#kompetensi">Kompetensi Keahlian</a></li>
        <li><a href="#galeri">Galeri</a></li>
      </ul>
    </nav>
    <div class="search">
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001q.044.06.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1 1 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0"/>
      </svg>
    </div>
  </header>
</template>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #608BC1;
  padding: 10px 20px;
  color: white;
}

.header .logo img {
  height: 50px;
  margin-right: 10px;
}
.header .logo{
  margin-left: 150px;
}

nav ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

.search {
  margin-right: 150px;
}

</style>