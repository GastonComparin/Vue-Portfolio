<template>
  <nav class="navbar sticky-top navbar-expand-lg bg-transparent">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">LOGO</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarText"
        aria-controls="navbarText"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Inicio</a>
          </li>
          <li class="nav-item">
            <a @click="scrollToProyectos" class="nav-link">Proyectos</a>
          </li>
          <li class="nav-item">
            <a @click="scrollToTecnologias" class="nav-link">Tecnologías</a>
          </li>

          <li class="nav-item">
            <a @click="scrollToContacto" class="nav-link">Contacto</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- !INICIO -->
  <div id="inicio" class="d-flex col-12 ms-md-5">
    <div class="card m-md-5 border-0">
      <img
        src="https://picsum.photos/id/120/600/800"
        class="card-img-top d-none d-md-block"
        alt="..."
      />
    </div>
    <div class="card bg-transparent">
      <div class="card-body" style="text-align: left">
        <div class="col-md-6 col-12">
          <h1 class="card-title" style="color: white">Gaston Comparin</h1>
          <h2 class="card-title" style="color: #ee6c4d">FullStack Developer</h2>
          <p class="card-text" style="color: white">
            Soy Gastón, una persona responsable, disciplinada y entusiasta que
            siempre busca nuevos desafíos en la programación.
          </p>
          <p class="card-text" style="color: white">
            Me aventuré en el emocionante camino del desarrollo FullStack, donde
            puedo combinar mi creatividad y habilidades técnicas para construir
            soluciones web impactantes.
          </p>
          <!-- !BOTON DE DESCARGA DE CV -->
          <a
            class="btn btn-primary"
            download="GastonComparin_CV.pdf"
            href="GastonComparin.pdf"
            >Descargar CV</a
          >
          <!-- ?GITHUB Y LENKEDIN -->
          <a
            class="git m-3"
            href="https://github.com/GastonComparin"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-github"
              width="32"
              height="32"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="white"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"
              />
            </svg>
          </a>
          <a
            class="lk"
            href="https://www.linkedin.com/in/gaston-comparin/"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-brand-linkedin"
              width="32"
              height="32"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="white"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none" />
              <path
                d="M4 4m0 2a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2z"
              />
              <path d="M8 11l0 5" />
              <path d="M8 8l0 .01" />
              <path d="M12 16l0 -5" />
              <path d="M16 16v-3a2 2 0 0 0 -4 0" />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- !PROYECTOS -->
  <h1 id="proyectos" class="titulos">Proyectos</h1>
  <h5>
    Si se puede <span style="color: #ee6c4d">imaginar</span>, se puede
    <span style="color: #ee6c4d">programar</span>
  </h5>
  <div class="d-flex justify-content-center">
    <div class="row col-md-8">
      <div class="col-md-4 mt-2">
        <div class="card card-hover">
          <div class="card">
            <img
              src="./assets/muscle.png"
              width="250"
              height="250"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body" style="height: 10.5rem">
              <h5 class="card-title">Muscle Lab</h5>
              <span class="badge">JavaScript</span>
              <span class="badge">CSS</span>
              <span class="badge">HTML</span>
              <span class="badge">Redux</span>
              <span class="badge">React</span>
              <span class="badge">SQL</span>
              <span class="badge">ExpressJS</span>
              <span class="badge">Postgres</span>
              <br />

              <a
                class="git m-3"
                href="https://github.com/GastonComparin/MuscleLab"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"
                  />
                </svg>
              </a>
              <a
                class="git m-3"
                href="https://muscle-lab-six.vercel.app"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M12 6h-6a2 2 0 0 0 -2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-6"
                  />
                  <path d="M11 13l9 -9" />
                  <path d="M15 4h5v5" />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-4 mt-2">
        <div class="card card-hover">
          <div class="card">
            <img
              src="./assets/gimlet.png"
              width="250"
              height="250"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body" style="height: 10.5rem">
              <h5 class="card-title">Gimlet Cocktail Club</h5>
              <span class="badge">JavaScript</span>
              <span class="badge">CSS</span>
              <span class="badge">HTML</span>
              <span class="badge">Vue</span>
              <span class="badge">Bootstrap</span>
              <br />

              <a
                class="git m-3"
                href="https://github.com/GastonComparin/GimletCocktailClub"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"
                  />
                </svg>
              </a>
              <a
                class="git m-3"
                href="https://gimletcocktailclub.com"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M12 6h-6a2 2 0 0 0 -2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-6"
                  />
                  <path d="M11 13l9 -9" />
                  <path d="M15 4h5v5" />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-4 mt-2">
        <div class="card card-hover">
          <div class="card">
            <img
              src="./assets/Garnish.png"
              width="250"
              height="250"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body" style="height: 10.5rem">
              <h5 class="card-title">The Garnish Bar</h5>
              <span class="badge">JavaScript</span>
              <span class="badge">CSS</span>
              <span class="badge">HTML</span>
              <span class="badge">Vite</span>
              <span class="badge">React</span>
              <span class="badge">Bootstrap</span>
              <br />

              <a
                class="git m-3"
                href="https://github.com/GastonComparin/TheGarnishBar"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5"
                  />
                </svg>
              </a>
              <a
                class="git m-3"
                href="https://the-garnish-bar.vercel.app"
                target="_blank"
                ><svg
                  style="margin-top: 1rem"
                  xmlns="http://www.w3.org/2000/svg"
                  class="icon icon-tabler icon-tabler-brand-github"
                  width="32"
                  height="32"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="black"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                  <path
                    d="M12 6h-6a2 2 0 0 0 -2 2v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-6"
                  />
                  <path d="M11 13l9 -9" />
                  <path d="M15 4h5v5" />
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--! TECNOLOGIAS -->
  <h1 id="tecnologias" class="titulos m-3">Tecnologías</h1>
  <div
    class="card bg-transparent col-8 mx-auto"
    style="border: 3px #ee6c4d solid; margin: 3rem"
  >
    <div class="card-body">
      <img class="tImg" src="./assets/js.png" alt="" />
      <img class="tImg" src="./assets/css-3.png" alt="" />
      <img class="tImg" src="./assets/html-5.png" alt="" />
      <img class="tImg" src="./assets/react.png" alt="" />
      <img class="tImg" src="./assets/redux.png" alt="" />
      <img class="tImg" src="./assets/vue.png" alt="" />
      <img class="tImg" src="./assets/nodejs.png" alt="" />
      <img class="tImg" src="./assets/expressjs.png" alt="" />
      <img class="tImg" src="./assets/sql.png" alt="" />
      <img class="tImg" src="./assets/postgre.png" alt="" />
      <img class="tImg" src="./assets/git.png" alt="" />
      <img class="tImg" src="./assets/bootstrap.png" alt="" />
    </div>
  </div>
  <!--! CONTACTO -->
  <h1 id="contacto" class="titulos m-3">Contáctame</h1>
  <div class="col-12 col-md-6 mx-auto d-flex justify-content-center">
    <div class="card bg-transparent" style="color: white">
      <div
        class="d-flex flex-column flex-md-row justify-content-center m-1 align-items-center"
      >
        <div class="m-1 text-center">
          <img width="36" src="./assets/gmail.png" alt="" />
          <p class="ms-3 m-3">gastoncomparin92@gmail.com</p>
        </div>
        <div class="m-1 text-center">
          <img width="36" src="./assets/whatsapp.png" alt="" />
          <p class="ms-3 m-3">+54 9 2613370889</p>
        </div>
      </div>
    </div>
  </div>
  <!-- !FOOTER -->
  <footer class="footer mt-5 py-3 bg-dark text-white bg-transparent"></footer>
