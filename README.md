<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SHELDA | Aire Acondicionado en Querétaro · Distribuidor Autorizado GREE</title>
<meta name="description" content="SHELDA: venta, instalación y mantenimiento de aire acondicionado en Querétaro. Distribuidor autorizado GREE con 12 años de experiencia. Minisplits, Fan & Coil, Piso Techo, Paquete, Chillers y VRF.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@500;600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          display: ['Manrope', 'system-ui', 'sans-serif'],
          body: ['Inter', 'system-ui', 'sans-serif'],
        },
        colors: {
          brand: {
            50: '#eef6ff',
            100: '#d9eaff',
            200: '#bcdaff',
            300: '#8ec3ff',
            400: '#59a1ff',
            500: '#337dff',
            600: '#1b5cf5',
            700: '#1447e1',
            800: '#173ab6',
            900: '#19358f',
            950: '#142257',
          },
          navy: '#0b1a3a',
          ice: '#f4f8fc',
          teal: '#00b8c4',
          wa: '#25D366',
        },
        boxShadow: {
          soft: '0 10px 40px -12px rgba(11,26,58,0.15)',
          glow: '0 0 0 1px rgba(51,125,255,0.15), 0 20px 50px -20px rgba(51,125,255,0.5)',
        }
      }
    }
  }
