<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Solução moderna e responsiva para pequenas e médias empresas. Serviços, depoimentos e contato em uma única página." />
  <title>Empresa XYZ — Soluções para seu Negócio</title>

  <!-- SEO básico -->
  <link rel="canonical" href="https://www.seudominio.com/" />
  <meta property="og:title" content="Empresa XYZ — Soluções para seu Negócio" />
  <meta property="og:description" content="Atendemos micro, pequenas e médias empresas com soluções sob medida." />
  <meta property="og:type" content="website" />
  <meta property="og:locale" content="pt_BR" />

  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <!-- Skip link para acessibilidade -->
  <a class="skip-link" href="#home">Pular para o conteúdo</a>

  <!-- Header + Navigation -->
  <header class="header" role="banner">
    <div class="container header__inner">
      <a class="logo" href="#home" aria-label="Ir para início">
        <img src="logo.svg" alt="Logo da Empresa" height="32" />
        <span class="logo__text">Empresa XYZ</span>
      </a>

      <button class="nav-toggle" aria-expanded="false" aria-controls="nav" aria-label="Abrir menu">
        <span class="nav-toggle__bar"></span>
        <span class="nav-toggle__bar"></span>
        <span class="nav-toggle__bar"></span>
      </button>

      <nav id="nav" class="nav" role="navigation" aria-label="Navegação principal">
        <ul class="nav__list">
          <li><a class="nav__link" href="#home">Home</a></li>
          <li><a class="nav__link" href="#sobre">Sobre</a></li>
          <li><a class="nav__link" href="#servicos">Serviços</a></li>
          <li><a class="nav__link" href="#depoimentos">Depoimentos</a></li>
          <li><a class="nav__link" href="#contato">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Home -->
  <main id="home" class="section section--hero" tabindex="-1">
    <div class="container hero__grid">
      <div class="hero__content">
        <h1 class="hero__title">Soluções que impulsionam o seu negócio</h1>
        <p class="hero__subtitle">Atendemos micro, pequenas e médias empresas com estratégia, tecnologia e resultados reais.</p>
        <div class="hero__cta">
          <a class="btn btn--primary" href="#servicos">Conheça nossos serviços</a>
          <a class="btn btn--outline" href="#contato">Solicite um orçamento</a>
        </div>
      </div>
      <figure class="hero__media" aria-label="Imagem ilustrativa de negócios">
        <img src="hero.jpg" alt="Equipe colaborando em escritório" loading="lazy" />
      </figure>
    </div>
  </main>

  <!-- Sobre -->
  <section id="sobre" class="section section--alt">
    <div class="container">
      <header class="section__header">
        <h2>Sobre nós</h2>
        <p>Somos especialistas em soluções acessíveis e escaláveis, adaptadas à realidade de cada cliente.</p>
      </header>

      <div class="grid grid--3">
        <article class="card">
          <h3>Missão</h3>
          <p>Entregar valor com simplicidade e eficiência.</p>
        </article>
        <article class="card">
          <h3>Visão</h3>
          <p>Ser referência em resultados para PMEs.</p>
        </article>
        <article class="card">
          <h3>Valores</h3>
          <ul>
            <li>Transparência</li>
            <li>Parceria</li>
            <li>Inovação</li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <!-- Serviços -->
  <section id="servicos" class="section">
    <div class="container">
      <header class="section__header">
        <h2>Serviços</h2>
        <p>Escolha o que mais combina com a sua necessidade.</p>
      </header>

      <div class="grid grid--3">
        <article class="card service">
          <h3>Consultoria</h3>
          <p>Diagnóstico e plano de ação sob medida.</p>
          <ul class="list-check">
            <li>Mapeamento de processos</li>
            <li>KPIs e OKRs</li>
            <li>Treinamentos</li>
          </ul>
        </article>

        <article class="card service">
          <h3>Marketing Digital</h3>
          <p>Atração e conversão de clientes.</p>
          <ul class="list-check">
            <li>Gestão de mídias</li>
            <li>Landing pages</li>
            <li>Automação de emails</li>
          </ul>
        </article>

        <article class="card service">
          <h3>Tecnologia</h3>
          <p>Sites, integrações e automações.</p>
          <ul class="list-check">
            <li>Desenvolvimento web</li>
            <li>Integração de sistemas</li>
            <li>RPA leve</li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <!-- Depoimentos -->
  <section id="depoimentos" class="section section--alt">
    <div class="container">
      <header class="section__header">
        <h2>Depoimentos</h2>
        <p>O que nossos clientes dizem</p>
      </header>

      <div class="carousel" aria-roledescription="carousel" aria-label="Depoimentos de clientes">
        <button class="carousel__btn carousel__btn--prev" aria-label="Anterior">❮</button>
        <div class="carousel__viewport" tabindex="0">
          <div class="carousel__track">
            <figure class="testimonial">
              <blockquote>“Aumentamos em 35% nossas vendas em 3 meses.”</blockquote>
              <figcaption>— Ana, Loja Local</figcaption>
            </figure>
            <figure class="testimonial">
              <blockquote>“Execução ágil e suporte impecável.”</blockquote>
              <figcaption>— Carlos, Oficina Mecânica</figcaption>
            </figure>
            <figure class="testimonial">
              <blockquote>“Finalmente um site que converte de verdade.”</blockquote>
              <figcaption>— Juliana, Clínica</figcaption>
            </figure>
          </div>
        </div>
        <button class="carousel__btn carousel__btn--next" aria-label="Próximo">❯</button>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="section">
    <div class="container">
      <header class="section__header">
        <h2>Fale conosco</h2>
        <p>Responderemos em até 1 dia útil.</p>
      </header>

      <form id="contactForm" class="form" novalidate>
        <div class="form__row">
          <label for="nome">Nome</label>
          <input id="nome" name="nome" type="text" autocomplete="name" required />
          <small class="error" aria-live="polite"></small>
        </div>

        <div class="form__row">
          <label for="email">E-mail</label>
          <input id="email" name="email" type="email" autocomplete="email" required />
          <small class="error" aria-live="polite"></small>
        </div>

        <div class="form__row">
          <label for="assunto">Assunto</label>
          <input id="assunto" name="assunto" type="text" required />
          <small class="error" aria-live="polite"></small>
        </div>

        <div class="form__row">
          <label for="mensagem">Mensagem</label>
          <textarea id="mensagem" name="mensagem" rows="4" required></textarea>
          <small class="error" aria-live="polite"></small>
        </div>

        <button type="submit" class="btn btn--primary">Enviar</button>
        <p id="formStatus" role="status" class="form__status" aria-live="polite"></p>
      </form>
    </div>
  </section>

  <!-- Footer (xxx e yyy) -->
  <footer class="footer" role="contentinfo">
    <div class="container footer__grid">
      <div class="footer__brand">
        <a class="logo" href="#home"><img src="logo.svg" alt="" height="24" /> <span>Empresa XYZ</span></a>
        <p class="footer__copy">© <span id="year"></span> Empresa XYZ. Todos os direitos reservados.</p>
      </div>

      <!-- xxx: horários de atendimento dinâmicos -->
      <div class="footer__hours">
        <h3>Horário de atendimento</h3>
        <p>Seg–Sex: 09h–18h • Sáb: 09h–13h</p>
        <p>Status: <strong id="openStatus" aria-live="polite">—</strong></p>
      </div>

      <!-- yyy: newsletter + voltar ao topo -->
      <div class="footer__actions">
        <form id="newsletterForm" class="newsletter" novalidate>
          <label for="newsletterEmail">Receba novidades</label>
          <div class="newsletter__controls">
            <input id="newsletterEmail" type="email" placeholder="seu@email.com" required />
            <button class="btn btn--secondary" type="submit">Inscrever</button>
          </div>
          <small class="error" aria-live="polite"></small>
          <p id="newsletterStatus" role="status" class="form__status" aria-live="polite"></p>
        </form>

        <button class="btn btn--ghost" id="backToTop" aria-label="Voltar ao topo">↑ Topo</button>
      </div>
    </div>
  </footer>

  <script src="app.js" defer></script>
