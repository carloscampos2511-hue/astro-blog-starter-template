<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Campos Legal Tax — Tu firma legal de confianza</title>
<meta name="description" content="Derecho corporativo y tributario. Oficinas en Samborondón - Ecuador. Acompañamos empresas que crecen.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bone:#F8F6F1;
  --bone-2:#F1EEE6;
  --carbon:#1A2638;
  --carbon-soft:#2A3548;
  --gray-1:#5B5B5B;
  --gray-2:#6A6A6A;
  --gray-3:#4A4A4A;
  --line:#D9D3C5;
  --gold:#B89968;
  --max:1240px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  background:var(--bone);
  color:var(--carbon);
  font-family:'Inter',sans-serif;
  font-weight:400;
  line-height:1.6;
  -webkit-font-smoothing:antialiased;
  font-size:16px;
}
.serif{font-family:'Cormorant Garamond',serif;font-weight:500;letter-spacing:-0.01em}
a{color:inherit;text-decoration:none}
img{max-width:100%;display:block}

/* NAV */
.nav{
  position:fixed;top:0;left:0;right:0;z-index:50;
  background:rgba(248,246,241,0.85);
  backdrop-filter:blur(12px);
  border-bottom:1px solid transparent;
  transition:border-color .3s, background .3s;
}
.nav.scrolled{border-bottom-color:var(--line)}
.nav-inner{
  max-width:var(--max);margin:0 auto;
  padding:18px 32px;
  display:flex;align-items:center;justify-content:space-between;
}
.brand{display:flex;align-items:center;gap:14px;text-decoration:none}
.brand-logo{
  height:44px;width:auto;display:block;
}
.brand-fallback{display:flex;align-items:baseline;gap:10px}
.brand-mark{
  font-family:'Cormorant Garamond',serif;
  font-size:30px;font-weight:500;letter-spacing:0.06em;
  color:var(--carbon);
  position:relative;
  text-transform:uppercase;
}
.brand-mark::after{
  content:"";position:absolute;left:0;right:0;bottom:-5px;
  height:2px;background:var(--carbon);
}
.brand-sub{font-size:11px;color:var(--gray-2);letter-spacing:0.14em;text-transform:uppercase}
.nav-menu{display:flex;gap:34px;align-items:center}
.nav-menu a{font-size:14px;color:var(--carbon);font-weight:400;transition:color .2s}
.nav-menu a:hover{color:var(--gray-1)}
.nav-cta{
  background:var(--carbon);color:var(--bone);
  padding:10px 20px;font-size:13px;letter-spacing:0.04em;
  border:1px solid var(--carbon);transition:all .25s;
}
.nav-cta:hover{background:transparent;color:var(--carbon)}
.menu-btn{display:none;background:none;border:none;font-size:22px;color:var(--carbon);cursor:pointer}

/* HERO */
.hero{
  min-height:100vh;
  display:flex;align-items:center;
  padding:140px 32px 80px;
}
.hero-inner{max-width:var(--max);margin:0 auto;width:100%;display:grid;grid-template-columns:1.4fr 1fr;gap:80px;align-items:center}
.hero-eyebrow{
  font-size:12px;letter-spacing:0.18em;text-transform:uppercase;
  color:var(--gray-1);margin-bottom:28px;
  display:flex;align-items:center;gap:14px;
}
.hero-eyebrow::before{content:"";width:36px;height:1px;background:var(--carbon)}
.hero h1{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(44px,6vw,82px);
  font-weight:500;
  line-height:1.04;
  letter-spacing:-0.015em;
  color:var(--carbon);
  margin-bottom:32px;
}
.hero h1 em{font-style:italic;color:var(--carbon-soft);font-weight:400}
.hero-lede{
  font-size:18px;color:var(--gray-1);max-width:540px;
  margin-bottom:42px;line-height:1.65;
}
.hero-actions{display:flex;gap:18px;align-items:center;flex-wrap:wrap}
.btn-primary{
  background:var(--carbon);color:var(--bone);
  padding:16px 32px;font-size:14px;letter-spacing:0.04em;
  border:1px solid var(--carbon);transition:all .25s;
  display:inline-block;
}
.btn-primary:hover{background:transparent;color:var(--carbon)}
.btn-ghost{
  color:var(--carbon);padding:16px 0;font-size:14px;letter-spacing:0.04em;
  border-bottom:1px solid var(--carbon);transition:all .25s;
}
.btn-ghost:hover{color:var(--gray-1);border-color:var(--gray-1)}

