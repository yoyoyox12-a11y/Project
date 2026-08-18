<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Ofertas USA 🇺🇸 | Productos Importados</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background: #f5f7fb;
      color: #1d2433;
    }

    /* HEADER */
    header {
      background: linear-gradient(135deg, #071a3d, #123d82);
      color: white;
      padding: 18px 6%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 3px 15px rgba(0,0,0,.15);
    }

    .logo {
      font-size: 27px;
      font-weight: 900;
      white-space: nowrap;
    }

    .logo span {
      color: #ffcc00;
    }

    .search {
      width: 45%;
      position: relative;
    }

    .search input {
      width: 100%;
      padding: 13px 18px;
      border: none;
      border-radius: 30px;
      outline: none;
      font-size: 15px;
    }

    .cart {
      font-size: 25px;
    }

    /* HERO */
    .hero {
      min-height: 430px;
      display: flex;
      align-items: center;
      padding: 60px 7%;
      color: white;
      background:
        linear-gradient(90deg, rgba(3,15,40,.95), rgba(3,15,40,.45)),
        linear-gradient(135deg, #09285e, #e63946);
    }

    .hero-content {
      max-width: 650px;
    }

    .badge {
      display: inline-block;
      background: #ffcc00;
      color: #111;
      padding: 8px 15px;
      border-radius: 30px;
      font-weight: bold;
      margin-bottom: 18px;
    }

    .hero h1 {
      font-size: clamp(40px, 6vw, 70px);
      line-height: 1;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #ffcc00;
    }

    .hero p {
      font-size: 20px;
      line-height: 1.6;
      margin-bottom: 30px;
    }

    .hero-btn {
      display: inline-block;
      padding: 15px 28px;
      background: #e63946;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: .2s;
    }

    .hero-btn:hover {
      background: #ff4d5a;
      transform: translateY(-2px);
    }

    /* CATEGORIES */
    .section {
      padding: 55px 6%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 30px;
    }

    .section-title h2 {
      font-size: 34px;
      margin-bottom: 8px;
    }

    .section-title p {
      color: #687386;
    }

    .categories {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
      gap: 15px;
    }

    .category {
      background: white;
      padding: 22px 10px;
      border-radius: 16px;
      text-align: center;
      cursor: pointer;
      border: 1px solid #e5e8ef;
      transition: .2s;
    }

    .category:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,.08);
      border-color: #123d82;
    }

    .category-icon {
      font-size: 35px;
      margin-bottom: 10px;
    }

    .category strong {
      display: block;
    }

    /* PRODUCTS */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
      gap: 22px;
    }

    .product {
      background: white;
      border-radius: 18px;
      overflow: hidden;
      border: 1px solid #e7eaf0;
      box-shadow: 0 5px 15px rgba(0,0,0,.04);
      transition: .25s;
    }

    .product:hover {
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(0,0,0,.12);
    }

    .product-image {
      height: 220px;
      background: #eef1f6;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 75px;
    }

    .product-info {
      padding: 18px;
    }

    .store {
      font-size: 12px;
      font-weight: bold;
      color: #777;
      margin-bottom: 8px;
    }

    .product h3 {
      font-size: 18px;
      margin-bottom: 9px;
    }

    .product p {
      color: #737b8c;
      font-size: 14px;
      line-height: 1.5;
      min-height: 42px;
    }

    .stars {
      color: #ffb400;
      margin: 12px 0;
    }

    .product-btn {
      width: 100%;
      border: none;
      background: #123d82;
      color: white;
      padding: 13px;
      border-radius: 10px;
      cursor: pointer;
      font-weight: bold;
      font-size: 15px;
      transition: .2s;
    }

    .product-btn:hover {
      background: #e63946;
    }

    /* TRUST */
    .trust {
      background: #071a3d;
      color: white;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      padding: 40px 6%;
      text-align: center;
    }

    .trust-item {
      padding: 10px;
    }

    .trust-item div {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .trust-item p {
      color: #d9e1f2;
      margin-top: 5px;
      font-size: 14px;
    }

    /* NEWSLETTER */
    .newsletter {
      padding: 55px 6%;
      background: #fff;
      text-align: center;
    }

    .newsletter h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    .newsletter p {
      color: #697386;
      margin-bottom: 22px;
    }

    .newsletter-form {
      display: flex;
      max-width: 550px;
      margin: auto;
      gap: 10px;
    }

    .newsletter-form input {
      flex: 1;
      padding: 14px 18px;
      border: 1px solid #d9deea;
      border-radius: 10px;
      outline: none;
    }

    .newsletter-form button {
      border: none;
      background: #e63946;
      color: white;
      padding: 0 22px;
      border-radius: 10px;
      font-weight: bold;
      cursor: pointer;
    }

    /* FOOTER */
    footer {
      background: #030b1b;
      color: white;
      text-align: center;
      padding: 30px 6%;
    }

    footer p {
      color: #aab4c8;
      font-size: 14px;
      margin-top: 8px;
    }

    /* WHATSAPP */
    .whatsapp {
      position: fixed;
      right: 20px;
      bottom: 20px;
      width: 58px;
      height: 58px;
      border-radius: 50%;
      background: #25d366;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 29px;
      text-decoration: none;
      box-shadow: 0 5px 20px rgba(0,0,0,.25);
      z-index: 200;
    }

    /* MOBILE */
    @media (max-width: 700px) {
      header {
        flex-wrap: wrap;
      }

      .search {
        order: 3;
        width: 100%;
      }

      .hero {
        min-height: 400px;
        padding: 45px 6%;
      }

      .hero h1 {
        font-size: 45px;
      }

      .hero p {
        font-size: 17px;
      }

      .newsletter-form {
        flex-direction: column;
      }

      .newsletter-form button {
        padding: 14px;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo">OFERTAS <span>USA 🇺🇸</span></div>

    <div class="search">
      <input
        type="text"
        id="searchInput"
        placeholder="¿Qué estás buscando?"
        onkeyup="searchProducts()"
      >
    </div>

    <div class="cart">🛍️</div>
  </header>


  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">

      <div class="badge">🔥 PRODUCTOS IMPORTADOS</div>

      <h1>
        Encuentra tus
        <span>favoritos</span>
      </h1>

      <p>
        Descubre productos seleccionados de Estados Unidos,
        grandes oportunidades y novedades para toda la familia.
      </p>

      <a href="#productos" class="hero-btn">
        VER PRODUCTOS →
      </a>

    </div>
  </section>


  <!-- CATEGORÍAS -->
  <section class="section">

    <div class="section-title">
      <h2>Explora por categoría</h2>
      <p>Encuentra rápidamente lo que estás buscando.</p>
    </div>

    <div class="categories">

      <div class="category">
        <div class="category-icon">📱</div>
        <strong>Electrónica</strong>
      </div>

      <div class="category">
        <div class="category-icon">🏠</div>
        <strong>Hogar</strong>
      </div>

      <div class="category">
        <div class="category-icon">👗</div>
        <strong>Moda</strong>
      </div>

      <div class="category">
        <div class="category-icon">💄</div>
        <strong>Belleza</strong>
      </div>

      <div class="category">
        <div class="category-icon">🚗</div>
        <strong>Automóvil</strong>
      </div>

      <div class="category">
        <div class="category-icon">🎮</div>
        <strong>Entretenimiento</strong>
      </div>

      <div class="category">
        <div class="category-icon">🎁</div>
        <strong>Regalos</strong>
      </div>

    </div>
  </section>


  <!-- PRODUCTOS -->
  <section class="section" id="productos">

    <div class="section-title">
      <h2>🔥 Productos destacados</h2>
      <p>Productos seleccionados para ti.</p>
    </div>

    <div class="products" id="productGrid">

      <!-- PRODUCTO 1 -->
      <div class="product" data-name="Auriculares inalámbricos">
        <div class="product-image">🎧</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Auriculares inalámbricos</h3>

          <p>
            Disfruta de tu música y llamadas con un diseño moderno.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.amazon.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>


      <!-- PRODUCTO 2 -->
      <div class="product" data-name="Accesorios para celular">
        <div class="product-image">📱</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Accesorios para celular</h3>

          <p>
            Accesorios prácticos para complementar tu dispositivo.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.amazon.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>


      <!-- PRODUCTO 3 -->
      <div class="product" data-name="Organizador para hogar">
        <div class="product-image">🏠</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Organizador para hogar</h3>

          <p>
            Una solución práctica para mantener tus espacios organizados.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.walmart.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>


      <!-- PRODUCTO 4 -->
      <div class="product" data-name="Accesorios para automóvil">
        <div class="product-image">🚗</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Accesorios para automóvil</h3>

          <p>
            Productos prácticos para tu vehículo y viajes.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.walmart.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>


      <!-- PRODUCTO 5 -->
      <div class="product" data-name="Artículos de belleza">
        <div class="product-image">💄</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Artículos de belleza</h3>

          <p>
            Productos y accesorios seleccionados para tu rutina.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.amazon.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>


      <!-- PRODUCTO 6 -->
      <div class="product" data-name="Regalos y novedades">
        <div class="product-image">🎁</div>

        <div class="product-info">
          <div class="store">🇺🇸 PRODUCTO IMPORTADO</div>

          <h3>Regalos y novedades</h3>

          <p>
            Encuentra ideas originales para sorprender a alguien especial.
          </p>

          <div class="stars">★★★★★</div>

          <button
            class="product-btn"
            onclick="openProduct('https://www.amazon.com/')"
          >
            VER PRODUCTO →
          </button>
        </div>
      </div>

    </div>
  </section>


  <!-- CONFIANZA -->
  <section class="trust">

    <div class="trust-item">
      <div>🇺🇸</div>
      <strong>Productos importados</strong>
      <p>Selección de productos de EE. UU.</p>
    </div>

    <div class="trust-item">
      <div>🔥</div>
      <strong>Ofertas seleccionadas</strong>
      <p>Encuentra productos interesantes.</p>
    </div>

    <div class="trust-item">
      <div>📱</div>
      <strong>Compra fácilmente</strong>
      <p>Accede al producto desde tu celular.</p>
    </div>

    <div class="trust-item">
      <div>⭐</div>
      <strong>Productos destacados</strong>
      <p>Selecciones para diferentes necesidades.</p>
    </div>

  </section>


  <!-- NEWSLETTER -->
  <section class="newsletter">

    <h2>🔥 No te pierdas las novedades</h2>

    <p>
      Déjanos tu correo para recibir nuevas ofertas y productos destacados.
    </p>

    <form class="newsletter-form" onsubmit="subscribe(event)">
      <input
        type="email"
        id="email"
        placeholder="Tu correo electrónico"
        required
      >

      <button type="submit">
        SUSCRIBIRME
      </button>
    </form>

  </section>


  <!-- FOOTER -->
  <footer>

    <h3>OFERTAS USA 🇺🇸</h3>

    <p>
      Productos importados y oportunidades seleccionadas.
    </p>

    <p>
      © 2026 Ofertas USA. Todos los derechos reservados.
    </p>

  </footer>


  <!-- WHATSAPP -->
  <a
    class="whatsapp"
    href="https://wa.me/"
    target="_blank"
    aria-label="WhatsApp"
  >
    ☎
  </a>


  <script>

    function openProduct(url) {
      window.open(url, "_blank");
    }


    function searchProducts() {

      const search =
        document
          .getElementById("searchInput")
          .value
          .toLowerCase();

      const products =
        document.querySelectorAll(".product");

      products.forEach(product => {

        const name =
          product.dataset.name.toLowerCase();

        if (name.includes(search)) {
          product.style.display = "";
        } else {
          product.style.display = "none";
        }

      });
    }


    function subscribe(event) {

      event.preventDefault();

      const email =
        document.getElementById("email").value;

      alert(
        "¡Gracias! " +
        email +
        " ha sido registrado."
      );

      document.getElementById("email").value = "";

    }

  </script>

</body>
</html>
