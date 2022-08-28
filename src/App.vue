<template>
  <nav>
    <div class="logo"></div>
    <div class="links">
      <a>Accueil</a>
      <a>Outils</a>
      <a>Projets</a>
      <div class="mail-btn"></div>
    </div>
  </nav>
  <main>
    <section class="home">
      <h1>Salut! <br> Moi c'est <b>Aigle Noir</b>.</h1>
      <p>Sur ce site, vous retrouverez plusieurs informations à mon propos,<br>
        je vous souhaite la bienvenue dans mon univers!</p>
      <button>En savoir plus</button>
    </section>
    <section class="tools">
      <div class="arrow"></div>
      <div class="title">
        <h3>Mes outils de travail</h3>
        <p>Les logiciels que j'utilise quotidiennement<br>
          pour exercer ma passion.</p>
      </div>
      <div class="card">
        <div class="el">
          <img src="./assets/images/photoshop.svg" alt="Adobe Photoshop">
          <h5>Adobe Phosohop</h5>
          <p>Design Varié</p>
        </div>
        <div class="el">
          <img src="./assets/images/illustrator.svg" alt="Adobe Illustrator">
          <h5>Adobe Illustrator</h5>
          <p>Design de Logos</p>
        </div>
        <div class="el">
          <img src="./assets/images/xd.svg" alt="Adobe XD">
          <h5>Adobe XD</h5>
          <p>Design Web</p>
        </div>
      </div>
    </section>
  </main>
  <footer></footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');

body {
  margin: 0;
  font-family: 'Rubik', sans-serif;
}

::-webkit-scrollbar {
  width: 0;
}
</style>

<style scoped lang="scss">
@import './assets/style/style.scss';
</style>