.hero-card{
  background:var(--bone-2);
  border:1px solid var(--line);
  padding:42px 38px;
  position:relative;
}
.hero-card-label{
  font-size:11px;letter-spacing:0.18em;text-transform:uppercase;
  color:var(--gray-1);margin-bottom:18px;
}
.hero-card h3{
  font-family:'Cormorant Garamond',serif;
  font-size:28px;font-weight:500;line-height:1.25;
  margin-bottom:16px;
}
.hero-card p{font-size:15px;color:var(--gray-1);line-height:1.6;margin-bottom:22px}
.hero-card .meta{
  font-size:12px;letter-spacing:0.1em;text-transform:uppercase;
  color:var(--gray-3);
  border-top:1px solid var(--line);padding-top:18px;margin-top:18px;
  display:flex;justify-content:space-between;
}

/* SECTION */
section{padding:120px 32px;border-top:1px solid var(--line)}
.container{max-width:var(--max);margin:0 auto}
.sec-eyebrow{
  font-size:12px;letter-spacing:0.18em;text-transform:uppercase;
  color:var(--gray-1);margin-bottom:18px;
  display:flex;align-items:center;gap:14px;
}
.sec-eyebrow::before{content:"";width:36px;height:1px;background:var(--carbon)}
.sec-title{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(34px,4.5vw,56px);
  font-weight:500;line-height:1.1;letter-spacing:-0.01em;
  margin-bottom:24px;max-width:780px;
}
.sec-lede{font-size:17px;color:var(--gray-1);max-width:680px;line-height:1.65;margin-bottom:64px}

/* PHILOSOPHY */
.philosophy{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:start}
.philosophy-quote{
  font-family:'Cormorant Garamond',serif;
  font-size:34px;font-weight:400;line-height:1.3;
  color:var(--carbon);font-style:italic;
}
.philosophy-quote::before{content:'"';font-size:90px;line-height:0.5;display:block;color:var(--gray-2);margin-bottom:24px}
.philosophy-body p{font-size:16px;color:var(--gray-1);margin-bottom:18px;line-height:1.7}
.philosophy-sign{
  margin-top:32px;font-size:13px;letter-spacing:0.1em;text-transform:uppercase;
  color:var(--carbon);
}
.philosophy-sign span{display:block;color:var(--gray-2);margin-top:4px;letter-spacing:0;text-transform:none}

/* SERVICES */
.services-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1px;background:var(--line);border:1px solid var(--line)}
.service{
  background:var(--bone);padding:48px 42px;
  transition:background .3s;
  position:relative;
  cursor:default;
}
.service:hover{background:var(--bone-2)}
.service-num{
  font-family:'Cormorant Garamond',serif;
  font-size:14px;color:var(--gray-2);font-style:italic;
  margin-bottom:18px;
}
.service h3{
  font-family:'Cormorant Garamond',serif;
  font-size:28px;font-weight:500;line-height:1.25;
  margin-bottom:16px;
}
.service p{font-size:15px;color:var(--gray-1);line-height:1.65;margin-bottom:24px}
.service ul{list-style:none}
.service ul li{
  font-size:14px;color:var(--gray-3);
  padding:10px 0;border-top:1px solid var(--line);
  display:flex;align-items:center;gap:12px;
}
.service ul li::before{
  content:"";width:5px;height:5px;background:var(--carbon);
  display:inline-block;flex-shrink:0;
}