</template>

<script>
import HomeView from "./views/HomeView.vue";
export default {
  methods: {
    scrollToProyectos() {
      const proyectos = document.querySelector("#proyectos");
      if (proyectos) {
        proyectos.scrollIntoView({
          behavior: "smooth",
          block: "start",
        });
      }
    },
    scrollToTecnologias() {
      const tecnologias = document.querySelector("#tecnologias");
      if (tecnologias) {
        tecnologias.scrollIntoView({
          behavior: "smooth",
          block: "start",
        });
      }
    },
    scrollToContacto() {
      const contacto = document.querySelector("#contacto");
      if (contacto) {
        contacto.scrollIntoView({
          behavior: "smooth",
          block: "start",
        });
      }
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-image: url("../src/assets/pxfuel.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: screen;
  overflow: hidden;
}
.btn {
  background-color: #ee6c4d;
  border-color: #ee6c4d;
  color: black;
  font-weight: 600;
}
.btn:hover {
  background-color: #ee6c4d;
  border-color: #ee6c4d;
}
.titulos {
  color: white;
  font-weight: 800;
}
.border-color {
  border-color: #ee6c4d;
}
.nav-link {
  color: white;
}
.nav-item {
  cursor: pointer;
}
.nav-link:hover {
  color: #ee6c4d;
}
.navbar-brand {
  color: #ee6c4d;
}
.card-hover {
  transition: transform 0.3s, box-shadow 0.3s, background-color 0.3s;
}
.card-hover:hover {
  background-color: #ee6c4d;
  transform: translateY(-5px);
  box-shadow: 0 4px 8px rgba(238, 108, 77, 0.8);
  background-color: rgba(238, 108, 77, 0.05);
}

.tImg {
  width: 8rem;
  margin: 0.5rem;
}
.tImg:hover {
  transition: transform 0.3s;
  transform: translateY(-5px);
}
.badge {
  margin: 0.2rem;
  background-color: gray;
}
.badge:hover {
  background-color: #ee6c4d;
}
</style>
