<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KB Contabilidad</title>
  <link rel="stylesheet" href="/css/styles.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header class="header" id="inicio">
    <nav class="nav container">
      <a href="/" class="logo">
        <span class="logo-icon">KB</span>
        <span class="logo-text">Contabilidad</span>
      </a>
      <button class="nav-toggle" id="navToggle" aria-label="Abrir menú">
        <span></span><span></span><span></span>
      </button>
      <ul class="nav-menu" id="navMenu">
        <li><a href="#inicio" class="nav-link active">Inicio</a></li>
        <li><a href="#servicios" class="nav-link">Servicios</a></li>
        <li><a href="#nosotros" class="nav-link">Nosotros</a></li>
        <li><a href="#recursos" class="nav-link">Recursos</a></li>
        <li><a href="#contacto" class="nav-link">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <h1 class="hero-title">Soluciones contables <span class="text-accent">profesionales</span> para tu negocio</h1>
        <p class="hero-subtitle">En KB Contabilidad ofrecemos servicios integrales de contabilidad, asesoría fiscal y financiera para empresas y emprendedores. Tu tranquilidad financiera es nuestra prioridad.</p>
        <div class="hero-actions">
          <a href="#contacto" class="btn btn-primary">Solicitar consulta</a>
          <a href="#servicios" class="btn btn-outline">Ver servicios</a>
        </div>
      </div>
      <div class="hero-visual">
        <div class="hero-card">
          <div class="hero-card-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/></svg>
          </div>
          <div class="hero-card-stat">
            <span class="stat-number">+500</span>
            <span class="stat-label">Clientes satisfechos</span>
          </div>
        </div>
        <div class="hero-card">
          <div class="hero-card-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 12h-4l-3 9L9 3l-3 9H2"/></svg>
          </div>
          <div class="hero-card-stat">
            <span class="stat-number">15+</span>
            <span class="stat-label">Años de experiencia</span>
          </div>
        </div>
        <div class="hero-card">
          <div class="hero-card-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12l2 2 4-4"/><circle cx="12" cy="12" r="10"/></svg>
          </div>
          <div class="hero-card-stat">
            <span class="stat-number">100%</span>
            <span class="stat-label">Compromiso</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Servicios -->
  <section class="services" id="servicios">
    <div class="container">
      <div class="section-header">
        <span class="section-tag">Nuestros Servicios</span>
        <h2 class="section-title">Soluciones contables a tu medida</h2>
        <p class="section-desc">Ofrecemos una amplia gama de servicios diseñados para cubrir todas las necesidades contables y fiscales de tu empresa.</p>
      </div>
      <div class="services-grid">
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="3" width="20" height="14" rx="2"/><path d="M8 21h8"/><path d="M12 17v4"/></svg>
          </div>
          <h3>Contabilidad General</h3>
          <p>Registro y control de todas las operaciones financieras de tu empresa. Mantenemos tus libros contables al día y en orden.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8z"/><path d="M14 2v6h6"/><path d="M16 13H8"/><path d="M16 17H8"/><path d="M10 9H8"/></svg>
          </div>
          <h3>Declaraciones Fiscales</h3>
          <p>Preparación y presentación de declaraciones de impuestos mensuales y anuales. Cumplimiento fiscal garantizado.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 1v22"/><path d="M17 5H9.5a3.5 3.5 0 000 7h5a3.5 3.5 0 010 7H6"/></svg>
          </div>
          <h3>Nómina y Sueldos</h3>
          <p>Administración completa de nómina, cálculo de prestaciones, retenciones y contribuciones de seguridad social.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 16V8a2 2 0 00-1-1.73l-7-4a2 2 0 00-2 0l-7 4A2 2 0 002 8v8a2 2 0 001 1.73l7 4a2 2 0 002 0l7-4A2 2 0 0022 16z"/></svg>
          </div>
          <h3>Auditoría Financiera</h3>
          <p>Revisión exhaustiva de estados financieros para garantizar la transparencia y confiabilidad de tu información contable.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 20V10"/><path d="M12 20V4"/><path d="M6 20v-6"/></svg>
          </div>
          <h3>Asesoría Financiera</h3>
          <p>Consultoría estratégica para optimizar tus recursos financieros, planificación de inversiones y análisis de rentabilidad.</p>
        </div>
        <div class="service-card">
          <div class="service-icon">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 00-3-3.87"/><path d="M16 3.13a4 4 0 010 7.75"/></svg>
          </div>
          <h3>Constitución de Empresas</h3>
          <p>Asesoría integral para la creación de tu empresa: desde el registro legal hasta la estructura fiscal más conveniente.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Nosotros -->
  <section class="about" id="nosotros">
    <div class="container">
      <div class="about-grid">
        <div class="about-content">
          <span class="section-tag">Sobre Nosotros</span>
          <h2 class="section-title">Experiencia y compromiso con la excelencia contable</h2>
          <p>En <strong>KB Contabilidad</strong> contamos con un equipo de profesionales altamente capacitados, dedicados a brindar soluciones contables y fiscales de la más alta calidad.</p>
          <p>Nuestra misión es ser el aliado estratégico de nuestros clientes, proporcionando información financiera precisa y oportuna que les permita tomar las mejores decisiones para el crecimiento de su negocio.</p>
          <div class="about-features">
            <div class="about-feature">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12l2 2 4-4"/><circle cx="12" cy="12" r="10"/></svg>
              <span>Profesionales certificados</span>
            </div>
            <div class="about-feature">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12l2 2 4-4"/><circle cx="12" cy="12" r="10"/></svg>
              <span>Atención personalizada</span>
            </div>
            <div class="about-feature">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12l2 2 4-4"/><circle cx="12" cy="12" r="10"/></svg>
              <span>Tecnología de vanguardia</span>
            </div>
            <div class="about-feature">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12l2 2 4-4"/><circle cx="12" cy="12" r="10"/></svg>
              <span>Confidencialidad absoluta</span>
            </div>
          </div>
        </div>
        <div class="about-stats">
          <div class="stat-card">
            <span class="stat-card-number">500+</span>
            <span class="stat-card-label">Clientes activos</span>
          </div>
          <div class="stat-card">
            <span class="stat-card-number">15+</span>
            <span class="stat-card-label">Años en el mercado</span>
          </div>
          <div class="stat-card">
            <span class="stat-card-number">98%</span>
            <span class="stat-card-label">Satisfacción</span>
          </div>
          <div class="stat-card">
            <span class="stat-card-number">20+</span>
            <span class="stat-card-label">Profesionales</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Recursos -->
  <section class="resources" id="recursos">
    <div class="container">
      <div class="section-header">
        <span class="section-tag">Recursos</span>
        <h2 class="section-title">Conocimiento contable a tu alcance</h2>
        <p class="section-desc">Artículos y guías para mantener tus finanzas en orden y estar al día con las obligaciones fiscales.</p>
      </div>
      <div class="resources-grid">
        <article class="resource-card">
          <div class="resource-tag">Fiscal</div>
          <h3>Obligaciones fiscales para PyMEs</h3>
          <p>Conoce las principales obligaciones tributarias que toda pequeña y mediana empresa debe cumplir para operar correctamente.</p>
          <span class="resource-date">Marzo 2026</span>
        </article>
        <article class="resource-card">
          <div class="resource-tag">Contabilidad</div>
          <h3>Principios básicos de contabilidad</h3>
          <p>Una guía introductoria a los fundamentos de la contabilidad: activos, pasivos, capital, ingresos y egresos explicados de forma sencilla.</p>
          <span class="resource-date">Febrero 2026</span>
        </article>
        <article class="resource-card">
          <div class="resource-tag">Finanzas</div>
          <h3>Cómo elaborar un presupuesto empresarial</h3>
          <p>Aprende paso a paso a crear un presupuesto efectivo que te permita planificar y controlar los recursos financieros de tu negocio.</p>
          <span class="resource-date">Enero 2026</span>
        </article>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section class="contact" id="contacto">
    <div class="container">
      <div class="contact-grid">
        <div class="contact-info">
          <span class="section-tag">Contacto</span>
          <h2 class="section-title">Hablemos sobre tu negocio</h2>
          <p>Estamos listos para ayudarte. Contáctanos y recibe una consulta inicial sin costo.</p>
          <div class="contact-details">
            <div class="contact-item">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07 19.5 19.5 0 01-6-6 19.79 19.79 0 01-3.07-8.67A2 2 0 014.11 2h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L8.09 9.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z"/></svg>
              <div>
                <strong>Teléfono</strong>
                <span>+52 (55) 1234-5678</span>
              </div>
            </div>
            <div class="contact-item">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><path d="M22 6l-10 7L2 6"/></svg>
              <div>
                <strong>Email</strong>
                <span>info@kbcontabilidad.com</span>
              </div>
            </div>
            <div class="contact-item">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"/><circle cx="12" cy="10" r="3"/></svg>
              <div>
                <strong>Dirección</strong>
                <span>Av. Principal #123, Col. Centro</span>
              </div>
            </div>
          </div>
        </div>
        <div class="contact-form-wrapper">
          <form class="contact-form" name="contacto" method="POST" data-netlify="true" netlify-honeypot="bot-field">
            <input type="hidden" name="form-name" value="contacto">
            <p class="hidden" aria-hidden="true">
              <label>No llenar: <input name="bot-field"></label>
            </p>
            <div class="form-group">
              <label for="nombre">Nombre completo</label>
              <input type="text" id="nombre" name="nombre" required placeholder="Tu nombre">
            </div>
            <div class="form-group">
              <label for="email">Correo electrónico</label>
              <input type="email" id="email" name="email" required placeholder="tu@email.com">
            </div>
            <div class="form-group">
              <label for="telefono">Teléfono</label>
              <input type="tel" id="telefono" name="telefono" placeholder="+52 (55) 0000-0000">
            </div>
            <div class="form-group">
              <label for="servicio">Servicio de interés</label>
              <select id="servicio" name="servicio" required>
                <option value="" disabled selected>Selecciona un servicio</option>
                <option value="contabilidad">Contabilidad General</option>
                <option value="fiscal">Declaraciones Fiscales</option>
                <option value="nomina">Nómina y Sueldos</option>
                <option value="auditoria">Auditoría Financiera</option>
                <option value="asesoria">Asesoría Financiera</option>
                <option value="constitucion">Constitución de Empresas</option>
                <option value="otro">Otro</option>
              </select>
            </div>
            <div class="form-group">
              <label for="mensaje">Mensaje</label>
              <textarea id="mensaje" name="mensaje" rows="4" required placeholder="Cuéntanos cómo podemos ayudarte"></textarea>
            </div>
            <button type="submit" class="btn btn-primary btn-full">Enviar mensaje</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="footer-grid">
        <div class="footer-brand">
          <a href="/" class="logo">
            <span class="logo-icon">KB</span>
            <span class="logo-text">Contabilidad</span>
          </a>
          <p>Soluciones contables profesionales para impulsar el crecimiento de tu negocio.</p>
        </div>
        <div class="footer-links">
          <h4>Enlaces</h4>
          <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#nosotros">Nosotros</a></li>
            <li><a href="#recursos">Recursos</a></li>
            <li><a href="#contacto">Contacto</a></li>
          </ul>
        </div>
        <div class="footer-links">
          <h4>Servicios</h4>
          <ul>
            <li><a href="#servicios">Contabilidad General</a></li>
            <li><a href="#servicios">Declaraciones Fiscales</a></li>
            <li><a href="#servicios">Nómina y Sueldos</a></li>
            <li><a href="#servicios">Auditoría Financiera</a></li>
            <li><a href="#servicios">Asesoría Financiera</a></li>
          </ul>
        </div>
        <div class="footer-links">
          <h4>Horario</h4>
          <ul>
            <li>Lunes a Viernes</li>
            <li>9:00 AM - 6:00 PM</li>
            <li>Sábado</li>
            <li>9:00 AM - 1:00 PM</li>
          </ul>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; 2026 KB Contabilidad. Todos los derechos reservados.</p>
      </div>
    </div>
  </footer>

  <script>
    // Mobile nav toggle
    const navToggle = document.getElementById('navToggle');
    const navMenu = document.getElementById('navMenu');
    navToggle.addEventListener('click', () => {
      navMenu.classList.toggle('open');
      navToggle.classList.toggle('active');
    });

    // Close menu on link click
    document.querySelectorAll('.nav-link').forEach(link => {
      link.addEventListener('click', () => {
        navMenu.classList.remove('open');
        navToggle.classList.remove('active');
      });
    });

    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });

    // Active nav link on scroll
    const sections = document.querySelectorAll('section, .hero');
    const navLinks = document.querySelectorAll('.nav-link');
    window.addEventListener('scroll', () => {
      let current = '';
      sections.forEach(section => {
        const sectionTop = section.offsetTop - 100;
        if (scrollY >= sectionTop) {
          current = section.getAttribute('id') || 'inicio';
        }
      });
      navLinks.forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href') === '#' + current) {
          link.classList.add('active');
        }
      });
    });

    // Header shadow on scroll
    const header = document.querySelector('.header');
    window.addEventListener('scroll', () => {
      header.classList.toggle('scrolled', window.scrollY > 10);
    });
  </script>
</body>
</html># Mi-sitio-web
Página web 