/* SECTORES */
.sectores{background:var(--carbon);color:var(--bone);border-color:var(--carbon-soft)}
.sectores .sec-eyebrow{color:#9CA3AF}
.sectores .sec-eyebrow::before{background:var(--bone)}
.sectores .sec-title{color:var(--bone)}
.sectores .sec-lede{color:#B8BCC4}
.sectores-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:1px;background:var(--carbon-soft)}
.sector-item{
  background:var(--carbon);padding:38px 24px;
  border-bottom:1px solid var(--carbon-soft);
  text-align:left;transition:background .3s;
}
.sector-item:hover{background:var(--carbon-soft)}
.sector-item .num{
  font-family:'Cormorant Garamond',serif;
  font-size:13px;color:#9CA3AF;font-style:italic;margin-bottom:14px;
}
.sector-item h4{
  font-family:'Cormorant Garamond',serif;
  font-size:22px;font-weight:500;line-height:1.25;color:var(--bone);
}

/* CASOS */
.casos-list{display:flex;flex-direction:column;gap:0;border-top:1px solid var(--line)}
.caso{
  display:grid;grid-template-columns:120px 1fr 1fr 140px;gap:40px;
  padding:38px 0;border-bottom:1px solid var(--line);
  align-items:start;transition:padding .3s;
}
.caso:hover{padding-left:14px}
.caso-num{
  font-family:'Cormorant Garamond',serif;
  font-size:36px;color:var(--gray-2);font-weight:400;font-style:italic;
}
.caso-title{
  font-family:'Cormorant Garamond',serif;
  font-size:24px;font-weight:500;line-height:1.3;color:var(--carbon);
}
.caso-title .sector{
  display:block;font-family:'Inter',sans-serif;
  font-size:11px;letter-spacing:0.15em;text-transform:uppercase;
  color:var(--gray-2);margin-top:8px;font-style:normal;
}
.caso-desc{font-size:15px;color:var(--gray-1);line-height:1.65}
.caso-tag{
  font-size:11px;letter-spacing:0.12em;text-transform:uppercase;
  color:var(--carbon);text-align:right;
  border:1px solid var(--carbon);padding:8px 12px;
  align-self:start;justify-self:end;
}

/* APPROACH */
.approach{background:var(--bone-2)}
.approach-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:48px;margin-top:24px}
.approach-step{padding-top:28px;border-top:1px solid var(--carbon)}
.approach-step .num{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:14px;color:var(--gray-2);margin-bottom:14px;
}
.approach-step h4{
  font-family:'Cormorant Garamond',serif;
  font-size:24px;font-weight:500;line-height:1.25;margin-bottom:12px;
}
.approach-step p{font-size:15px;color:var(--gray-1);line-height:1.65}

/* FOUNDER */
.founder{display:grid;grid-template-columns:1fr 1.4fr;gap:80px;align-items:center}
.founder-portrait{
  aspect-ratio:3/4;background:var(--carbon);
  display:flex;align-items:center;justify-content:center;
  position:relative;overflow:hidden;
  border:1px solid var(--carbon-soft);
}
.founder-portrait::before{
  content:"";position:absolute;inset:14px;border:1px solid rgba(248,246,241,0.15);
}
.founder-portrait .initials{
  font-family:'Cormorant Garamond',serif;
  font-size:120px;font-weight:400;color:var(--bone);
  letter-spacing:-0.02em;
}
.founder-body h2{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(32px,4vw,48px);font-weight:500;line-height:1.15;
  margin-bottom:18px;
}
.founder-role{
  font-size:13px;letter-spacing:0.12em;text-transform:uppercase;
  color:var(--gray-1);margin-bottom:28px;
}
.founder-body p{font-size:16px;color:var(--gray-1);line-height:1.7;margin-bottom:18px}