</script>
<style>
  html { scroll-behavior: smooth; }
  body { font-family: 'Inter', system-ui, sans-serif; color: #1e293b; background: #ffffff; -webkit-font-smoothing: antialiased; }
  h1,h2,h3,h4,.font-display { font-family: 'Manrope', system-ui, sans-serif; }

  /* Reveal animations */
  .reveal { opacity: 0; transform: translateY(28px); transition: opacity .8s cubic-bezier(.22,1,.36,1), transform .8s cubic-bezier(.22,1,.36,1); }
  .reveal.in { opacity: 1; transform: none; }
  .reveal-delay-1 { transition-delay: .1s; }
  .reveal-delay-2 { transition-delay: .2s; }
  .reveal-delay-3 { transition-delay: .3s; }
  .reveal-delay-4 { transition-delay: .4s; }

  /* Hero background */
  .hero-bg {
    background:
      radial-gradient(1200px 600px at 85% 10%, rgba(0,184,196,0.18), transparent 60%),
      radial-gradient(900px 500px at 10% 90%, rgba(51,125,255,0.22), transparent 60%),
      linear-gradient(160deg, #0b1a3a 0%, #10285f 55%, #142257 100%);
  }
  .grid-lines {
    background-image:
      linear-gradient(rgba(255,255,255,0.05) 1px, transparent 1px),
      linear-gradient(90deg, rgba(255,255,255,0.05) 1px, transparent 1px);
    background-size: 56px 56px;
    mask-image: radial-gradient(ellipse at center, black 40%, transparent 80%);
    -webkit-mask-image: radial-gradient(ellipse at center, black 40%, transparent 80%);
  }

  /* Floating air flow lines */
  @keyframes flow { 0% { transform: translateX(-20%); opacity: 0; } 20% { opacity: .9; } 80% { opacity: .9; } 100% { transform: translateX(120%); opacity: 0; } }
  .flow-line { position: absolute; height: 2px; border-radius: 2px; background: linear-gradient(90deg, transparent, rgba(142,195,255,.9), transparent); animation: flow 6s linear infinite; }

  @keyframes floaty { 0%,100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
  .floaty { animation: floaty 6s ease-in-out infinite; }
  .floaty-slow { animation: floaty 9s ease-in-out infinite; }

  /* Card hover */
  .card { transition: transform .35s cubic-bezier(.22,1,.36,1), box-shadow .35s, border-color .35s; }
  .card:hover { transform: translateY(-6px); box-shadow: 0 24px 50px -20px rgba(11,26,58,0.25); border-color: rgba(51,125,255,.35); }

  /* Marquee */
  @keyframes marquee { from { transform: translateX(0); } to { transform: translateX(-50%); } }
  .marquee { animation: marquee 30s linear infinite; }
  .marquee:hover { animation-play-state: paused; }

  /* WhatsApp pulse */
  @keyframes pulse-ring { 0% { transform: scale(1); opacity: .6; } 100% { transform: scale(1.7); opacity: 0; } }
  .pulse-ring::before { content: ''; position: absolute; inset: 0; border-radius: 9999px; background: #25D366; animation: pulse-ring 2s ease-out infinite; z-index: -1; }

  /* Nav scrolled */
  #nav.scrolled { background: rgba(255,255,255,.92); backdrop-filter: blur(14px); box-shadow: 0 6px 30px -16px rgba(11,26,58,.25); }
  #nav.scrolled .nav-link { color: #0b1a3a; }
  #nav.scrolled .nav-logo-text { color: #0b1a3a; }
  #nav.scrolled .nav-sub { color: #64748b; }
  #nav.scrolled .burger span { background: #0b1a3a; }

  /* Gradient text */
  .grad-text { background: linear-gradient(90deg, #8ec3ff, #00e0ee); -webkit-background-clip: text; background-clip: text; color: transparent; }

  /* Steps line */
  .step-line::after { content: ''; position: absolute; top: 28px; left: calc(50% + 36px); width: calc(100% - 72px); height: 2px; background: linear-gradient(90deg, #bcdaff, #d9eaff); }
  @media (max-width: 1023px) { .step-line::after { display: none; } }

  /* Focus */
  input:focus, textarea:focus, select:focus { outline: none; border-color: #337dff; box-shadow: 0 0 0 4px rgba(51,125,255,.12); }

  ::selection { background: #bcdaff; color: #0b1a3a; }
</style>
</head>
<body>

<!-- ======================= NAVBAR ======================= -->
<header id="nav" class="fixed top-0 inset-x-0 z-50 transition-all duration-300">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="flex items-center justify-between h-20">
      <a href="#inicio" class="flex items-center gap-3 group">
       <div class="relative w-11 h-11 rounded-xl bg-gradient-to-br from-brand-500 to-teal flex items-center justify-center shadow-glow">
  <img src="LOGO SHELDA SF.png" alt="SHELDA Logo" class="w-6 h-6 object-contain">
</div>
        <div class="leading-tight">
          <div class="nav-logo-text font-display font-extrabold text-2xl tracking-tight text-white transition-colors">SHELDA</div>
          <div class="nav-sub text-[11px] uppercase tracking-[0.18em] text-brand-200 transition-colors">Climatización · Querétaro</div>
        </div>
      </a>

      <nav class="hidden lg:flex items-center gap-8">
        <a href="#servicios" class="nav-link text-sm font-medium text-white/85 hover:text-brand-400 transition-colors">Servicios</a>
        <a href="#equipos" class="nav-link text-sm font-medium text-white/85 hover:text-brand-400 transition-colors">Equipos</a>
        <a href="#nosotros" class="nav-link text-sm font-medium text-white/85 hover:text-brand-400 transition-colors">Nosotros</a>
        <a href="#proceso" class="nav-link text-sm font-medium text-white/85 hover:text-brand-400 transition-colors">Proceso</a>
        <a href="#contacto" class="nav-link text-sm font-medium text-white/85 hover:text-brand-400 transition-colors">Contacto</a>
      </nav>

      <div class="hidden lg:flex items-center gap-3">
        <a href="tel:+524422219667" class="nav-link inline-flex items-center gap-2 text-sm font-semibold text-white/90 hover:text-brand-400 transition-colors">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
          442 000 0000
        </a>
        <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20me%20interesa%20una%20cotizaci%C3%B3n%20de%20aire%20acondicionado." target="_blank" rel="noopener" class="inline-flex items-center gap-2 rounded-full bg-wa text-white text-sm font-semibold px-5 py-2.5 hover:brightness-110 hover:-translate-y-0.5 transition-all shadow-lg shadow-wa/30">
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="currentColor"><path d="M20.52 3.48A11.86 11.86 0 0012.06 0C5.5 0 .16 5.34.16 11.9c0 2.1.55 4.14 1.6 5.95L0 24l6.32-1.66a11.9 11.9 0 005.74 1.46c6.56 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.44-8.42zM12.06 21.8a9.9 9.9 0 01-5.04-1.38l-.36-.21-3.75.98 1-3.65-.24-.38a9.87 9.87 0 01-1.51-5.26c0-5.45 4.44-9.89 9.9-9.89 2.64 0 5.13 1.03 7 2.9a9.83 9.83 0 012.9 7c0 5.45-4.44 9.89-9.9 9.89zm5.43-7.4c-.3-.15-1.76-.87-2.03-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.64.07-.3-.15-1.26-.46-2.4-1.48-.88-.79-1.48-1.76-1.65-2.06-.17-.3-.02-.46.13-.6.13-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.6-.91-2.2-.24-.58-.49-.5-.67-.5h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.01-1.04 2.47s1.06 2.87 1.21 3.07c.15.2 2.1 3.2 5.08 4.48.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.76-.72 2.01-1.41.25-.7.25-1.29.17-1.41-.07-.13-.27-.2-.57-.35z"/></svg>
          WhatsApp
        </a>
      </div>

      <button id="burger" aria-label="Abrir menú" class="burger lg:hidden relative w-11 h-11 rounded-lg flex flex-col items-center justify-center gap-1.5">
        <span class="block w-6 h-0.5 bg-white rounded transition-all"></span>
        <span class="block w-6 h-0.5 bg-white rounded transition-all"></span>
        <span class="block w-6 h-0.5 bg-white rounded transition-all"></span>
      </button>
    </div>
  </div>

  <!-- Mobile menu -->
  <div id="mobileMenu" class="lg:hidden hidden bg-white border-t border-slate-100 shadow-soft">
    <div class="px-5 py-5 flex flex-col gap-1">
      <a href="#servicios" class="mob-link px-3 py-3 rounded-lg text-navy font-medium hover:bg-ice">Servicios</a>
      <a href="#equipos" class="mob-link px-3 py-3 rounded-lg text-navy font-medium hover:bg-ice">Equipos</a>
      <a href="#nosotros" class="mob-link px-3 py-3 rounded-lg text-navy font-medium hover:bg-ice">Nosotros</a>
      <a href="#proceso" class="mob-link px-3 py-3 rounded-lg text-navy font-medium hover:bg-ice">Proceso</a>
      <a href="#contacto" class="mob-link px-3 py-3 rounded-lg text-navy font-medium hover:bg-ice">Contacto</a>
      <div class="grid grid-cols-2 gap-3 mt-3">
        <a href="tel:+524422219667" class="inline-flex justify-center items-center gap-2 rounded-xl bg-navy text-white font-semibold py-3">Llamar</a>
        <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20me%20interesa%20una%20cotizaci%C3%B3n." target="_blank" rel="noopener" class="inline-flex justify-center items-center gap-2 rounded-xl bg-wa text-white font-semibold py-3">WhatsApp</a>
      </div>
    </div>
  </div>
</header>

<!-- ======================= HERO ======================= -->
<section id="inicio" class="hero-bg relative overflow-hidden text-white">
  <div class="absolute inset-0 grid-lines pointer-events-none"></div>
  <div class="flow-line w-72 top-[22%] left-0" style="animation-delay: 0s;"></div>
  <div class="flow-line w-96 top-[48%] left-0" style="animation-delay: 2s;"></div>
  <div class="flow-line w-64 top-[70%] left-0" style="animation-delay: 4s;"></div>

  <div class="max-w-7xl mx-auto px-5 sm:px-8 pt-36 pb-24 lg:pt-44 lg:pb-32 relative">
    <div class="grid lg:grid-cols-12 gap-12 items-center">
      <div class="lg:col-span-7">
        <div class="reveal inline-flex items-center gap-2 rounded-full border border-white/15 bg-white/5 backdrop-blur px-4 py-1.5 text-xs font-semibold tracking-wide">
          <span class="w-2 h-2 rounded-full bg-teal animate-pulse"></span>
          DISTRIBUIDOR AUTORIZADO <span class="grad-text font-extrabold">GREE</span> · QUERÉTARO
        </div>
        <h1 class="reveal reveal-delay-1 mt-6 font-display font-extrabold text-4xl sm:text-5xl lg:text-6xl leading-[1.05] tracking-tight">
          Climatización profesional que <span class="grad-text">se nota</span> en cada grado.
        </h1>
        <p class="reveal reveal-delay-2 mt-6 text-lg text-brand-100/85 max-w-xl leading-relaxed">
          Venta, instalación y mantenimiento de aire acondicionado con <strong class="text-white font-semibold">12 años de experiencia</strong>. Desde un minisplit para tu hogar hasta sistemas VRF y chillers para grandes proyectos — con la garantía y respaldo de GREE.
        </p>
        <div class="reveal reveal-delay-3 mt-9 flex flex-col sm:flex-row gap-4">
          <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20quiero%20cotizar%20un%20equipo%20de%20aire%20acondicionado." target="_blank" rel="noopener" class="inline-flex justify-center items-center gap-2.5 rounded-full bg-wa text-white font-semibold px-7 py-4 hover:brightness-110 hover:-translate-y-0.5 transition-all shadow-xl shadow-wa/30">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="currentColor"><path d="M20.52 3.48A11.86 11.86 0 0012.06 0C5.5 0 .16 5.34.16 11.9c0 2.1.55 4.14 1.6 5.95L0 24l6.32-1.66a11.9 11.9 0 005.74 1.46c6.56 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.44-8.42zM12.06 21.8a9.9 9.9 0 01-5.04-1.38l-.36-.21-3.75.98 1-3.65-.24-.38a9.87 9.87 0 01-1.51-5.26c0-5.45 4.44-9.89 9.9-9.89 2.64 0 5.13 1.03 7 2.9a9.83 9.83 0 012.9 7c0 5.45-4.44 9.89-9.9 9.89zm5.43-7.4c-.3-.15-1.76-.87-2.03-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.64.07-.3-.15-1.26-.46-2.4-1.48-.88-.79-1.48-1.76-1.65-2.06-.17-.3-.02-.46.13-.6.13-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.6-.91-2.2-.24-.58-.49-.5-.67-.5h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.01-1.04 2.47s1.06 2.87 1.21 3.07c.15.2 2.1 3.2 5.08 4.48.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.76-.72 2.01-1.41.25-.7.25-1.29.17-1.41-.07-.13-.27-.2-.57-.35z"/></svg>
            Cotizar por WhatsApp
          </a>
          <a href="#equipos" class="inline-flex justify-center items-center gap-2 rounded-full border border-white/20 bg-white/5 backdrop-blur text-white font-semibold px-7 py-4 hover:bg-white/10 transition-all">
            Ver equipos
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 14l-7 7m0 0l-7-7m7 7V3"/></svg>
          </a>
        </div>

        <div class="reveal reveal-delay-4 mt-12 grid grid-cols-3 gap-6 max-w-lg">
          <div>
            <div class="font-display font-extrabold text-3xl sm:text-4xl"><span class="counter" data-target="12">0</span>+</div>
            <div class="text-xs sm:text-sm text-brand-200/80 mt-1">Años de experiencia</div>
          </div>
          <div>
            <div class="font-display font-extrabold text-3xl sm:text-4xl"><span class="counter" data-target="2500">0</span>+</div>
            <div class="text-xs sm:text-sm text-brand-200/80 mt-1">Equipos instalados</div>
          </div>
          <div>
            <div class="font-display font-extrabold text-3xl sm:text-4xl"><span class="counter" data-target="100">0</span>%</div>
            <div class="text-xs sm:text-sm text-brand-200/80 mt-1">Personal certificado</div>
          </div>
        </div>
      </div>

      <!-- Hero visual -->
      <div class="lg:col-span-5 reveal reveal-delay-2">
        <div class="relative">
          <div class="absolute -inset-6 bg-gradient-to-tr from-brand-500/30 to-teal/30 blur-3xl rounded-full"></div>
          <div class="relative rounded-3xl border border-white/15 bg-white/[0.06] backdrop-blur-xl p-6 sm:p-8 shadow-2xl floaty">
            <!-- Unit illustration -->
            <div class="rounded-2xl bg-gradient-to-b from-white to-slate-100 p-5 shadow-inner">
              <div class="flex items-center justify-between">
                <div class="text-navy font-display font-extrabold tracking-tight">GREE</div>
                <div class="flex items-center gap-1.5 text-[10px] font-semibold text-brand-700"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span> INVERTER</div>
              </div>
              <div class="mt-4 h-2 rounded-full bg-slate-200"></div>
              <div class="mt-2 h-2 rounded-full bg-slate-200 w-4/5"></div>
              <div class="mt-5 grid grid-cols-6 gap-1.5">
                <div class="h-1 rounded bg-brand-200"></div><div class="h-1 rounded bg-brand-300"></div><div class="h-1 rounded bg-brand-400"></div><div class="h-1 rounded bg-brand-300"></div><div class="h-1 rounded bg-brand-200"></div><div class="h-1 rounded bg-brand-100"></div>
              </div>
            </div>
            <div class="mt-6 grid grid-cols-2 gap-4">
              <div class="rounded-xl bg-white/10 border border-white/10 p-4">
                <div class="text-[11px] uppercase tracking-wider text-brand-200">Temperatura</div>
                <div class="mt-1 font-display font-extrabold text-3xl">22<span class="text-lg text-brand-200">°C</span></div>
              </div>
              <div class="rounded-xl bg-white/10 border border-white/10 p-4">
                <div class="text-[11px] uppercase tracking-wider text-brand-200">Ahorro energético</div>
                <div class="mt-1 font-display font-extrabold text-3xl text-teal">-60<span class="text-lg">%</span></div>
              </div>
            </div>
            <div class="mt-5 flex items-center gap-3 rounded-xl bg-teal/15 border border-teal/30 p-3.5">
              <svg class="w-5 h-5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
              <div class="text-sm"><span class="font-semibold">Garantía GREE vigente</span> · Instalación certificada SHELDA</div>
            </div>
          </div>
          <!-- floating badge -->
          <div class="absolute -bottom-6 -left-4 sm:-left-10 rounded-2xl bg-white text-navy p-4 shadow-2xl floaty-slow">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-full bg-brand-50 flex items-center justify-center">
                <svg class="w-5 h-5 text-brand-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75m-3-7.036A11.959 11.959 0 013.598 6 11.99 11.99 0 003 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.332 9-6.03 9-11.622 0-1.31-.21-2.571-.598-3.751h-.152c-3.196 0-6.1-1.248-8.25-3.285z"/></svg>
              </div>
              <div>
                <div class="text-xs text-slate-500">Respaldo oficial</div>
                <div class="font-display font-bold text-sm">Distribuidor Autorizado</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- bottom wave -->
  <svg class="absolute bottom-0 left-0 w-full text-white" viewBox="0 0 1440 80" preserveAspectRatio="none" fill="currentColor"><path d="M0,40 C360,90 1080,-10 1440,40 L1440,80 L0,80 Z"/></svg>
</section>

<!-- ======================= TRUST BAR ======================= -->
<section class="bg-white border-b border-slate-100">
  <div class="max-w-7xl mx-auto px-5 sm:px-8 py-8">
    <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
      <div class="reveal flex items-center gap-3">
        <div class="w-11 h-11 rounded-xl bg-brand-50 flex items-center justify-center shrink-0"><svg class="w-5 h-5 text-brand-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M16.5 18.75h-9m9 0a3 3 0 013 3h-15a3 3 0 013-3m9 0v-3.375c0-.621-.503-1.125-1.125-1.125h-.871M7.5 18.75v-3.375c0-.621.504-1.125 1.125-1.125h.872m5.007 0H9.497m5.007 0a7.454 7.454 0 01-.982-3.172M9.497 14.25a7.454 7.454 0 00.981-3.172M5.25 4.236c-.982.143-1.954.317-2.916.52A6.003 6.003 0 007.73 9.728M5.25 4.236V4.5c0 2.108.966 3.99 2.48 5.228M5.25 4.236V2.721C7.456 2.41 9.71 2.25 12 2.25c2.291 0 4.545.16 6.75.47v1.516M7.73 9.728a6.726 6.726 0 002.748 1.35m8.272-6.842V4.5c0 2.108-.966 3.99-2.48 5.228m2.48-5.492a46.32 46.32 0 012.916.52 6.003 6.003 0 01-5.395 4.972m0 0a6.726 6.726 0 01-2.749 1.35m0 0a6.772 6.772 0 01-3.044 0"/></svg></div>
        <div><div class="font-display font-bold text-navy text-sm">Distribuidor GREE</div><div class="text-xs text-slate-500">Autorizado y certificado</div></div>
      </div>
      <div class="reveal reveal-delay-1 flex items-center gap-3">
        <div class="w-11 h-11 rounded-xl bg-brand-50 flex items-center justify-center shrink-0"><svg class="w-5 h-5 text-brand-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"/></svg></div>
        <div><div class="font-display font-bold text-navy text-sm">12 años en el mercado</div><div class="text-xs text-slate-500">Experiencia comprobada</div></div>
      </div>
      <div class="reveal reveal-delay-2 flex items-center gap-3">
        <div class="w-11 h-11 rounded-xl bg-brand-50 flex items-center justify-center shrink-0"><svg class="w-5 h-5 text-brand-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M11.42 15.17l-5.1-5.1a2.652 2.652 0 010-3.75l.53-.53a2.652 2.652 0 013.75 0l5.1 5.1M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M6.75 7.5l-1.5-1.5"/></svg></div>
        <div><div class="font-display font-bold text-navy text-sm">Técnicos certificados</div><div class="text-xs text-slate-500">Instalación bajo norma</div></div>
      </div>
      <div class="reveal reveal-delay-3 flex items-center gap-3">
        <div class="w-11 h-11 rounded-xl bg-brand-50 flex items-center justify-center shrink-0"><svg class="w-5 h-5 text-brand-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"/></svg></div>
        <div><div class="font-display font-bold text-navy text-sm">Querétaro y zona metro</div><div class="text-xs text-slate-500">Servicio local y rápido</div></div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= SERVICIOS ======================= -->
<section id="servicios" class="py-24 bg-ice">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="max-w-2xl reveal">
      <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Nuestros servicios</div>
      <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-navy tracking-tight leading-tight">Todo el ciclo de vida de tu equipo, en manos expertas.</h2>
      <p class="mt-4 text-slate-600 text-lg">Acompañamos a nuestros clientes desde la selección del equipo ideal hasta su mantenimiento a largo plazo. Un solo proveedor, cero complicaciones.</p>
    </div>

    <div class="mt-14 grid md:grid-cols-3 gap-6">
      <!-- Venta -->
      <div class="card reveal rounded-3xl bg-white border border-slate-100 p-8 shadow-soft relative overflow-hidden group">
        <div class="absolute -right-10 -top-10 w-40 h-40 rounded-full bg-brand-50 group-hover:scale-125 transition-transform duration-500"></div>
        <div class="relative">
          <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white flex items-center justify-center shadow-lg shadow-brand-500/30">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z"/></svg>
          </div>
          <div class="mt-6 text-xs font-bold text-brand-600 tracking-widest">01</div>
          <h3 class="mt-1 font-display font-bold text-2xl text-navy">Venta de equipos</h3>
          <p class="mt-3 text-slate-600 leading-relaxed">Asesoría técnica para elegir la capacidad y tecnología exacta que tu espacio necesita. Equipos GREE originales con garantía de fábrica y precios de distribuidor.</p>
          <ul class="mt-5 space-y-2 text-sm text-slate-700">
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Cálculo de carga térmica</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Tecnología Inverter de alta eficiencia</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Refacciones originales</li>
          </ul>
        </div>
      </div>
      <!-- Instalación -->
      <div class="card reveal reveal-delay-1 rounded-3xl bg-white border border-slate-100 p-8 shadow-soft relative overflow-hidden group">
        <div class="absolute -right-10 -top-10 w-40 h-40 rounded-full bg-brand-50 group-hover:scale-125 transition-transform duration-500"></div>
        <div class="relative">
          <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white flex items-center justify-center shadow-lg shadow-brand-500/30">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M11.42 15.17l-5.1-5.1a2.652 2.652 0 010-3.75l.53-.53a2.652 2.652 0 013.75 0l5.1 5.1M11.42 15.17L17.25 21A2.652 2.652 0 0021 17.25l-5.877-5.877M11.42 15.17l2.496-3.03c.317-.384.74-.626 1.208-.766M6.75 7.5l-1.5-1.5"/></svg>
          </div>
          <div class="mt-6 text-xs font-bold text-brand-600 tracking-widest">02</div>
          <h3 class="mt-1 font-display font-bold text-2xl text-navy">Instalación profesional</h3>
          <p class="mt-3 text-slate-600 leading-relaxed">Una instalación correcta define el rendimiento y la vida útil del equipo. Trabajamos con procedimientos certificados, herramienta especializada y acabados limpios.</p>
          <ul class="mt-5 space-y-2 text-sm text-slate-700">
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Vacío y presurización con nitrógeno</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Proyectos residenciales, comerciales e industriales</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Puesta en marcha y capacitación</li>
          </ul>
        </div>
      </div>
      <!-- Mantenimiento -->
      <div class="card reveal reveal-delay-2 rounded-3xl bg-white border border-slate-100 p-8 shadow-soft relative overflow-hidden group">
        <div class="absolute -right-10 -top-10 w-40 h-40 rounded-full bg-brand-50 group-hover:scale-125 transition-transform duration-500"></div>
        <div class="relative">
          <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white flex items-center justify-center shadow-lg shadow-brand-500/30">
            <svg class="w-7 h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.324.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 011.37.49l1.296 2.247a1.125 1.125 0 01-.26 1.431l-1.003.827c-.293.24-.438.613-.431.992a6.759 6.759 0 010 .255c-.007.378.138.75.43.99l1.005.828c.424.35.534.954.26 1.43l-1.298 2.247a1.125 1.125 0 01-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.57 6.57 0 01-.22.128c-.331.183-.581.495-.644.869l-.213 1.28c-.09.543-.56.941-1.11.941h-2.594c-.55 0-1.02-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 01-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 01-1.369-.49l-1.297-2.247a1.125 1.125 0 01.26-1.431l1.004-.827c.292-.24.437-.613.43-.992a6.932 6.932 0 010-.255c.007-.378-.138-.75-.43-.99l-1.004-.828a1.125 1.125 0 01-.26-1.43l1.297-2.247a1.125 1.125 0 011.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.087.22-.128.332-.183.582-.495.644-.869l.214-1.281z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          </div>
          <div class="mt-6 text-xs font-bold text-brand-600 tracking-widest">03</div>
          <h3 class="mt-1 font-display font-bold text-2xl text-navy">Mantenimiento y servicio</h3>
          <p class="mt-3 text-slate-600 leading-relaxed">Programas preventivos y atención correctiva para cualquier marca. Mantenemos tus equipos eficientes, silenciosos y libres de fallas costosas.</p>
          <ul class="mt-5 space-y-2 text-sm text-slate-700">
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Pólizas de mantenimiento preventivo</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Diagnóstico y reparación de todas las marcas</li>
            <li class="flex items-start gap-2"><svg class="w-4 h-4 mt-0.5 text-teal shrink-0" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/></svg>Limpieza profunda y carga de refrigerante</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= EQUIPOS ======================= -->
<section id="equipos" class="py-24 bg-white relative overflow-hidden">
  <div class="absolute top-0 right-0 w-[600px] h-[600px] rounded-full bg-brand-50 blur-3xl opacity-70 -translate-y-1/2 translate-x-1/3 pointer-events-none"></div>
  <div class="max-w-7xl mx-auto px-5 sm:px-8 relative">
    <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-6 reveal">
      <div class="max-w-2xl">
        <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Equipos y tecnologías</div>
        <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-navy tracking-tight leading-tight">Soluciones para cada espacio y cada escala.</h2>
        <p class="mt-4 text-slate-600 text-lg">Manejamos toda la línea de climatización: desde equipos residenciales hasta sistemas centrales para edificios, hoteles, hospitales y plantas industriales.</p>
      </div>
      <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20quiero%20asesor%C3%ADa%20para%20elegir%20el%20equipo%20ideal." target="_blank" rel="noopener" class="inline-flex items-center gap-2 font-semibold text-brand-700 hover:text-brand-900 transition-colors shrink-0">
        ¿No sabes cuál necesitas? Te asesoramos
        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3"/></svg>
      </a>
    </div>

    <div class="mt-14 grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-5">
      <!-- Minisplit -->
      <div class="card reveal rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><rect x="3" y="6" width="18" height="8" rx="2"/><path stroke-linecap="round" d="M6 10h12M7 17.5c1 1 2 1 3 0M11 17.5c1 1 2 1 3 0M15 17.5c1 1 2 1 3 0"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Minisplit</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Ideal para hogares, oficinas y consultorios. Tecnología Inverter, Wi-Fi y filtros de alta eficiencia. Capacidades de 1 a 3 toneladas.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Residencial</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Oficinas</span></div>
      </div>
      <!-- Fan & Coil -->
      <div class="card reveal reveal-delay-1 rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><circle cx="12" cy="12" r="2.2"/><path stroke-linecap="round" d="M12 9.8c0-3.5 2.5-5.3 4.5-4.3M12 14.2c0 3.5-2.5 5.3-4.5 4.3M9.8 12c-3.5 0-5.3-2.5-4.3-4.5M14.2 12c3.5 0 5.3 2.5 4.3 4.5"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Fan & Coil</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Unidades ocultas en plafón o expuestas para distribución por ductos. Máxima discreción y confort uniforme en espacios comerciales y hoteleros.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Hoteles</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Ductos</span></div>
      </div>
      <!-- Divididos -->
      <div class="card reveal reveal-delay-2 rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><rect x="3" y="4" width="8" height="7" rx="1.5"/><rect x="13" y="13" width="8" height="7" rx="1.5"/><path stroke-linecap="round" d="M11 7.5h3.5a2 2 0 012 2V13"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Sistemas Divididos</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Condensadora exterior y evaporadora interior de alta capacidad para locales, restaurantes y salones. Robustez y bajo costo operativo.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Comercial</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">3–20 TR</span></div>
      </div>
      <!-- Piso Techo -->
      <div class="card reveal reveal-delay-3 rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><rect x="4" y="3" width="16" height="5" rx="1.5"/><rect x="4" y="16" width="16" height="5" rx="1.5"/><path stroke-linecap="round" d="M12 8v8M9.5 11l2.5-3 2.5 3M9.5 13l2.5 3 2.5-3"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Piso Techo</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Versátiles: se instalan en piso o techo. Gran alcance de aire para naves pequeñas, gimnasios, aulas, iglesias y áreas de doble altura.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Amplios</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Flexible</span></div>
      </div>
      <!-- Paquete -->
      <div class="card reveal rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 7.5l-9-4.5-9 4.5m18 0l-9 4.5m9-4.5v9l-9 4.5m0-9L3 7.5m9 4.5v9m-9-13.5v9l9 4.5"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Unidades Paquete</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Todo en un solo gabinete para azotea. Solución probada para tiendas, bodegas, plantas y oficinas corporativas con red de ductos.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Azotea</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Industrial</span></div>
      </div>
      <!-- Chillers -->
      <div class="card reveal reveal-delay-1 rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 3v18M5 7.5l14 9M19 7.5l-14 9M12 3l-2 2m2-2l2 2M12 21l-2-2m2 2l2-2M5 7.5L4.5 4.8M5 7.5l-2.7.5M19 7.5l.5-2.7M19 7.5l2.7.5M5 16.5l-2.7-.5M5 16.5l-.5 2.7M19 16.5l2.7-.5M19 16.5l.5 2.7"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Chillers</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Enfriadores de agua para grandes cargas térmicas: hospitales, centros comerciales, procesos industriales y edificios de gran altura.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Gran escala</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Procesos</span></div>
      </div>
      <!-- VRF -->
      <div class="card reveal reveal-delay-2 rounded-2xl border border-slate-200 bg-white p-6">
        <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><rect x="9" y="3" width="6" height="5" rx="1.2"/><rect x="2.5" y="16" width="5" height="4.5" rx="1.2"/><rect x="9.5" y="16" width="5" height="4.5" rx="1.2"/><rect x="16.5" y="16" width="5" height="4.5" rx="1.2"/><path stroke-linecap="round" d="M12 8v4M5 16v-2a2 2 0 012-2h10a2 2 0 012 2v2M12 12v4"/></svg>
        </div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Sistemas VRF</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Flujo de refrigerante variable: control independiente por zona, ahorro energético superior y diseño para edificios, corporativos y hoteles.</p>
        <div class="mt-4 flex flex-wrap gap-1.5"><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Edificios</span><span class="text-[11px] font-semibold px-2.5 py-1 rounded-full bg-ice text-brand-800">Alta eficiencia</span></div>
      </div>
      <!-- CTA card -->
      <div class="card reveal reveal-delay-3 rounded-2xl bg-gradient-to-br from-navy to-brand-900 p-6 text-white flex flex-col justify-between">
        <div>
          <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-300">Proyecto a medida</div>
          <h3 class="mt-3 font-display font-bold text-xl leading-snug">¿Tienes un proyecto comercial o industrial?</h3>
          <p class="mt-2 text-sm text-brand-100/80">Diseñamos la ingeniería completa: cálculo, selección, ductería e instalación.</p>
        </div>
        <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20tengo%20un%20proyecto%20comercial%2Findustrial%20de%20climatizaci%C3%B3n." target="_blank" rel="noopener" class="mt-6 inline-flex items-center justify-center gap-2 rounded-full bg-white text-navy font-semibold px-5 py-3 hover:bg-brand-50 transition-colors">
          Hablar con un ingeniero
          <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 8l4 4m0 0l-4 4m4-4H3"/></svg>
        </a>
      </div>
    </div>
  </div>
</section>

<!-- ======================= MARQUEE ======================= -->
<section class="bg-navy py-5 overflow-hidden border-y border-white/5">
  <div class="flex whitespace-nowrap marquee">
    <div class="flex items-center gap-12 pr-12 text-sm font-semibold tracking-wide text-brand-100/80">
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>DISTRIBUIDOR AUTORIZADO GREE</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>12 AÑOS DE EXPERIENCIA</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>MINISPLIT</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>FAN & COIL</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>DIVIDIDOS</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>PISO TECHO</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>PAQUETE</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>CHILLERS</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>VRF</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>QUERÉTARO, MÉXICO</span>
    </div>
    <div class="flex items-center gap-12 pr-12 text-sm font-semibold tracking-wide text-brand-100/80" aria-hidden="true">
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>DISTRIBUIDOR AUTORIZADO GREE</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>12 AÑOS DE EXPERIENCIA</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>MINISPLIT</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>FAN & COIL</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>DIVIDIDOS</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>PISO TECHO</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>PAQUETE</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>CHILLERS</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>VRF</span>
      <span class="flex items-center gap-3"><span class="w-1.5 h-1.5 rounded-full bg-teal"></span>QUERÉTARO, MÉXICO</span>
    </div>
  </div>
</section>

<!-- ======================= NOSOTROS / POR QUÉ ======================= -->
<section id="nosotros" class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="grid lg:grid-cols-2 gap-14 lg:gap-20 items-center">
      <div class="reveal">
        <div class="relative">
          <div class="absolute -inset-4 bg-gradient-to-tr from-brand-100 to-teal/20 rounded-[2rem] blur-2xl"></div>
          <div class="relative rounded-[2rem] overflow-hidden bg-gradient-to-br from-navy via-brand-900 to-brand-700 p-8 sm:p-10 text-white shadow-2xl">
            <div class="absolute inset-0 grid-lines opacity-60"></div>
            <div class="relative">
              <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-300">Desde 2013</div>
              <div class="mt-4 font-display font-extrabold text-6xl sm:text-7xl leading-none">12</div>
              <div class="font-display font-bold text-2xl text-brand-100">años enfriando Querétaro</div>
              <p class="mt-6 text-brand-100/80 leading-relaxed">Comenzamos como un pequeño taller de servicio y hoy somos distribuidor autorizado de una de las marcas líderes a nivel mundial. Nuestro crecimiento se construyó con la confianza de cada cliente atendido.</p>
              <div class="mt-8 grid grid-cols-2 gap-4">
                <div class="rounded-2xl bg-white/10 border border-white/10 p-4">
                  <div class="font-display font-extrabold text-3xl text-teal">7</div>
                  <div class="text-xs text-brand-100/80 mt-1">Líneas de equipo</div>
                </div>
                <div class="rounded-2xl bg-white/10 border border-white/10 p-4">
                  <div class="font-display font-extrabold text-3xl text-teal">3</div>
                  <div class="text-xs text-brand-100/80 mt-1">Sectores: residencial, comercial e industrial</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div>
        <div class="reveal">
          <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">¿Por qué SHELDA?</div>
          <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-navy tracking-tight leading-tight">Experiencia, conocimiento y respaldo que marcan la diferencia.</h2>
          <p class="mt-4 text-slate-600 text-lg">No solo vendemos equipos: resolvemos problemas de confort y eficiencia con criterio técnico. Eso es lo que nos distingue de la competencia.</p>
        </div>

        <div class="mt-10 space-y-6">
          <div class="reveal flex gap-5">
            <div class="w-12 h-12 shrink-0 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center"><svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75m-3-7.036A11.959 11.959 0 013.598 6 11.99 11.99 0 003 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.332 9-6.03 9-11.622 0-1.31-.21-2.571-.598-3.751h-.152c-3.196 0-6.1-1.248-8.25-3.285z"/></svg></div>
            <div>
              <h3 class="font-display font-bold text-lg text-navy">Respaldo oficial GREE</h3>
              <p class="mt-1 text-slate-600 leading-relaxed">Como distribuidor autorizado garantizamos equipos originales, refacciones disponibles y validez total de la garantía de fábrica.</p>
            </div>
          </div>
          <div class="reveal reveal-delay-1 flex gap-5">
            <div class="w-12 h-12 shrink-0 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center"><svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"/></svg></div>
            <div>
              <h3 class="font-display font-bold text-lg text-navy">Conocimiento técnico real</h3>
              <p class="mt-1 text-slate-600 leading-relaxed">Dimensionamos con cálculo de carga térmica, no "a ojo". Un equipo bien seleccionado consume menos, dura más y enfría mejor.</p>
            </div>
          </div>
          <div class="reveal reveal-delay-2 flex gap-5">
            <div class="w-12 h-12 shrink-0 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center"><svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3.75 13.5l10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75z"/></svg></div>
            <div>
              <h3 class="font-display font-bold text-lg text-navy">Respuesta rápida y local</h3>
              <p class="mt-1 text-slate-600 leading-relaxed">Somos de Querétaro. Atendemos emergencias y mantenimientos en toda la zona metropolitana con tiempos de respuesta cortos.</p>
            </div>
          </div>
          <div class="reveal reveal-delay-3 flex gap-5">
            <div class="w-12 h-12 shrink-0 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center"><svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M11.48 3.499a.562.562 0 011.04 0l2.125 5.111a.563.563 0 00.475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 00-.182.557l1.285 5.385a.562.562 0 01-.84.61l-4.725-2.885a.563.563 0 00-.586 0L6.982 20.54a.562.562 0 01-.84-.61l1.285-5.386a.562.562 0 00-.182-.557l-4.204-3.602a.563.563 0 01.321-.988l5.518-.442a.563.563 0 00.475-.345L11.48 3.5z"/></svg></div>
            <div>
              <h3 class="font-display font-bold text-lg text-navy">Trabajo limpio y garantizado</h3>
              <p class="mt-1 text-slate-600 leading-relaxed">Instalaciones ordenadas, canalización estética y garantía por escrito de nuestra mano de obra. Dejamos tu espacio como lo encontramos.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= SECTORES ======================= -->
<section class="py-24 bg-ice">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="text-center max-w-2xl mx-auto reveal">
      <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Sectores que atendemos</div>
      <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-navy tracking-tight leading-tight">Del hogar a la industria.</h2>
    </div>
    <div class="mt-14 grid md:grid-cols-3 gap-6">
      <div class="card reveal rounded-3xl overflow-hidden bg-white border border-slate-100 shadow-soft">
        <div class="h-44 bg-gradient-to-br from-brand-400 to-brand-700 relative flex items-end p-6">
          <div class="absolute inset-0 grid-lines opacity-50"></div>
          <svg class="absolute right-6 top-6 w-16 h-16 text-white/30" fill="none" stroke="currentColor" stroke-width="1.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12l8.954-8.955c.44-.439 1.152-.439 1.591 0L21.75 12M4.5 9.75v10.125c0 .621.504 1.125 1.125 1.125H9.75v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21h4.125c.621 0 1.125-.504 1.125-1.125V9.75M8.25 21h8.25"/></svg>
          <h3 class="relative font-display font-bold text-2xl text-white">Residencial</h3>
        </div>
        <div class="p-6">
          <p class="text-slate-600 leading-relaxed">Casas, departamentos y fraccionamientos. Minisplits Inverter silenciosos y eficientes, con instalación limpia y control desde tu celular.</p>
          <ul class="mt-4 text-sm text-slate-700 space-y-1.5">
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Recámaras y salas</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Casas completas multizona</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Mantenimiento anual</li>
          </ul>
        </div>
      </div>
      <div class="card reveal reveal-delay-1 rounded-3xl overflow-hidden bg-white border border-slate-100 shadow-soft">
        <div class="h-44 bg-gradient-to-br from-brand-700 to-brand-900 relative flex items-end p-6">
          <div class="absolute inset-0 grid-lines opacity-50"></div>
          <svg class="absolute right-6 top-6 w-16 h-16 text-white/30" fill="none" stroke="currentColor" stroke-width="1.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z"/></svg>
          <h3 class="relative font-display font-bold text-2xl text-white">Comercial</h3>
        </div>
        <div class="p-6">
          <p class="text-slate-600 leading-relaxed">Oficinas, restaurantes, tiendas, clínicas, escuelas y hoteles. Sistemas divididos, Fan & Coil, piso techo y VRF con ingeniería a medida.</p>
          <ul class="mt-4 text-sm text-slate-700 space-y-1.5">
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Proyecto y ductería</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Control por zonas</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Pólizas empresariales</li>
          </ul>
        </div>
      </div>
      <div class="card reveal reveal-delay-2 rounded-3xl overflow-hidden bg-white border border-slate-100 shadow-soft">
        <div class="h-44 bg-gradient-to-br from-navy to-brand-800 relative flex items-end p-6">
          <div class="absolute inset-0 grid-lines opacity-50"></div>
          <svg class="absolute right-6 top-6 w-16 h-16 text-white/30" fill="none" stroke="currentColor" stroke-width="1.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 21h19.5m-18-18v18m10.5-18v18m6-13.5V21M6.75 6.75h.75m-.75 3h.75m-.75 3h.75m3-6h.75m-.75 3h.75m-.75 3h.75M6.75 21v-3.375c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21M3 3h12m-.75 4.5H21m-3.75 3.75h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008zm0 3h.008v.008h-.008v-.008z"/></svg>
          <h3 class="relative font-display font-bold text-2xl text-white">Industrial</h3>
        </div>
        <div class="p-6">
          <p class="text-slate-600 leading-relaxed">Naves, plantas de manufactura, laboratorios y centros de datos en el corredor industrial de Querétaro. Paquetes, chillers y control de procesos.</p>
          <ul class="mt-4 text-sm text-slate-700 space-y-1.5">
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Grandes cargas térmicas</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Confiabilidad 24/7</li>
            <li class="flex gap-2"><span class="text-teal font-bold">•</span> Mantenimiento programado</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= PROCESO ======================= -->
<section id="proceso" class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="text-center max-w-2xl mx-auto reveal">
      <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Cómo trabajamos</div>
      <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl lg:text-5xl text-navy tracking-tight leading-tight">Un proceso claro, sin sorpresas.</h2>
      <p class="mt-4 text-slate-600 text-lg">Sabemos que contratar climatización puede ser confuso. Por eso lo hacemos simple y transparente de principio a fin.</p>
    </div>

    <div class="mt-16 grid sm:grid-cols-2 lg:grid-cols-4 gap-8">
      <div class="reveal relative text-center step-line">
        <div class="mx-auto w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white font-display font-extrabold text-xl flex items-center justify-center shadow-lg shadow-brand-500/30 relative z-10">1</div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Contacto y diagnóstico</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Escríbenos por WhatsApp o llámanos. Escuchamos tu necesidad y, si es necesario, visitamos tu espacio sin costo.</p>
      </div>
      <div class="reveal reveal-delay-1 relative text-center step-line">
        <div class="mx-auto w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white font-display font-extrabold text-xl flex items-center justify-center shadow-lg shadow-brand-500/30 relative z-10">2</div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Propuesta técnica</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Calculamos la carga térmica y te presentamos la mejor opción de equipo con cotización detallada y transparente.</p>
      </div>
      <div class="reveal reveal-delay-2 relative text-center step-line">
        <div class="mx-auto w-14 h-14 rounded-2xl bg-gradient-to-br from-brand-500 to-brand-700 text-white font-display font-extrabold text-xl flex items-center justify-center shadow-lg shadow-brand-500/30 relative z-10">3</div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Instalación certificada</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Nuestro equipo técnico instala bajo estándares del fabricante, con acabados limpios y pruebas de funcionamiento.</p>
      </div>
      <div class="reveal reveal-delay-3 relative text-center">
        <div class="mx-auto w-14 h-14 rounded-2xl bg-gradient-to-br from-teal to-brand-500 text-white font-display font-extrabold text-xl flex items-center justify-center shadow-lg shadow-teal/30 relative z-10">4</div>
        <h3 class="mt-5 font-display font-bold text-lg text-navy">Garantía y seguimiento</h3>
        <p class="mt-2 text-sm text-slate-600 leading-relaxed">Te entregamos garantía por escrito y programamos tus mantenimientos para que tu equipo rinda por años.</p>
      </div>
    </div>
  </div>
</section>

<!-- ======================= TESTIMONIOS ======================= -->
<section class="py-24 bg-ice">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="text-center max-w-2xl mx-auto reveal">
      <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Lo que dicen nuestros clientes</div>
      <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl text-navy tracking-tight leading-tight">Confianza construida instalación por instalación.</h2>
    </div>
    <div class="mt-14 grid md:grid-cols-3 gap-6">
      <div class="card reveal rounded-3xl bg-white border border-slate-100 p-8 shadow-soft">
        <div class="flex gap-1 text-amber-400">
          <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg>
        </div>
        <p class="mt-4 text-slate-700 leading-relaxed">"Instalaron tres minisplits en casa en una sola mañana. Todo quedó limpio, ordenado y me explicaron cómo usar la app. Muy profesionales."</p>
        <div class="mt-6 flex items-center gap-3">
          <div class="w-10 h-10 rounded-full bg-brand-100 text-brand-800 font-bold flex items-center justify-center">MG</div>
          <div><div class="font-semibold text-navy text-sm">Mariana G.</div><div class="text-xs text-slate-500">Juriquilla, Querétaro</div></div>
        </div>
      </div>
      <div class="card reveal reveal-delay-1 rounded-3xl bg-white border border-slate-100 p-8 shadow-soft">
        <div class="flex gap-1 text-amber-400">
          <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg>
        </div>
        <p class="mt-4 text-slate-700 leading-relaxed">"Llevamos 4 años con su póliza de mantenimiento en nuestras oficinas. Cero paros, siempre puntuales y con reportes claros de cada visita."</p>
        <div class="mt-6 flex items-center gap-3">
          <div class="w-10 h-10 rounded-full bg-brand-100 text-brand-800 font-bold flex items-center justify-center">RL</div>
          <div><div class="font-semibold text-navy text-sm">Ing. Roberto L.</div><div class="text-xs text-slate-500">Corporativo · Centro Sur</div></div>
        </div>
      </div>
      <div class="card reveal reveal-delay-2 rounded-3xl bg-white border border-slate-100 p-8 shadow-soft">
        <div class="flex gap-1 text-amber-400">
          <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg><svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path d="M10 15.27L16.18 19l-1.64-7.03L20 7.24l-7.19-.61L10 0 7.19 6.63 0 7.24l5.46 4.73L3.82 19z"/></svg>
        </div>
        <p class="mt-4 text-slate-700 leading-relaxed">"Nos diseñaron el sistema VRF completo del hotel. Cumplieron tiempos de obra y el ahorro en luz frente al sistema anterior fue notable."</p>
        <div class="mt-6 flex items-center gap-3">
          <div class="w-10 h-10 rounded-full bg-brand-100 text-brand-800 font-bold flex items-center justify-center">AC</div>
          <div><div class="font-semibold text-navy text-sm">Arq. Alejandra C.</div><div class="text-xs text-slate-500">Hotel boutique · Centro Histórico</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= CTA BANNER ======================= -->
<section class="py-16 bg-white">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="reveal relative rounded-[2rem] overflow-hidden hero-bg text-white p-10 sm:p-14">
      <div class="absolute inset-0 grid-lines"></div>
      <div class="relative grid lg:grid-cols-2 gap-8 items-center">
        <div>
          <h2 class="font-display font-extrabold text-3xl sm:text-4xl tracking-tight leading-tight">¿Listo para respirar aire fresco? <span class="grad-text">Cotiza hoy mismo.</span></h2>
          <p class="mt-4 text-brand-100/85 text-lg">Respuesta en minutos por WhatsApp. Visita técnica sin costo en Querétaro y zona metropolitana.</p>
        </div>
        <div class="flex flex-col sm:flex-row lg:justify-end gap-4">
          <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20quiero%20una%20cotizaci%C3%B3n." target="_blank" rel="noopener" class="inline-flex justify-center items-center gap-2.5 rounded-full bg-wa text-white font-semibold px-7 py-4 hover:brightness-110 hover:-translate-y-0.5 transition-all shadow-xl shadow-wa/30">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="currentColor"><path d="M20.52 3.48A11.86 11.86 0 0012.06 0C5.5 0 .16 5.34.16 11.9c0 2.1.55 4.14 1.6 5.95L0 24l6.32-1.66a11.9 11.9 0 005.74 1.46c6.56 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.44-8.42zM12.06 21.8a9.9 9.9 0 01-5.04-1.38l-.36-.21-3.75.98 1-3.65-.24-.38a9.87 9.87 0 01-1.51-5.26c0-5.45 4.44-9.89 9.9-9.89 2.64 0 5.13 1.03 7 2.9a9.83 9.83 0 012.9 7c0 5.45-4.44 9.89-9.9 9.89zm5.43-7.4c-.3-.15-1.76-.87-2.03-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.64.07-.3-.15-1.26-.46-2.4-1.48-.88-.79-1.48-1.76-1.65-2.06-.17-.3-.02-.46.13-.6.13-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.6-.91-2.2-.24-.58-.49-.5-.67-.5h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.01-1.04 2.47s1.06 2.87 1.21 3.07c.15.2 2.1 3.2 5.08 4.48.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.76-.72 2.01-1.41.25-.7.25-1.29.17-1.41-.07-.13-.27-.2-.57-.35z"/></svg>
            WhatsApp
          </a>
          <a href="tel:+524422219667" class="inline-flex justify-center items-center gap-2.5 rounded-full bg-white text-navy font-semibold px-7 py-4 hover:bg-brand-50 transition-all">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
            Llamar ahora
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= CONTACTO ======================= -->
<section id="contacto" class="py-24 bg-ice">
  <div class="max-w-7xl mx-auto px-5 sm:px-8">
    <div class="grid lg:grid-cols-5 gap-12">
      <div class="lg:col-span-2 reveal">
        <div class="text-xs font-bold uppercase tracking-[0.2em] text-brand-600">Contacto</div>
        <h2 class="mt-3 font-display font-extrabold text-3xl sm:text-4xl text-navy tracking-tight leading-tight">Hablemos de tu proyecto.</h2>
        <p class="mt-4 text-slate-600 text-lg">Elige el canal que prefieras. Estamos disponibles de lunes a sábado para atenderte con rapidez.</p>

        <div class="mt-8 space-y-4">
          <a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20me%20gustar%C3%ADa%20recibir%20informaci%C3%B3n." target="_blank" rel="noopener" class="card flex items-center gap-4 rounded-2xl bg-white border border-slate-200 p-5 group">
            <div class="w-12 h-12 rounded-xl bg-wa/10 text-wa flex items-center justify-center shrink-0">
              <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M20.52 3.48A11.86 11.86 0 0012.06 0C5.5 0 .16 5.34.16 11.9c0 2.1.55 4.14 1.6 5.95L0 24l6.32-1.66a11.9 11.9 0 005.74 1.46c6.56 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.44-8.42zM12.06 21.8a9.9 9.9 0 01-5.04-1.38l-.36-.21-3.75.98 1-3.65-.24-.38a9.87 9.87 0 01-1.51-5.26c0-5.45 4.44-9.89 9.9-9.89 2.64 0 5.13 1.03 7 2.9a9.83 9.83 0 012.9 7c0 5.45-4.44 9.89-9.9 9.89zm5.43-7.4c-.3-.15-1.76-.87-2.03-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.64.07-.3-.15-1.26-.46-2.4-1.48-.88-.79-1.48-1.76-1.65-2.06-.17-.3-.02-.46.13-.6.13-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.6-.91-2.2-.24-.58-.49-.5-.67-.5h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.01-1.04 2.47s1.06 2.87 1.21 3.07c.15.2 2.1 3.2 5.08 4.48.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.76-.72 2.01-1.41.25-.7.25-1.29.17-1.41-.07-.13-.27-.2-.57-.35z"/></svg>
            </div>
            <div class="flex-1">
              <div class="text-xs text-slate-500 font-medium">WhatsApp</div>
              <div class="font-display font-bold text-navy">+52 442 000 0000</div>
            </div>
            <svg class="w-5 h-5 text-slate-300 group-hover:text-brand-500 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
          </a>
          <a href="tel:+524422219667" class="card flex items-center gap-4 rounded-2xl bg-white border border-slate-200 p-5 group">
            <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center shrink-0">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
            </div>
            <div class="flex-1">
              <div class="text-xs text-slate-500 font-medium">Teléfono</div>
              <div class="font-display font-bold text-navy">(442) 000 0000</div>
            </div>
            <svg class="w-5 h-5 text-slate-300 group-hover:text-brand-500 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
          </a>
          <a href="mailto:sheldaingenieria@gmail.com?subject=Cotizaci%C3%B3n%20aire%20acondicionado" class="card flex items-center gap-4 rounded-2xl bg-white border border-slate-200 p-5 group">
            <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center shrink-0">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75"/></svg>
            </div>
            <div class="flex-1">
              <div class="text-xs text-slate-500 font-medium">Correo electrónico</div>
              <div class="font-display font-bold text-navy">sheldaingenieria@gmail.com</div>
            </div>
            <svg class="w-5 h-5 text-slate-300 group-hover:text-brand-500 group-hover:translate-x-1 transition-all" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
          </a>
          <div class="flex items-start gap-4 rounded-2xl bg-white border border-slate-200 p-5">
            <div class="w-12 h-12 rounded-xl bg-brand-50 text-brand-700 flex items-center justify-center shrink-0">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"/></svg>
            </div>
            <div>
              <div class="text-xs text-slate-500 font-medium">Cobertura</div>
              <div class="font-display font-bold text-navy">Querétaro, Qro. y zona metropolitana</div>
              <div class="text-sm text-slate-600 mt-1">Lun – Vie 9:00 – 18:00 · Sáb 9:00 – 14:00</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Form -->
      <div class="lg:col-span-3 reveal reveal-delay-1">
        <div class="rounded-3xl bg-white border border-slate-100 shadow-soft p-7 sm:p-10">
          <h3 class="font-display font-bold text-2xl text-navy">Solicita tu cotización</h3>
          <p class="mt-2 text-slate-600 text-sm">Completa el formulario y te contactaremos por WhatsApp con una propuesta personalizada.</p>
          <form id="quoteForm" class="mt-8 grid sm:grid-cols-2 gap-5">
            <div>
              <label class="block text-sm font-semibold text-navy mb-1.5" for="nombre">Nombre</label>
              <input id="nombre" name="nombre" type="text" required placeholder="Tu nombre" class="w-full rounded-xl border border-slate-200 bg-ice px-4 py-3 text-sm transition-all">
            </div>
            <div>
              <label class="block text-sm font-semibold text-navy mb-1.5" for="telefono">Teléfono</label>
              <input id="telefono" name="telefono" type="tel" required placeholder="442 000 0000" class="w-full rounded-xl border border-slate-200 bg-ice px-4 py-3 text-sm transition-all">
            </div>
            <div>
              <label class="block text-sm font-semibold text-navy mb-1.5" for="servicio">Servicio</label>
              <select id="servicio" name="servicio" class="w-full rounded-xl border border-slate-200 bg-ice px-4 py-3 text-sm transition-all">
                <option>Venta e instalación</option>
                <option>Solo instalación</option>
                <option>Mantenimiento preventivo</option>
                <option>Reparación / servicio correctivo</option>
                <option>Proyecto comercial / industrial</option>
              </select>
            </div>
            <div>
              <label class="block text-sm font-semibold text-navy mb-1.5" for="equipo">Tipo de equipo</label>
              <select id="equipo" name="equipo" class="w-full rounded-xl border border-slate-200 bg-ice px-4 py-3 text-sm transition-all">
                <option>Minisplit</option>
                <option>Fan & Coil</option>
                <option>Sistema dividido</option>
                <option>Piso Techo</option>
                <option>Unidad Paquete</option>
                <option>Chiller</option>
                <option>VRF</option>
                <option>No estoy seguro / necesito asesoría</option>
              </select>
            </div>
            <div class="sm:col-span-2">
              <label class="block text-sm font-semibold text-navy mb-1.5" for="mensaje">Cuéntanos sobre tu espacio</label>
              <textarea id="mensaje" name="mensaje" rows="4" placeholder="Ej. Sala de 25 m² con ventanas al poniente, planta alta, en Juriquilla..." class="w-full rounded-xl border border-slate-200 bg-ice px-4 py-3 text-sm transition-all resize-none"></textarea>
            </div>
            <div class="sm:col-span-2 flex flex-col sm:flex-row sm:items-center gap-4 justify-between">
              <p class="text-xs text-slate-500">Al enviar, se abrirá WhatsApp con tu solicitud lista para mandar.</p>
              <button type="submit" class="inline-flex justify-center items-center gap-2.5 rounded-full bg-gradient-to-r from-brand-600 to-brand-500 text-white font-semibold px-7 py-3.5 hover:shadow-glow hover:-translate-y-0.5 transition-all">
                Enviar solicitud
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5"/></svg>
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ======================= FOOTER ======================= -->
<footer class="bg-navy text-white">
  <div class="max-w-7xl mx-auto px-5 sm:px-8 py-16">
    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-10">
      <div class="lg:col-span-2">
        <div class="flex items-center gap-3">
          <div class="w-11 h-11 rounded-xl bg-gradient-to-br from-brand-500 to-teal flex items-center justify-center">
            <svg viewBox="0 0 24 24" class="w-6 h-6 text-white" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M4.9 6.5l14.2 11M19.1 6.5 4.9 17.5"/><path d="M12 2l-2.5 2.5M12 2l2.5 2.5M12 22l-2.5-2.5M12 22l2.5-2.5"/></svg>
          </div>
          <div class="leading-tight">
            <div class="font-display font-extrabold text-2xl tracking-tight">SHELDA</div>
            <div class="text-[11px] uppercase tracking-[0.18em] text-brand-200">Climatización · Querétaro</div>
          </div>
        </div>
        <p class="mt-5 text-brand-100/70 max-w-md leading-relaxed">Distribuidor autorizado GREE con 12 años de experiencia en venta, instalación y mantenimiento de sistemas de aire acondicionado para hogares, negocios e industria en Querétaro.</p>
        <div class="mt-6 inline-flex items-center gap-2 rounded-full border border-white/10 bg-white/5 px-4 py-2 text-xs font-semibold">
          <svg class="w-4 h-4 text-teal" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75m-3-7.036A11.959 11.959 0 013.598 6 11.99 11.99 0 003 9.749c0 5.592 3.824 10.29 9 11.623 5.176-1.332 9-6.03 9-11.622 0-1.31-.21-2.571-.598-3.751h-.152c-3.196 0-6.1-1.248-8.25-3.285z"/></svg>
          Distribuidor Autorizado GREE
        </div>
      </div>
      <div>
        <h4 class="font-display font-bold text-sm uppercase tracking-wider text-brand-200">Navegación</h4>
        <ul class="mt-5 space-y-3 text-sm text-brand-100/80">
          <li><a href="#servicios" class="hover:text-white transition-colors">Servicios</a></li>
          <li><a href="#equipos" class="hover:text-white transition-colors">Equipos</a></li>
          <li><a href="#nosotros" class="hover:text-white transition-colors">Nosotros</a></li>
          <li><a href="#proceso" class="hover:text-white transition-colors">Proceso</a></li>
          <li><a href="#contacto" class="hover:text-white transition-colors">Contacto</a></li>
        </ul>
      </div>
      <div>
        <h4 class="font-display font-bold text-sm uppercase tracking-wider text-brand-200">Contacto</h4>
        <ul class="mt-5 space-y-3 text-sm text-brand-100/80">
          <li><a href="https://wa.me/524422219667" target="_blank" rel="noopener" class="hover:text-white transition-colors flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-wa"></span>WhatsApp: +52 442 000 0000</a></li>
          <li><a href="tel:+524422219667" class="hover:text-white transition-colors flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-brand-400"></span>Tel: (442) 000 0000</a></li>
          <li><a href="mailto:sheldaingenieria@gmail.com" class="hover:text-white transition-colors flex items-center gap-2"><span class="w-1.5 h-1.5 rounded-full bg-brand-400"></span>sheldaingenieria@gmail.com</a></li>
          <li class="flex items-start gap-2"><span class="w-1.5 h-1.5 rounded-full bg-brand-400 mt-1.5"></span>Querétaro, Qro., México</li>
        </ul>
      </div>
    </div>
    <div class="mt-14 pt-8 border-t border-white/10 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-brand-100/60">
      <div>© <span id="year"></span> SHELDA Climatización. Todos los derechos reservados.</div>
      <div>GREE es una marca registrada de su respectivo propietario. Sitio de demostración.</div>
    </div>
  </div>
</footer>

<!-- ======================= FLOATING WHATSAPP ======================= -->
<a href="https://wa.me/524422219667?text=Hola%20SHELDA%2C%20me%20interesa%20informaci%C3%B3n%20sobre%20aire%20acondicionado." target="_blank" rel="noopener" aria-label="Contactar por WhatsApp" class="pulse-ring fixed bottom-6 right-6 z-50 w-16 h-16 rounded-full bg-wa text-white flex items-center justify-center shadow-2xl shadow-wa/40 hover:scale-110 transition-transform">
  <svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor"><path d="M20.52 3.48A11.86 11.86 0 0012.06 0C5.5 0 .16 5.34.16 11.9c0 2.1.55 4.14 1.6 5.95L0 24l6.32-1.66a11.9 11.9 0 005.74 1.46c6.56 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.44-8.42zM12.06 21.8a9.9 9.9 0 01-5.04-1.38l-.36-.21-3.75.98 1-3.65-.24-.38a9.87 9.87 0 01-1.51-5.26c0-5.45 4.44-9.89 9.9-9.89 2.64 0 5.13 1.03 7 2.9a9.83 9.83 0 012.9 7c0 5.45-4.44 9.89-9.9 9.89zm5.43-7.4c-.3-.15-1.76-.87-2.03-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.94 1.17-.17.2-.35.22-.64.07-.3-.15-1.26-.46-2.4-1.48-.88-.79-1.48-1.76-1.65-2.06-.17-.3-.02-.46.13-.6.13-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.6-.91-2.2-.24-.58-.49-.5-.67-.5h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.01-1.04 2.47s1.06 2.87 1.21 3.07c.15.2 2.1 3.2 5.08 4.48.71.31 1.26.49 1.69.63.71.23 1.36.2 1.87.12.57-.08 1.76-.72 2.01-1.41.25-.7.25-1.29.17-1.41-.07-.13-.27-.2-.57-.35z"/></svg>
</a>

<script>
  // Year
  document.getElementById('year').textContent = new Date().getFullYear();

  // Navbar scroll state
  const nav = document.getElementById('nav');
  const onScroll = () => nav.classList.toggle('scrolled', window.scrollY > 40);
  onScroll();
  window.addEventListener('scroll', onScroll, { passive: true });

  // Mobile menu
  const burger = document.getElementById('burger');
  const mobileMenu = document.getElementById('mobileMenu');
  const spans = burger.querySelectorAll('span');
  let open = false;
  const setMenu = (state) => {
    open = state;
    mobileMenu.classList.toggle('hidden', !open);
    if (open) nav.classList.add('scrolled');
    else onScroll();
    spans[0].style.transform = open ? 'translateY(8px) rotate(45deg)' : '';
    spans[1].style.opacity = open ? '0' : '1';
    spans[2].style.transform = open ? 'translateY(-8px) rotate(-45deg)' : '';
  };
  burger.addEventListener('click', () => setMenu(!open));
  document.querySelectorAll('.mob-link').forEach(a => a.addEventListener('click', () => setMenu(false)));

  // Reveal on scroll
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in'); io.unobserve(e.target); } });
  }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });
  document.querySelectorAll('.reveal').forEach(el => io.observe(el));

  // Counters
  const counters = document.querySelectorAll('.counter');
  const animateCounter = (el) => {
    const target = +el.dataset.target;
    const duration = 1600;
    const start = performance.now();
    const step = (now) => {
      const p = Math.min((now - start) / duration, 1);
      const eased = 1 - Math.pow(1 - p, 3);
      el.textContent = Math.floor(eased * target).toLocaleString('es-MX');
      if (p < 1) requestAnimationFrame(step);
    };
    requestAnimationFrame(step);
  };
  const cio = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { animateCounter(e.target); cio.unobserve(e.target); } });
  }, { threshold: 0.5 });
  counters.forEach(c => cio.observe(c));

  // Form -> WhatsApp
  document.getElementById('quoteForm').addEventListener('submit', (e) => {
    e.preventDefault();
    const f = e.target;
    const msg =
`Hola SHELDA, quiero una cotización.
• Nombre: ${f.nombre.value.trim()}
• Teléfono: ${f.telefono.value.trim()}
• Servicio: ${f.servicio.value}
• Equipo: ${f.equipo.value}
• Detalles: ${f.mensaje.value.trim() || 'Sin detalles adicionales'}`;
    window.open('https://wa.me/524422219667?text=' + encodeURIComponent(msg), '_blank', 'noopener');
  });

  // Smooth offset for anchors (account for fixed nav)
  document.querySelectorAll('a[href^="#"]').forEach(a => {
    a.addEventListener('click', (e) => {
      const id = a.getAttribute('href');
      if (id.length > 1) {
        const target = document.querySelector(id);
        if (target) {
          e.preventDefault();
          const y = target.getBoundingClientRect().top + window.scrollY - 72;
          window.scrollTo({ top: y, behavior: 'smooth' });
        }
      }
    });
  });
</script>
</body>
</html>