</body>
</html>

:root{
  --bg: #0b0e14;
  --bg-alt: #121826;
  --surface: #1f2430;
  --text: #e6e6e6;
  --muted: #a9b1c0;
  --primary: #3b82f6;
  --primary-600:#2563eb;
  --accent: #22c55e;
  --danger: #ef4444;
  --radius: 12px;
  --shadow: 0 10px 30px rgba(0,0,0,.25);
  --container: 1120px;
}

*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0; font-family:system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Arial, sans-serif;
  color:var(--text); background:linear-gradient(180deg,var(--bg),var(--bg-alt));
}

/* Acessibilidade */
.skip-link{
  position:absolute; left:-999px; top:auto; width:1px; height:1px; overflow:hidden;
}
.skip-link:focus{left:1rem; top:1rem; width:auto; height:auto; background:#000; color:#fff; padding:.5rem 1rem; z-index:1000;}

/* Layout utilitários */
.container{max-width:var(--container); margin:0 auto; padding:0 1rem}
.section{padding:64px 0}
.section--alt{background:rgba(255,255,255,.03)}
.section__header{margin-bottom:24px}
.section__header h2{margin:0 0 8px}
.grid{display:grid; gap:16px}
.grid--3{grid-template-columns:repeat(3,minmax(0,1fr))}
@media (max-width: 960px){
  .grid--3{grid-template-columns:1fr 1fr}
}
@media (max-width: 640px){
  .grid--3{grid-template-columns:1fr}
}

/* Header / Nav */
.header{
  position:sticky; top:0; z-index:100; background:rgba(15,18,28,.7); backdrop-filter:saturate(180%) blur(10px);
  border-bottom:1px solid rgba(255,255,255,.06);
}
.header__inner{display:flex; align-items:center; justify-content:space-between; height:64px}
.logo{display:flex; align-items:center; gap:.5rem; color:var(--text); text-decoration:none; font-weight:700}
.nav{display:flex}
.nav__list{display:flex; list-style:none; gap:1rem; margin:0; padding:0}
.nav__link{color:var(--muted); text-decoration:none; padding:.5rem .75rem; border-radius:8px}
.nav__link:hover,.nav__link.is-active{color:#fff; background:rgba(255,255,255,.08)}
.nav-toggle{display:none; background:none; border:0; cursor:pointer}
.nav-toggle__bar{display:block; width:24px; height:2px; background:#fff; margin:5px 0}
@media (max-width: 840px){
  .nav{position:absolute; top:64px; right:0; background:var(--bg-alt); width:100%; transform:translateY(-120%); transition:.25s; border-bottom:1px solid rgba(255,255,255,.06)}
  .nav[aria-expanded="true"]{transform:translateY(0)}
  .nav__list{flex-direction:column; padding:1rem}
  .nav-toggle{display:block}
}

/* Hero */
.section--hero{padding:96px 0 64px}
.hero__grid{display:grid; gap:24px; grid-template-columns:1.2fr .8fr; align-items:center}
.hero__title{font-size:clamp(1.8rem, 2.5vw, 3rem); margin:0 0 8px}
.hero__subtitle{color:var(--muted); margin:0 0 24px}
.hero__cta{display:flex; gap:12px; flex-wrap:wrap}
.hero__media img{width:100%; height:auto; border-radius:var(--radius); box-shadow:var(--shadow)}
@media (max-width: 960px){
  .hero__grid{grid-template-columns:1fr}
}

/* Cards / Serviços */
.card{
  background:var(--surface); border:1px solid rgba(255,255,255,.06);
  border-radius:var(--radius); padding:20px; box-shadow:var(--shadow)
}
.service h3{margin-top:0}
.list-check{padding-left:1.1rem}
.list-check li{margin:.25rem 0;}

/* Carrossel */
.carousel{position:relative}
.carousel__viewport{
  overflow:hidden; border-radius:var(--radius); outline:0; background:var(--surface); border:1px solid rgba(255,255,255,.06)
}
.carousel__track{display:flex; transition:transform .3s ease}
.testimonial{min-width:100%; margin:0; padding:24px}
.testimonial blockquote{font-size:1.1rem; margin:0 0 8px}
.carousel__btn{
  position:absolute; top:50%; transform:translateY(-50%); background:rgba(0,0,0,.5); color:#fff;
  border:0; width:40px; height:40px; border-radius:50%; cursor:pointer
}
.carousel__btn--prev{left:8px}
.carousel__btn--next{right:8px}

/* Formulários */
.form{max-width:720px}
.form__row{display:flex; flex-direction:column; gap:.25rem; margin-bottom:14px}
input, textarea{
  background:#0e1420; color:var(--text); border:1px solid rgba(255,255,255,.12); border-radius:10px; padding:.75rem .9rem;
}
input:focus, textarea:focus{outline:2px solid var(--primary)}
.error{color:var(--danger); min-height:1.1em}
.form__status{margin-top:8px; color:var(--accent)}

/* Footer */
.footer{padding:32px 0; background:#0a0f18; border-top:1px solid rgba(255,255,255,.06)}
.footer__grid{display:grid; gap:16px; grid-template-columns:2fr 1fr 1.5fr}
.footer__copy{color:var(--muted)}
@media (max-width: 840px){
  .footer__grid{grid-template-columns:1fr}
}

/* Botões */
.btn{
  display:inline-flex; align-items:center; justify-content:center; gap:.5rem;
  padding:.75rem 1rem; border-radius:10px; border:1px solid transparent; cursor:pointer; text-decoration:none; font-weight:600;
}
.btn--primary{background:var(--primary); color:#fff}
.btn--primary:hover{background:var(--primary-600)}
.btn--outline{background:transparent; color:#fff; border-color:rgba(255,255,255,.2)}
.btn--secondary{background:var(--accent); color:#0a0f18}
.btn--ghost{background:transparent; color:#fff; border-color:rgba(255,255,255,.2)}

/* Utilitários */
[hidden]{display:none !important}

// ===== Navegação: menu mobile e rolagem suave =====
const navToggle = document.querySelector('.nav-toggle');
const nav = document.getElementById('nav');
const navLinks = document.querySelectorAll('.nav__link');

function setNavExpanded(expanded){
  nav.setAttribute('aria-expanded', expanded);
  navToggle.setAttribute('aria-expanded', expanded);
}
if(navToggle){
  navToggle.addEventListener('click', () => {
    const expanded = nav.getAttribute('aria-expanded') === 'true';
    setNavExpanded(!expanded);
  });
}
navLinks.forEach(link => {
  link.addEventListener('click', e => {
    // Rolagem suave
    const targetId = link.getAttribute('href');
    if(targetId.startsWith('#')){
      e.preventDefault();
      const target = document.querySelector(targetId);
      if(target){
        target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        setNavExpanded(false);
      }
    }
  });
});

// ===== Scroll spy: ativa link conforme seção visível =====
const sections = document.querySelectorAll('main.section, section.section');
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    const id = entry.target.getAttribute('id');
    if(id){
      const link = document.querySelector(`.nav__link[href="#${id}"]`);
      if(entry.isIntersecting){
        document.querySelectorAll('.nav__link').forEach(a => a.classList.remove('is-active'));
        if(link) link.classList.add('is-active');
      }
    }
  });
}, { rootMargin: '-40% 0px -55% 0px', threshold: 0.01 });

sections.forEach(sec => observer.observe(sec));

// ===== Carrossel simples (Depoimentos) =====
const track = document.querySelector('.carousel__track');
const btnPrev = document.querySelector('.carousel__btn--prev');
const btnNext = document.querySelector('.carousel__btn--next');
const viewport = document.querySelector('.carousel__viewport');

let index = 0;
function updateCarousel(){
  const width = viewport.clientWidth;
  track.style.transform = `translateX(-${index * width}px)`;
}
function next(){ index = Math.min(index + 1, track.children.length - 1); updateCarousel(); }
function prev(){ index = Math.max(index - 1, 0); updateCarousel(); }

window.addEventListener('resize', updateCarousel);
btnNext?.addEventListener('click', next);
btnPrev?.addEventListener('click', prev);
viewport?.addEventListener('keydown', (e) => {
  if(e.key === 'ArrowRight') next();
  if(e.key === 'ArrowLeft') prev();
});
updateCarousel();

// ===== Validação do formulário de contato =====
const contactForm = document.getElementById('contactForm');
const formStatus = document.getElementById('formStatus');

function setError(input, message){
  const small = input.parentElement.querySelector('.error');
  small.textContent = message || '';
  input.setAttribute('aria-invalid', message ? 'true' : 'false');
}
function validateEmail(email){
  return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);
}
contactForm?.addEventListener('submit', (e) => {
  e.preventDefault();
  formStatus.textContent = '';
  let valid = true;

  const nome = contactForm.nome;
  const email = contactForm.email;
  const assunto = contactForm.assunto;
  const mensagem = contactForm.mensagem;

  if(!nome.value.trim()){ setError(nome, 'Informe seu nome.'); valid = false; } else setError(nome);
  if(!validateEmail(email.value)){ setError(email, 'E-mail inválido.'); valid = false; } else setError(email);
  if(!assunto.value.trim()){ setError(assunto, 'Informe o assunto.'); valid = false; } else setError(assunto);
  if(!mensagem.value.trim()){ setError(mensagem, 'Escreva sua mensagem.'); valid = false; } else setError(mensagem);

  if(valid){
    // Aqui você pode integrar com backend (fetch/axios) ou serviços de email.
    formStatus.textContent = 'Mensagem enviada! (simulação)';
    contactForm.reset();
  }
});

// ===== Footer: ano dinâmico + aberto/fechado (xxx) =====
document.getElementById('year').textContent = new Date().getFullYear();

const openStatus = document.getElementById('openStatus');
function businessOpenNow(date = new Date()){
  // Exemplo de horário: Seg–Sex 09–18, Sáb 09–13, Dom fechado
  const day = date.getDay(); // 0=Dom ... 6=Sáb
  const hour = date.getHours();
  const isWeekday = day >= 1 && day <= 5;
  const isSaturday = day === 6;

  if(isWeekday) return hour >= 9 && hour < 18;
  if(isSaturday) return hour >= 9 && hour < 13;
  return false;
}
if(openStatus){
  const open = businessOpenNow();
  openStatus.textContent = open ? 'Aberto agora' : 'Fechado no momento';
  openStatus.style.color = open ? 'var(--accent)' : 'var(--danger)';
}

// ===== Newsletter + Voltar ao topo (yyy) =====
const newsletterForm = document.getElementById('newsletterForm');
const newsletterEmail = document.getElementById('newsletterEmail');
const newsletterStatus = document.getElementById('newsletterStatus');

newsletterForm?.addEventListener('submit', (e) => {
  e.preventDefault();
  if(!validateEmail(newsletterEmail.value)){
    const err = newsletterForm.querySelector('.error');
    err.textContent = 'Informe um e-mail válido.';
    return;
  }
  newsletterForm.querySelector('.error').textContent = '';
  newsletterStatus.textContent = 'Inscrição realizada! (simulação)';
  newsletterForm.reset();
});

const backToTop = document.getElementById('backToTop');
backToTop?.addEventListener('click', () => window.scrollTo({ top: 0, behavior: 'smooth' }));
``