/* CTA STRIP */
.cta-strip{padding:90px 32px;background:var(--carbon);color:var(--bone);text-align:center;border-top:1px solid var(--carbon-soft)}
.cta-strip h2{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(34px,4.5vw,52px);font-weight:500;line-height:1.15;
  margin-bottom:22px;font-style:italic;color:var(--bone);
}
.cta-strip p{font-size:17px;color:#B8BCC4;max-width:620px;margin:0 auto 36px;line-height:1.65}
.cta-strip a{
  background:var(--bone);color:var(--carbon);
  padding:16px 36px;font-size:14px;letter-spacing:0.04em;
  border:1px solid var(--bone);transition:all .25s;
  display:inline-block;
}
.cta-strip a:hover{background:transparent;color:var(--bone)}

/* FORM */
.form-section{background:var(--bone-2)}
.form-grid{display:grid;grid-template-columns:1fr 1.2fr;gap:80px;align-items:start}
.form-side h2{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(34px,4.5vw,52px);font-weight:500;line-height:1.1;margin-bottom:22px;
}
.form-side p{font-size:16px;color:var(--gray-1);line-height:1.65;margin-bottom:32px}
.form-side .info{border-top:1px solid var(--line);padding-top:28px;margin-top:32px}
.form-side .info-row{
  display:flex;justify-content:space-between;
  padding:14px 0;border-bottom:1px solid var(--line);
  font-size:14px;
}
.form-side .info-row span:first-child{
  color:var(--gray-2);text-transform:uppercase;letter-spacing:0.1em;font-size:12px;
}
.form-side .info-row span:last-child{color:var(--carbon)}

form{
  background:var(--bone);padding:48px 42px;
  border:1px solid var(--line);
}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:20px}
.form-field{margin-bottom:20px}
.form-field label{
  display:block;font-size:12px;letter-spacing:0.1em;text-transform:uppercase;
  color:var(--gray-1);margin-bottom:8px;
}
.form-field input,.form-field select,.form-field textarea{
  width:100%;padding:14px 16px;
  background:var(--bone-2);border:1px solid var(--line);
  font-family:'Inter',sans-serif;font-size:15px;color:var(--carbon);
  transition:border-color .2s, background .2s;
}
.form-field input:focus,.form-field select:focus,.form-field textarea:focus{
  outline:none;border-color:var(--carbon);background:var(--bone);
}
.form-field textarea{resize:vertical;min-height:120px;line-height:1.55}
.form-submit{
  background:var(--carbon);color:var(--bone);
  padding:16px 32px;font-size:14px;letter-spacing:0.04em;
  border:1px solid var(--carbon);transition:all .25s;
  font-family:'Inter',sans-serif;cursor:pointer;
  width:100%;margin-top:8px;
}
.form-submit:hover{background:transparent;color:var(--carbon)}
.form-note{
  font-size:12px;color:var(--gray-2);margin-top:18px;line-height:1.55;
  text-align:center;
}
.form-success{
  display:none;background:var(--bone);padding:60px 42px;border:1px solid var(--carbon);
  text-align:center;
}
.form-success.show{display:block}
.form-success h3{
  font-family:'Cormorant Garamond',serif;
  font-size:32px;font-weight:500;margin-bottom:16px;color:var(--carbon);
}
.form-success p{color:var(--gray-1);font-size:15px;line-height:1.65}

