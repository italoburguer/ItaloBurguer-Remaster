<template>
  <div>
    <!-- ======= Top Bar ======= -->
    <div id="topbar" class="d-flex align-items-center fixed-top">
      <div class="container d-flex justify-content-center justify-content-md-between">
        <div class="contact-info d-flex align-items-center">
          <i class="bi bi-phone d-flex align-items-center"
            ><span>+57 310 444 55 66</span></i
          >
          <i class="bi bi-clock d-flex align-items-center ms-4"
            ><span> Martes a domingo: 3PM - 11PM </span></i >
        </div>

        <!-- <div class="languages d-none d-md-flex align-items-center">
        <ul>
          <li>En</li>         <li><a href="#">De</a></li>
        </ul>
      </div> -->
      </div>
    </div>

    <!-- ======= Header ======= -->
    <header id="header" class="fixed-top d-flex align-items-cente">
      <div
        class="
          container-fluid container-xl
          d-flex
          align-items-center
          justify-content-lg-between
        "
      >
        <h1 class="logo me-auto me-lg-0">
          <a>italoBurguer</a>
        </h1>
        

        <nav id="navbar" class="navbar order-last order-lg-0">
         <i class="bi bi-list mobile-nav-toggle"></i>
        </nav>
        <!-- .navbar -->
        <a class="book-a-table-btn scrollto d-none d-lg-flex" href="#hero">Home</a>
        <a class="book-a-table-btn scrollto d-none d-lg-flex" href="#about">About</a>
        <a class="book-a-table-btn scrollto d-none d-lg-flex" href="#chefs">Chefs</a>      
        <a href="#Login" class="book-a-table-btn scrollto d-none d-lg-flex">Login</a>
        <a href="#book-a-table" class="book-a-table-btn scrollto d-none d-lg-flex">Admin</a> 
        
         
      </div>
    </header>
    <!-- End Header -->

    <!-- ======= Hero Section ======= -->
    <section id="hero" class="d-flex align-items-center">
      <div
        class="container position-relative text-center text-lg-start"
        data-aos="zoom-in"
        data-aos-delay="100"
      >
        <div class="row">
          <div class="col-lg-8">
            <h1>Bienvenido a <span> Italo Burguer</span></h1>
            <h2>
              Seguimos entregando deliciosas hamburguesas de gran calidad!
            </h2>

            <div class="btns">
              <a href="#gallery" class="btn-menu animated fadeInUp scrollto"
                >Nuestros combos</a
              >
              <a href="#menu" class="btn-book animated fadeInUp scrollto"
                >A tu gusto</a
              >
            </div>
          </div>
          <div
            class="
              col-lg-4
              d-flex
              align-items-center
              justify-content-center
              position-relative
            "
            data-aos="zoom-in"
            data-aos-delay="200"
          >
            <a
              href="https://www.youtube.com/watch?v=ZRYyL72avdc"
              class="glightbox play-btn"
            ></a>
          </div>
        </div>
      </div>
    </section>
    <!-- End Hero -->

    <!-- ======= Gallery Section ======= -->
    <section id="gallery" class="gallery">
      <div class="container" data-aos="fade-up">
        <div class="section-title">
          <h2>Gallery</h2>
          <p>Super especiales de la casa</p>
        </div>
      </div>

      <div class="container-fluid" data-aos="fade-up" data-aos-delay="100">
        <div class="row g-0">
          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">

              <a href="@/assets/img/gallery/gallery-1.jpg" class="gallery-lightbox" data-gall="gallery-item">
                <img src="@/assets/img/gallery/gallery-1.jpg" alt="" class="img-fluid"/>             
                               
              </a>            


            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-2.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-2.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-3.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-3.jpg"
                  alt=""
                  class="img-fluid"
                />                
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-4.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-4.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-5.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-5.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-6.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-6.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-7.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-7.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>

          <div class="col-lg-3 col-md-4">
            <div class="gallery-item">
              <a
                href="@/assets/img/gallery/gallery-8.jpg"
                class="gallery-lightbox"
                data-gall="gallery-item"
              >
                <img
                  src="@/assets/img/gallery/gallery-8.jpg"
                  alt=""
                  class="img-fluid"
                />
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- End Gallery Section -->

    <main id="main">
      <!-- ======= Menu Section ======= -->
      <section id="menu" class="menu section-bg">
        <div class="container" data-aos="fade-up">
          <div class="section-title">
            <h2>Menu por ingredientes</h2>
            <p>Elija su opción</p>
          </div>

          <div class="row" data-aos="fade-up" data-aos-delay="100">
            <div class="col-lg-12 d-flex justify-content-center">
              <ul id="menu-flters">
                <li data-filter="*" class="filter-active">Meats</li>
                <li data-filter=".filter-starters">Vegetables</li>
                <li data-filter=".filter-salads">Features</li>
                <li data-filter=".filter-specialty">Drinks</li>
              </ul>
            </div>
          </div>

          <div
            class="row menu-container"
            data-aos="fade-up"
            data-aos-delay="200"
          >
            <div class="col-lg-6 menu-item filter-starters">
              <img
                src="@/assets/img/menu/lobster-bisque.jpg"
                class="menu-img"
                alt=""
              />
              <div class="menu-content">
                <a href="#">Baby beef</a><span>$5.95</span>
              </div>
              <div class="menu-ingredients">
                Lorem, deren, trataro, filede, nerada
              </div>
            </div>

            <div class="col-lg-6 menu-item filter-specialty">
              <img
                src="@/assets/img/menu/bread-barrel.jpg"
                class="menu-img"
                alt=""
              />
              <div class="menu-content">
                <a href="#">Calf meat</a><span>$6.95</span>
              </div>
              <div class="menu-ingredients">
                Lorem, deren, trataro, filede, nerada
              </div>
            </div>

            <div class="col-lg-6 menu-item filter-starters">
              <img src="@/assets/img/menu/cake.jpg" class="menu-img" alt="" />
              <div class="menu-content">
                <a href="#">grilled chicken</a><span>$7.95</span>
              </div>
              <div class="menu-ingredients">
                A delicate crab cake served on a toasted roll with lettuce and
                tartar sauce
              </div>
            </div>

            <div class="col-lg-6 menu-item filter-salads">
              <img src="@/assets/img/menu/caesar.jpg" class="menu-img" alt="" />
              <div class="menu-content">
                <a href="#">Pork rind</a><span>$8.95</span>
              </div>
              <div class="menu-ingredients">
                Lorem, deren, trataro, filede, nerada
              </div>
            </div>

            <div class="col-lg-6 menu-item filter-specialty">
              <img
                src="@/assets/img/menu/tuscan-grilled.jpg"
                class="menu-img"
                alt=""
              />
              <div class="menu-content">
                <a href="#">Breaded Chicken</a><span>$9.95</span>
              </div>
              <div class="menu-ingredients">
                Grilled chicken with provolone, artichoke hearts, and roasted
                red pesto
              </div>
            </div>

            <div class="col-lg-6 menu-item filter-starters">
              <img
                src="@/assets/img/menu/mozzarella.jpg"
                class="menu-img"
                alt=""
              />
              <div class="menu-content">
                <a href="#">Vegetariana</a><span>$4.95</span>
              </div>
              <div class="menu-ingredients">
                Lorem, deren, trataro, filede, nerada
              </div>
            </div>


          </div>
        </div>
      </section>
      <!-- End Menu Section -->

      <!-- ======= About Section ======= -->
      <section id="about" class="about">
        <div class="container" data-aos="fade-up">
          <div class="row">
            <div
              class="col-lg-6 order-1 order-lg-2"
              data-aos="zoom-in"
              data-aos-delay="100"
            >
              <div class="about-img">
                <img src="@/assets/img/about.jpg" alt="" />
              </div>
            </div>
            <div class="col-lg-6 pt-4 pt-lg-0 order-2 order-lg-1 content">
              <h3>NOSOTROS..</h3>
              <p class="fst-italic">
                Somos una pequeña familia quienes de manera artesanal,
                cultivamos gran parte de nuestros ingredientes sin químicos ni
                conservantes, nuestro pan esta hecho con sémola de gran calidad
                para deleite de su paladar.
              </p>
              <ul>
                <li>
                  <i class="bi bi-check-circle"></i> Ullamco laboris nisi ut
                  aliquip ex ea commodo consequat.
                </li>
                <li>
                  <i class="bi bi-check-circle"></i> Duis aute irure dolor in
                  reprehenderit in voluptate velit.
                </li>
                <li>
                  <i class="bi bi-check-circle"></i> Ullamco laboris nisi ut
                  aliquip ex ea commodo consequat. Duis aute irure dolor in
                  reprehenderit in voluptate trideta storacalaperda mastiro
                  dolore eu fugiat nulla pariatur.
                </li>
              </ul>
              <p>
                Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis
                aute irure dolor in reprehenderit in voluptate velit esse cillum
                dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                cupidatat non proident, sunt in culpa qui officia deserunt
                mollit anim id est laborum
              </p>
            </div>
          </div>
        </div>
      </section>
      <!-- End About Section -->

      <!-- ======= Chefs Section ======= -->
      <section id="chefs" class="chefs">
        <div class="container" data-aos="fade-up">
          <div class="section-title">
            <h2>Chefs</h2>
            <p>Our Proffesional Chefs</p>
          </div>

          <div class="row">
            <div class="col-lg-4 col-md-6">
              <div class="member" data-aos="zoom-in" data-aos-delay="100">
                <img
                  src="@/assets/img/chefs/chefs-1.jpg"
                  class="img-fluid"
                  alt=""
                />
                <div class="member-info">
                  <div class="member-info-content">
                    <h4>Italo Sahit</h4>
                    <span>Master Chef</span>
                  </div>
                  <div class="social">
                    <a href=""><i class="bi bi-twitter"></i></a>
                    <a href=""><i class="bi bi-facebook"></i></a>
                    <a href=""><i class="bi bi-instagram"></i></a>
                    <a href=""><i class="bi bi-linkedin"></i></a>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6">
              <div class="member" data-aos="zoom-in" data-aos-delay="200">
                <img
                  src="@/assets/img/chefs/chefs-2.jpg"
                  class="img-fluid"
                  alt=""
                />
                <div class="member-info">
                  <div class="member-info-content">
                    <h4>Ricardo Andres Bastidas</h4>
                    <span>Patissier</span>
                  </div>
                  <div class="social">
                    <a href=""><i class="bi bi-twitter"></i></a>
                    <a href=""><i class="bi bi-facebook"></i></a>
                    <a href=""><i class="bi bi-instagram"></i></a>
                    <a href=""><i class="bi bi-linkedin"></i></a>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-4 col-md-6">
              <div class="member" data-aos="zoom-in" data-aos-delay="300">
                <img
                  src="@/assets/img/chefs/chefs-3.jpg"
                  class="img-fluid"
                  alt=""
                />
                <div class="member-info">
                  <div class="member-info-content">
                    <h4>Milton Alberto Medina</h4>
                    <span>Cook</span>
                  </div>
                  <div class="social">
                    <a href=""><i class="bi bi-twitter"></i></a>
                    <a href=""><i class="bi bi-facebook"></i></a>
                    <a href=""><i class="bi bi-instagram"></i></a>
                    <a href=""><i class="bi bi-linkedin"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- End Chefs Section -->

      <!-- ======= Book A Table Section ======= -->
      <section id="book-a-table" class="book-a-table">
        <div class="container" data-aos="fade-up">
          <div class="section-title">
            <h2>Tu orden</h2>

            <p>Artículos</p>
          </div>

            <div id="app">
    <div id="nav">
      <router-link to="/productos">Productos</router-link>
    </div>
    <router-view/>
  </div>
          
        </div>
      </section>
      <!-- End Book A Table Section -->

      <!-- ======= Login Section ======= -->

      <section id="Login" class="Login">
        <div class="container" data-aos="fade-up">
          <div class="section-title">
            <h2>Iniciar sesión</h2>
            <p>Informacion</p>
          </div>

          <div class="login-box">
            <form>
              <!-- ADMIN INPUT -->
              <br>
              <label for="username">Administrador</label>
              <br>
              
              <label for="username">Correo electronico</label>
              <input type="text" placeholder="Ingrese su correo electronico" />
              <!-- PASSWORD INPUT -->
              <label for="password">Contraseña</label>
              <input type="password" placeholder="Ingrese su contraseña" />              
              <a href="index.html">Ingresar</a><br/>  
              <a href="#">Olvido su contraseña?</a><br/>  
                         
            </form>

            <form>
              <!-- REGISTRADO INPUT -->
              <br>
              <label for="username">Usuario registrado</label>
              <br>
              <br>
              <label for="username">Correo electronico</label>
              <input type="text" placeholder="Ingrese su correo electronico" />
              <!-- PASSWORD INPUT -->
              <label for="password">Contraseña</label>
              <input type="password" placeholder="Ingrese su contraseña" />
              <input type="submit" value="Log In" />
              <a href="#">Olvido su contraseña?</a><br />                          
            </form>
          
            <form>
               <!-- REGISTRASE INPUT -->
              <label for="username">Registrarse</label>
              <input type="text" placeholder="Ingrese su nombre completo" />
              <!-- USERNAME INPUT -->
              <label for="username">Correo electronico</label>
              <input type="text" placeholder="Ingrese su correo electronico" />
              <!-- PASSWORD INPUT -->
              <label for="password">Contraseña</label>
              <input type="password" placeholder="Ingrese su contraseña" />
              <input type="submit" value="Registrar" />            
              
            </form>
          </div>

        </div>
      </section>

      <!-- End Login Section -->
    </main>
    <!-- End #main -->

    <!-- ======= Footer ======= -->
    <footer id="footer">
      <div class="footer-top">
        <div class="container">
          <div class="row">
            <div class="col-lg-3 col-md-6">
              <div class="footer-info">
                <h3>Restaurantly</h3>
                <p>
                  A108 Adam Street <br />
                  NY 535022, USA<br /><br />
                  <strong>Phone:</strong> +1 5589 55488 55<br />
                  <strong>Email:</strong> info@example.com<br />
                </p>
                <div class="social-links mt-3">
                  <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
                  <a href="#" class="facebook"
                    ><i class="bx bxl-facebook"></i
                  ></a>
                  <a href="#" class="instagram"
                    ><i class="bx bxl-instagram"></i
                  ></a>
                  <a href="#" class="google-plus"
                    ><i class="bx bxl-skype"></i
                  ></a>
                  <a href="#" class="linkedin"
                    ><i class="bx bxl-linkedin"></i
                  ></a>
                </div>
              </div>
            </div>

            <div class="col-lg-2 col-md-6 footer-links">
              <h4>Useful Links</h4>
              <ul>
                <li>
                  <i class="bx bx-chevron-right"></i> <a href="#">Home</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i> <a href="#">About us</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i> <a href="#">Services</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i>
                  <a href="#">Terms of service</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i>
                  <a href="#">Privacy policy</a>
                </li>
              </ul>
            </div>

            <div class="col-lg-3 col-md-6 footer-links">
              <h4>Our Services</h4>
              <ul>
                <li>
                  <i class="bx bx-chevron-right"></i> <a href="#">Web Design</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i>
                  <a href="#">Web Development</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i>
                  <a href="#">Product Management</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i> <a href="#">Marketing</a>
                </li>
                <li>
                  <i class="bx bx-chevron-right"></i>
                  <a href="#">Graphic Design</a>
                </li>
              </ul>
            </div>

            <div class="col-lg-4 col-md-6 footer-newsletter">
              <h4>Our Newsletter</h4>
              <p>
                Tamen quem nulla quae legam multos aute sint culpa legam noster
                magna
              </p>
              <form action="" method="post">
                <input type="email" name="email" /><input
                  type="submit"
                  value="Subscribe"
                />
              </form>
            </div>
          </div>
        </div>
      </div>

      <div class="container">
        <div class="copyright">
          &copy; Copyright <strong><span>Restaurantly</span></strong
          >.
        </div>
        <div class="credits">
         <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/restaurantly-restaurant-template/ -->
          Designed by <a href="https://bootstrapmade.com/">bootstrapmade</a>
        </div>
      </div>
    </footer>
    <!-- End Footer -->
  </div>
</template>
<style scoped>
#hero {
  background: url("./assets/img/about-bg-ita.jpg") center center;
}
</style>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>


