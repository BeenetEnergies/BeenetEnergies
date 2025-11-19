<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Beenet Energies — Proyecto</title>
  <meta name="description" content="Beenet Energies - soluciones de eficiencia energética para hogares. Proyecto académico.">

  <!-- Tailwind CDN (rápido para prototipos) -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">

  <!-- favicon (opcional) -->
  <link rel="icon" href="assets/img/logo.png">

  <!-- estilos propios -->
  <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-50 text-gray-800 antialiased">

  <!-- NAV -->
  <header class="bg-white/70 backdrop-blur sticky top-0 z-50 border-b">
    <div class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <img src="assets/img/logo.png" alt="Beenet logo" class="h-10 w-10 object-cover rounded-md hidden sm:block">
        <a href="#inicio" class="font-bold text-lg">Beenet Energies</a>
      </div>

      <nav class="hidden md:flex items-center gap-6">
        <a href="#inicio" class="nav-link">Inicio</a>
        <a href="#quienes" class="nav-link">Quiénes somos</a>
        <a href="#vision" class="nav-link">Visión & Misión</a>
        <a href="#servicios" class="nav-link">Soluciones</a>
        <a href="#campañas" class="nav-link">Campañas</a>
        <a href="#beneficios" class="nav-link">Beneficios</a>
        <a href="#colab" class="nav-link">Colaboraciones</a>
        <a href="#contacto" class="nav-link btn-primary">Contacto</a>
      </nav>

      <!-- boton mobile -->
      <button id="btnMenu" aria-label="Abrir menú" class="md:hidden p-2 rounded-md border">
        <svg id="iconMenu" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8h16M4 16h16" />
        </svg>
      </button>
    </div>

    <!-- mobile menu -->
    <div id="mobileMenu" class="md:hidden hidden border-t">
      <div class="px-6 py-4 flex flex-col gap-3">
        <a href="#inicio" class="nav-link">Inicio</a>
        <a href="#quienes" class="nav-link">Quiénes somos</a>
        <a href="#vision" class="nav-link">Visión & Misión</a>
        <a href="#servicios" class="nav-link">Soluciones</a>
        <a href="#campañas" class="nav-link">Campañas</a>
        <a href="#beneficios" class="nav-link">Beneficios</a>
        <a href="#colab" class="nav-link">Colaboraciones</a>
        <a href="#contacto" class="nav-link btn-primary">Contacto</a>
      </div>
    </div>
  </header>

  <!-- HERO -->
  <main>
    <section id="inicio" class="min-h-[70vh] flex items-center">
      <div class="max-w-6xl mx-auto px-6 py-16 grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
        <div data-aos="fade-right">
          <h1 class="text-4xl sm:text-5xl font-extrabold leading-tight mb-4">Beenet Energies</h1>
          <p class="text-lg mb-6">Soluciones accesibles y responsables para el ahorro y la eficiencia energética en hogares y pequeñas comunidades.</p>
          <div class="flex gap-4">
            <a href="#servicios" class="inline-block px-5 py-3 rounded-lg border btn-primary">Nuestras soluciones</a>
            <a href="#campañas" class="inline-block px-5 py-3 rounded-lg border">Campañas</a>
          </div>
        </div>

        <div data-aos="fade-left" class="flex justify-center">
          <div id="card" class="p-6 rounded-2xl shadow-2xl bg-white w-full max-w-md">
            <h3 class="font-semibold mb-2">Demo interactiva</h3>
            <p class="text-sm mb-4">Tarjeta con interacción para mostrar tu propuesta o KPIs.</p>
            <div class="grid grid-cols-3 gap-2 text-center">
              <div>
                <div class="text-2xl font-bold">—</div>
                <div class="text-xs text-gray-500">Ahorro</div>
              </div>
              <div>
                <div class="text-2xl font-bold">—</div>
                <div class="text-xs text-gray-500">Impacto</div>
              </div>
              <div>
                <div class="text-2xl font-bold">—</div>
                <div class="text-xs text-gray-500">Comunidad</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- QUIENES SOMOS -->
    <section id="quienes" class="py-16 bg-white">
      <div class="max-w-6xl mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-10 items-center">
          <div data-aos="fade-up">
            <h2 class="text-3xl font-bold mb-3">Quiénes somos</h2>
            <p class="mb-4">En <strong>Beenet Energies</strong> trabajamos para mejorar la calidad de vida a través de soluciones energéticas responsables, accesibles y sostenibles.</p>
            <p class="mb-4">Equipo: <strong>Ionut Antonio George Mihai</strong>, <strong>Matías Torres Morales</strong>, <strong>Renata Vizitiu</strong> y <strong>Paula de Santiago Delgado</strong>.</p>
            <a href="#contacto" class="underline">Contáctanos para colaborar</a>
          </div>
          <div data-aos="zoom-in">
            <img src="assets/img/logo.png" alt="Equipo Beenet" class="rounded-lg shadow-lg w-full object-cover">
          </div>
        </div>
      </div>
    </section>

    <!-- VISION/MISION/ODS -->
    <section id="vision" class="py-16">
      <div class="max-w-6xl mx-auto px-6 space-y-6">
        <h2 class="text-3xl font-bold" data-aos="fade-up">Visión & Misión</h2>
        <div class="grid md:grid-cols-3 gap-6">
          <article data-aos="fade-right" class="p-6 bg-white rounded-xl shadow">
            <h3 class="font-semibold mb-2">Visión</h3>
            <p>Ser referencia en soluciones energéticas responsables para hogares y comunidades.</p>
          </article>
          <article data-aos="fade-up" class="p-6 bg-white rounded-xl shadow">
            <h3 class="font-semibold mb-2">Misión</h3>
            <p>Promover el uso eficiente de energía y recursos mediante herramientas accesibles y educación.</p>
          </article>
          <article data-aos="fade-left" class="p-6 bg-white rounded-xl shadow">
            <h3 class="font-semibold mb-2">ODS 12</h3>
            <p>Contribuimos a la producción y consumo responsables impulsando hábitos sostenibles.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- SOLUCIONES / SERVICIOS -->
    <section id="servicios" class="py-16 bg-white/60">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">Soluciones</h2>
        <div class="grid md:grid-cols-3 gap-6">
          <div data-aos="fade-up" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Ahorro y eficiencia</h4>
            <p>Herramientas y asesoría para reducir el consumo eléctrico y optimizar recursos en el hogar.</p>
          </div>
          <div data-aos="fade-up" data-aos-delay="80" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Productos accesibles</h4>
            <p>Selección de productos eficientes y económicos, pensados para hogares vulnerables.</p>
          </div>
          <div data-aos="fade-up" data-aos-delay="160" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Educación</h4>
            <p>Talleres, guías y campañas para concienciar sobre consumo responsable.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CAMPAÑAS -->
    <section id="campañas" class="py-16">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">Campañas</h2>
        <div class="grid md:grid-cols-3 gap-6">
          <article data-aos="flip-left" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Hogar Eficiente</h4>
            <p>Diagnósticos gratuitos y consejos prácticos para mejorar la eficiencia del hogar.</p>
          </article>
          <article data-aos="flip-left" data-aos-delay="80" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Semana de la Energía</h4>
            <p>Eventos y talleres en centros comunitarios para enseñar prácticas sostenibles.</p>
          </article>
          <article data-aos="flip-left" data-aos-delay="160" class="p-6 bg-white rounded-xl shadow">
            <h4 class="font-semibold mb-2">Desenchufa & Ahorra</h4>
            <p>Retos y guías para reducir el consumo de aparatos en stand-by.</p>
          </article>
        </div>
      </div>
    </section>

    <!-- BENEFICIOS -->
    <section id="beneficios" class="py-16 bg-white/60">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">Beneficios</h2>
        <ul class="grid md:grid-cols-3 gap-4" data-aos="fade-up" data-aos-delay="60">
          <li class="p-4 bg-white rounded-lg shadow">Ahorro económico en facturas</li>
          <li class="p-4 bg-white rounded-lg shadow">Reducción del impacto ambiental</li>
          <li class="p-4 bg-white rounded-lg shadow">Acceso a educación energética</li>
        </ul>
      </div>
    </section>

    <!-- COLABORACIONES -->
    <section id="colab" class="py-16">
      <div class="max-w-6xl mx-auto px-6">
        <h2 class="text-3xl font-bold mb-6" data-aos="fade-up">Colaboraciones</h2>
        <p data-aos="fade-up" class="mb-4">Trabajamos con instituciones, ONGs y centros educativos. ¿Quieres colaborar? Escríbenos.</p>
        <div class="flex flex-wrap gap-4" data-aos="fade-up" data-aos-delay="80">
          <span class="px-4 py-2 bg-white rounded-full shadow text-sm">ONG Local</span>
          <span class="px-4 py-2 bg-white rounded-full shadow text-sm">Colegio X</span>
          <span class="px-4 py-2 bg-white rounded-full shadow text-sm">Empresa Y</span>
        </div>
      </div>
    </section>

    <!-- CONTACTO -->
    <section id="contacto" class="py-16 bg-white/90">
      <div class="max-w-4xl mx-auto px-6">
        <h2 class="text-3xl font-bold mb-4" data-aos="fade-up">Contacto</h2>
        <p data-aos="fade-up" class="mb-6">Escríbenos para colaboraciones, dudas o si quieres un diagnóstico.</p>

        <!-- Formulario simple (usa mailto como fallback) -->
        <form id="contactForm" class="grid grid-cols-1 gap-4" data-aos="fade-up" onsubmit="return handleContact(event)">
          <input required name="nombre" type="text" placeholder="Tu nombre" class="p-3 rounded border">
          <input required name="email" type="email" placeholder="Tu email" class="p-3 rounded border">
          <textarea required name="mensaje" rows="5" placeholder="Mensaje" class="p-3 rounded border"></textarea>
          <div class="flex gap-4">
            <button type="submit" class="px-5 py-3 rounded-lg btn-primary">Enviar mensaje</button>
            <a href="mailto:tu-email@ejemplo.com" class="px-5 py-3 rounded-lg border">Enviar desde tu correo</a>
          </div>
          <p id="formMessage" class="text-sm text-green-600 hidden">¡Mensaje enviado! Gracias.</p>
        </form>
      </div>
    </section>
  </main>

  <footer class="py-8 border-t bg-white">
    <div class="max-w-6xl mx-auto px-6 text-center text-sm">
      © <span id="year"></span> Beenet Energies — Proyecto académico.
    </div>
  </footer>

  <!-- Scripts: GSAP y AOS -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.0/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>

  <!-- Script propio -->
  <script src="script.js"></script>
  <script>
    // Inicializaciones pequeñas que no cambian
    AOS.init({ once: true, duration: 800 });
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>