/* FOOTER */
footer{
  background:var(--carbon);color:var(--bone);
  padding:80px 32px 32px;
}
.foot-inner{max-width:var(--max);margin:0 auto}
.foot-grid{
  display:grid;grid-template-columns:1.6fr 1fr 1fr 1fr;gap:60px;
  padding-bottom:60px;border-bottom:1px solid var(--carbon-soft);
}
.foot-brand .mark{
  font-family:'Cormorant Garamond',serif;
  font-size:32px;font-weight:500;letter-spacing:0.04em;
  position:relative;display:inline-block;color:var(--bone);
}
.foot-brand .mark::after{
  content:"";position:absolute;left:0;right:0;bottom:-4px;
  height:1.5px;background:var(--bone);
}
.foot-brand .tag{
  font-family:'Cormorant Garamond',serif;font-style:italic;
  font-size:18px;color:#B8BCC4;margin-top:24px;line-height:1.4;
  max-width:280px;
}
.foot-col h5{
  font-size:11px;letter-spacing:0.15em;text-transform:uppercase;
  color:#9CA3AF;margin-bottom:20px;
}
.foot-col a, .foot-col p{
  display:block;font-size:14px;color:var(--bone);
  padding:6px 0;line-height:1.5;
  transition:color .2s;
}
.foot-col a:hover{color:#B8BCC4}
.foot-bottom{
  display:flex;justify-content:space-between;align-items:center;
  padding-top:32px;font-size:12px;color:#9CA3AF;letter-spacing:0.05em;
}

/* RESPONSIVE */
@media (max-width:980px){
  .hero-inner,.philosophy,.founder,.form-grid{grid-template-columns:1fr;gap:48px}
  .services-grid,.sectores-grid{grid-template-columns:repeat(2,1fr)}
  .approach-grid{grid-template-columns:1fr;gap:32px}
  .caso{grid-template-columns:60px 1fr;gap:20px}
  .caso-tag{grid-column:1/-1;justify-self:start;margin-top:8px}
  .caso-desc{grid-column:1/-1;padding-left:80px}
  .nav-menu{display:none}
  .nav-menu.open{
    display:flex;position:absolute;top:100%;left:0;right:0;
    background:var(--bone);flex-direction:column;
    padding:24px 32px;gap:18px;border-bottom:1px solid var(--line);
  }
  .menu-btn{display:block}
  section{padding:80px 24px}
  .hero{padding:120px 24px 60px}
  .form-row{grid-template-columns:1fr}
  form{padding:32px 24px}
  .foot-grid{grid-template-columns:1fr 1fr;gap:40px}
}
@media (max-width:560px){
  .services-grid,.sectores-grid{grid-template-columns:1fr}
  .foot-grid{grid-template-columns:1fr}
  .foot-bottom{flex-direction:column;gap:14px;text-align:center}
  .caso{grid-template-columns:1fr}
  .caso-desc{padding-left:0}
}
</style>
</head>
<body>

<!-- NAV -->
<nav class="nav" id="nav">
  <div class="nav-inner">
    <a href="#top" class="brand" aria-label="Campos Legal Tax — Inicio">
      <!-- Logo: cuando coloques "logo.png" en la misma carpeta del HTML, esta imagen se mostrará automáticamente y reemplazará el wordmark de respaldo -->
      <img src="logo.png" alt="Campos Legal Tax" class="brand-logo"
           onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
      <span class="brand-fallback">
        <span class="brand-mark">Campos</span>
        <span class="brand-sub">Legal Tax</span>
      </span>
    </a>
    <div class="nav-menu" id="navMenu">
      <a href="#filosofia">Filosofía</a>
      <a href="#servicios">Servicios</a>
      <a href="#fundador">Fundador</a>
      <a href="#contacto" class="nav-cta">Conversemos</a>
    </div>
    <button class="menu-btn" id="menuBtn" aria-label="Menú">≡</button>
  </div>
</nav>

<!-- HERO -->
<header class="hero" id="top">
  <div class="hero-inner">
    <div>
      <div class="hero-eyebrow">Oficinas en Samborondón - Ecuador</div>
      <h1>Tu firma legal <em>de confianza</em> para empresas que crecen.</h1>
      <p class="hero-lede">Derecho corporativo y tributario para pymes, exportadoras y operaciones en la costa ecuatoriana. Atención directa, criterio jurídico y estrategia, no urgencia.</p>
      <div class="hero-actions">
        <a href="#contacto" class="btn-primary">Agendar diagnóstico</a>
        <a href="#servicios" class="btn-ghost">Ver servicios</a>
      </div>
    </div>
    <aside class="hero-card">
      <div class="hero-card-label">Pieza del mes</div>
      <h3>Antes del problema, está la decisión que nadie tomó.</h3>
      <p>Boletín quincenal sobre criterio jurídico aplicado al día a día de la empresa: SRI, contratos, sucesiones, protección patrimonial.</p>
      <a href="#contacto" class="btn-ghost" style="font-size:13px;padding:10px 0">Suscribirme →</a>
      <div class="meta">
        <span>Newsletter</span>
        <span>Quincenal</span>
      </div>
    </aside>
  </div>
</header>

<!-- FILOSOFÍA -->
<section id="filosofia">
  <div class="container">
    <div class="sec-eyebrow">Filosofía</div>
    <div class="philosophy">
      <div>
        <p class="philosophy-quote">El abogado de cabecera no resuelve el pleito. Evita que llegue.</p>
      </div>
      <div class="philosophy-body">
        <p>En Campos Legal Tax acompañamos a empresarios que entienden que la asesoría legal no es un gasto reactivo: es la infraestructura silenciosa que sostiene la operación, el patrimonio y la familia.</p>
        <p>No vendemos urgencia. Construimos criterio. Cada empresa que asesoramos tiene un único interlocutor que conoce su sector, su estructura y su próxima decisión antes de que se convierta en problema.</p>
        <p>Lo que entregamos no es un proveedor de servicios legales. Es un despacho que piensa con usted.</p>
        <div class="philosophy-sign">
          Carlos Campos
          <span>Fundador · Campos Legal Tax</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICIOS -->
<section id="servicios">
  <div class="container">
    <div class="sec-eyebrow">Servicios</div>
    <h2 class="sec-title">Cuatro frentes, una sola interlocución.</h2>

    <div class="services-grid">
      <article class="service">
        <div class="service-num">i.</div>
        <h3>Consultoría corporativa</h3>
        <p>Estructura societaria, gobierno corporativo, contratos comerciales y mercantiles, fusiones, adquisiciones y reestructuraciones. El soporte legal del crecimiento.</p>
        <ul>
          <li>Constitución y reformas estatutarias</li>
          <li>Contratos comerciales y M&amp;A</li>
          <li>Compliance corporativo y societario</li>
          <li>Estructuras holding y filiales</li>
        </ul>
      </article>

      <article class="service">
        <div class="service-num">ii.</div>
        <h3>Planificación tributaria</h3>
        <p>Diagnóstico, optimización y defensa frente al SRI. Diseñamos estrategia tributaria con anticipación, no respuestas a notificaciones.</p>
        <ul>
          <li>Diagnóstico y planificación anual</li>
          <li>Reclamos administrativos y judiciales</li>
          <li>Recuperación de tributos</li>
          <li>Asesorías tributarias en general</li>
        </ul>
      </article>

      <article class="service">
        <div class="service-num">iii.</div>
        <h3>Asesoría administrativa</h3>
        <p>Acompañamiento ante entidades de control: Superintendencia de Compañías, SENAE, ARCOTEL, ARCSA, Ministerios. Trámites con criterio, no formularios.</p>
        <ul>
          <li>Permisos, licencias y registros sectoriales</li>
          <li>Importación, exportación y comercio exterior</li>
          <li>Resolución de controversias administrativas</li>
          <li>Protección de datos personales (PDP)</li>
        </ul>
      </article>

      <article class="service">
        <div class="service-num">iv.</div>
        <h3>Patrocinio judicial</h3>
        <p>Representación estratégica en sede contencioso-tributaria, civil y constitucional. Litigamos cuando la negociación cierra. Antes, no.</p>
        <ul>
          <li>Procesos contencioso-tributarios</li>
          <li>Procesos civiles y comerciales</li>
          <li>Acciones constitucionales</li>
          <li>Mediación y arbitraje empresarial</li>
        </ul>
      </article>
    </div>
  </div>
</section>

<!-- APPROACH -->
<section class="approach">
  <div class="container">
    <div class="sec-eyebrow">Cómo trabajamos</div>
    <h2 class="sec-title">Tres pasos. Cero sorpresas.</h2>
    <p class="sec-lede">El primer encuentro es gratuito y revelador. Lo que sigue se decide con criterio, no con presión comercial.</p>

    <div class="approach-grid">
      <div class="approach-step">
        <div class="num">— Paso uno</div>
        <h4>Diagnóstico</h4>
        <p>30 minutos para entender su empresa, sus operaciones reguladas, su exposición tributaria y su próxima decisión. Sin compromiso.</p>
      </div>
      <div class="approach-step">
        <div class="num">— Paso dos</div>
        <h4>Propuesta de acompañamiento</h4>
        <p>Documento corto con áreas críticas, plan de trabajo y modalidad sugerida: fee mensual, proyecto puntual o asesoría judicial.</p>
      </div>
      <div class="approach-step">
        <div class="num">— Paso tres</div>
        <h4>Acompañamiento</h4>
        <p>Un único interlocutor, respuestas en máximo 24 horas hábiles, reportes trimestrales y reuniones presenciales en Samborondón cuando lo amerite.</p>
      </div>
    </div>
  </div>
</section>

<!-- FOUNDER -->
<section id="fundador">
  <div class="container">
    <div class="founder">
      <div class="founder-portrait">
        <span class="initials">CC</span>
      </div>
      <div class="founder-body">
        <div class="sec-eyebrow">Sobre el fundador</div>
        <h2>Carlos Campos.</h2>
        <div class="founder-role">Abogado · Fundador de Campos Legal Tax</div>
        <p>Abogado ecuatoriano con experiencia previa en multinacionales, banca regional e industria pesada antes de fundar el despacho. Esa trayectoria definió un criterio: el mejor servicio legal no se factura por hora, se construye por relación.</p>
        <p>Campos Legal Tax nace para empresarios que prefieren un despacho boutique con atención directa, sobre estructuras grandes que delegan en asociados rotativos. La diferencia se siente en el primer correo y se demuestra en el segundo año.</p>
        <p>Domicilio profesional en Samborondón. Clientes en Guayaquil, Quito, Cuenca, Manta y operaciones internacionales coordinadas en español e inglés.</p>
      </div>
    </div>
  </div>
</section>

<!-- CTA STRIP -->
<div class="cta-strip">
  <h2>Acompañamos empresas que crecen.</h2>
  <p>Si su empresa está en un punto de inflexión —expansión, sucesión, contingencia tributaria, nueva ronda de inversión— hablemos antes del problema.</p>
  <a href="#contacto">Agendar diagnóstico</a>
</div>

<!-- FORM -->
<section class="form-section" id="contacto">
  <div class="container">
    <div class="form-grid">
      <div class="form-side">
        <div class="sec-eyebrow">Contacto</div>
        <h2>Conversemos sobre su empresa.</h2>
        <p>Complete el formulario con la mayor precisión posible. Respondemos en máximo 24 horas hábiles con propuesta de fecha para diagnóstico inicial.</p>
        <p>Para asuntos urgentes contencioso-tributarios escriba directamente al correo del despacho.</p>

        <div class="info">
          <div class="info-row">
            <span>Oficina</span>
            <span>Samborondón - Ecuador</span>
          </div>
          <div class="info-row">
            <span>Correo</span>
            <span>info@camposlegaltax.com</span>
          </div>
          <div class="info-row">
            <span>Tiempo de respuesta</span>
            <span>Máximo 24 h hábiles</span>
          </div>
          <div class="info-row">
            <span>Idiomas</span>
            <span>Español · English</span>
          </div>
        </div>
      </div>

      <div>
        <form id="contactForm" novalidate>
          <div class="form-row">
            <div class="form-field">
              <label for="nombre">Nombre completo</label>
              <input type="text" id="nombre" name="nombre" required>
            </div>
            <div class="form-field">
              <label for="empresa">Empresa</label>
              <input type="text" id="empresa" name="empresa" required>
            </div>
          </div>

          <div class="form-row">
            <div class="form-field">
              <label for="email">Correo corporativo</label>
              <input type="email" id="email" name="email" required>
            </div>
            <div class="form-field">
              <label for="telefono">Teléfono / WhatsApp</label>
              <input type="tel" id="telefono" name="telefono">
            </div>
          </div>

          <div class="form-row">
            <div class="form-field">
              <label for="sector">Sector</label>
              <select id="sector" name="sector" required>
                <option value="">Seleccionar...</option>
                <option>Agroexportación</option>
                <option>Banca y servicios financieros</option>
                <option>Cervecero y bebidas</option>
                <option>Cementero e industrial</option>
                <option>Logística internacional</option>
                <option>Manufactura / papelero</option>
                <option>Telecomunicaciones</option>
                <option>Servicios B2B</option>
                <option>Tecnología</option>
                <option>Otro</option>
              </select>
            </div>
            <div class="form-field">
              <label for="facturacion">Facturación anual estimada</label>
              <select id="facturacion" name="facturacion" required>
                <option value="">Seleccionar...</option>
                <option>Hasta $50.000 USD</option>
                <option>$50.000 - $250.000 USD</option>
                <option>$250.000 - $1.000.000 USD</option>
                <option>$1.000.000 - $5.000.000 USD</option>
                <option>Más de $5.000.000 USD</option>
              </select>
            </div>
          </div>

          <div class="form-field">
            <label for="interes">Área de interés</label>
            <select id="interes" name="interes" required>
              <option value="">Seleccionar...</option>
              <option>Fee mensual / abogado de cabecera</option>
              <option>Planificación tributaria</option>
              <option>Patrocinio judicial</option>
              <option>Estructuración corporativa</option>
              <option>Inversión extranjera en Ecuador</option>
              <option>Protección de datos personales</option>
              <option>Aún no lo tengo claro</option>
            </select>
          </div>

          <div class="form-field">
            <label for="mensaje">Cuéntenos brevemente su situación</label>
            <textarea id="mensaje" name="mensaje" rows="4" placeholder="¿Qué necesita resolver, anticipar o estructurar?"></textarea>
          </div>

          <button type="submit" class="form-submit">Enviar y agendar diagnóstico</button>
          <p class="form-note">Al enviar acepta nuestra política de tratamiento de datos personales conforme a la Ley Orgánica de Protección de Datos Personales del Ecuador.</p>
        </form>

        <div class="form-success" id="formSuccess">
          <h3>Mensaje recibido.</h3>
          <p>Gracias por escribirnos. Le responderemos en máximo 24 horas hábiles con propuesta de fecha para el diagnóstico inicial.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="foot-inner">
    <div class="foot-grid">
      <div class="foot-brand">
        <div class="mark">Campos</div>
        <div class="tag">Tu firma legal de confianza. Acompañamos empresas que crecen.</div>
      </div>
      <div class="foot-col">
        <h5>Despacho</h5>
        <a href="#filosofia">Filosofía</a>
        <a href="#fundador">Fundador</a>
        <a href="#contacto">Contacto</a>
      </div>
      <div class="foot-col">
        <h5>Servicios</h5>
        <a href="#servicios">Consultoría corporativa</a>
        <a href="#servicios">Planificación tributaria</a>
        <a href="#servicios">Asesoría administrativa</a>
        <a href="#servicios">Patrocinio judicial</a>
      </div>
      <div class="foot-col">
        <h5>Contacto</h5>
        <p>Samborondón - Ecuador</p>
        <p>info@camposlegaltax.com</p>
        <a href="#contacto">Agendar diagnóstico →</a>
      </div>
    </div>
    <div class="foot-bottom">
      <span>© 2026 Campos Legal Tax · Derecho corporativo y tributario</span>
      <span>Aviso legal · Política de privacidad</span>
    </div>
  </div>
</footer>

<script>
// Nav scroll state
const nav = document.getElementById('nav');
window.addEventListener('scroll', () => {
  if (window.scrollY > 24) nav.classList.add('scrolled');
  else nav.classList.remove('scrolled');
});

// Mobile menu
const menuBtn = document.getElementById('menuBtn');
const navMenu = document.getElementById('navMenu');
menuBtn.addEventListener('click', () => navMenu.classList.toggle('open'));
navMenu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => navMenu.classList.remove('open')));

// Form
const form = document.getElementById('contactForm');
const success = document.getElementById('formSuccess');
form.addEventListener('submit', e => {
  e.preventDefault();
  // Basic validation
  const required = ['nombre','empresa','email','sector','facturacion','interes'];
  for (const id of required) {
    const el = document.getElementById(id);
    if (!el.value.trim()) {
      el.focus();
      el.style.borderColor = '#B89968';
      return;
    }
  }
  form.style.display = 'none';
  success.classList.add('show');
  success.scrollIntoView({behavior:'smooth', block:'center'});
});
</script>
</body>
</html>
