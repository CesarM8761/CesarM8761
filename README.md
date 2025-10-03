<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>README personal</title>
  <style>
    :root {
      --bg: #0b1220;
      --card: #0f1724;
      --accent: #06b6d4;
      --muted: #94a3b8;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    html, body {
      background: var(--bg);
      color: #e6eef8;
      margin: 0;
      padding: 24px;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      border-radius: 10px;
      padding: 28px;
      box-shadow: 0 6px 24px rgba(2,6,23,0.6);
    }
    header {
      display: flex;
      gap: 18px;
      align-items: center;
    }
    .avatar {
      width: 96px;
      height: 96px;
      border-radius: 12px;
      background: linear-gradient(135deg, var(--accent), #7c3aed);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 28px;
      color: #021127;
    }
    h1 { margin: 0; font-size: 22px }
    p.lead { margin: 6px 0 0 0; color: var(--muted) }

    .grid {
      display: grid;
      grid-template-columns: 1fr 340px;
      gap: 18px;
      margin-top: 18px;
    }

    .card {
      background: var(--card);
      border-radius: 10px;
      padding: 14px;
      box-shadow: 0 4px 14px rgba(2,6,23,0.4);
    }

    .skills-icons { margin-top: 10px }
    .skills-icons img { margin: 4px; max-width: 100% }

    .contact a { display: inline-block; margin-right: 10px; color: var(--muted); text-decoration: none; font-size: 13px }

    .projects { display: grid; gap: 14px; grid-template-columns: 1fr 1fr }
    .project { background: var(--card); border-radius: 10px; overflow: hidden; box-shadow: 0 4px 14px rgba(2,6,23,0.4) }
    .project img { width: 100%; height: 140px; object-fit: cover }
    .project-content { padding: 12px }
    .project h4 { margin: 0 0 6px 0 }
    .project a { color: var(--accent); text-decoration: none; font-size: 13px }
    .meta { color: var(--muted); font-size: 13px }

    footer { margin-top: 18px; color: var(--muted); font-size: 13px }

    @media (max-width: 900px) {
      .grid { grid-template-columns: 1fr; }
      .projects { grid-template-columns: 1fr }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">CM</div>
      <div>
        <h1>Cesar Mauricio Martinez Navarro</h1>
        <p class="lead">Desarrollador de software con experiencia en backend .NET, desarrollo full stack y administración de sistemas</p>
      </div>
    </header>

    <div class="grid">
      <div>
        <div class="card">
          <h3>Sobre mí</h3>
          <p class="meta">Soy un apasionado desarrollador de software, actualmente cursando Ingeniería de Sistemas, me especializo en backend con .NET y tengo experiencia con PHP, React, Kotlin, MySQL y PostgreSQL</p>
          <hr />
          <h4>Habilidades clave</h4>
          <div class="skills-icons">
            <a href="https://skillicons.dev">
              <img src="https://skillicons.dev/icons?i=dotnet,react,java,mysql,linux,docker&perline=3" />
            </a>
          </div>

          <h4 style="margin-top:12px">Stack tecnológico</h4>
          <div class="skills-icons">
            <a href="https://skillicons.dev">
              <img src="https://skillicons.dev/icons?i=cs,kotlin,php,python,mysql,postgres,git&perline=5" />
            </a>
          </div>
        </div>
<!--
        <div class="card" style="margin-top:12px">
          <h4>Proyectos</h4>
          <div class="projects">
            <div class="project">
              <img src="https://via.placeholder.com/300x140" alt="Proyecto 1" />
              <div class="project-content">
                <h4>Aplicación móvil de gestión residencial</h4>
                <div class="meta">Desarrollo full stack con .NET, Node.js, Express y Kotlin</div>
                <a href="#">Ver proyecto</a>
              </div>
            </div>
            <div class="project">
              <img src="https://via.placeholder.com/300x140" alt="Proyecto 2" />
              <div class="project-content">
                <h4>Plataforma tipo Airbnb</h4>
                <div class="meta">Laravel, reservas en tiempo real, seguridad y panel de administración</div>
                <a href="#">Ver proyecto</a>
              </div>
            </div>
            <div class="project">
              <img src="https://via.placeholder.com/300x140" alt="Proyecto 3" />
              <div class="project-content">
                <h4>Sitios web CMS</h4>
                <div class="meta">WordPress, WooCommerce, PrestaShop y Shopify</div>
                <a href="#">Ver proyecto</a>
              </div>
            </div>
          </div>
        </div>
-->
        <div class="card" style="margin-top:12px">
          <h4>Certificados</h4>
          <ul class="meta">
            <li><a href="https://platzi.com/p/cegamer/curso/4788-clean-code-csharp/diploma/detalle/">Buenas Prácticas y Código Limpio en C# - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/8036-c-sharp-poo/diploma/detalle/">Programación Orientada a Objetos con C# - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/4263-linq/diploma/detalle/">Manejo de Datos en C# con LINQ - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/4761-solid-csharp-net/diploma/detalle/">Principios SOLID en C# y .NET - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/3086-csharp/diploma/detalle/">Programación Básica en C# - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/2983-apis-net/diploma/detalle/">APIs con .NET - Platzi</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/2883-fundamentos-net/diploma/detalle/">Fundamentos de .NET - Platzi</a></li>
            <li><a href="https://www.udemy.com/certificate/UC-1918d150-e610-4aba-9694-2c6e28debdc6/">Fundamentos de Programación - Udemy</a></li>
            <li><a href="https://www.udemy.com/certificate/UC-3ee122a1-f37c-40fc-8426-15ea102a57eb/">Python 3 desde Cero - Udemy</a></li>
            <li><a href="https://platzi.com/p/cegamer/curso/1050-basico-programacion/diploma/detalle/">Curso Básico de Programación - Platzi</a></li>
          </ul>
        </div>
      </div>

      <aside>
        <div class="card contact">
          <h4>Contacto</h4>
          <div class="meta">
            <a href="https://github.com/CesarM8761" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/in/cesar-m-martinez" target="_blank">LinkedIn</a>
            <a href="mailto:cesarmauriciomn2012@gmail.com">Email</a>
          </div>
          <h4 style="margin-top:12px">Idiomas</h4>
          <div class="meta">Español nativo, Inglés intermedio</div>
        </div>

        <div class="card" style="margin-top:12px">
          <h4>Disponibilidad</h4>
          <p class="meta">Abierto a proyectos freelance, colaboraciones open source y roles en backend y full stack</p>
        </div>
      </aside>
    </div>
  </div>
</body>
</html>
