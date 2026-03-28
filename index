<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gabriele Winkel — Designer de Marca</title>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@200;300;400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --cream:#F7F2EC;--cream2:#EFE8DF;--cream3:#E6DDD2;
  --terra:#C4622D;--warm:#D4784A;--peach:#F0A07A;
  --sky-light:#C8DCE8;--sky-pale:#E8F2F7;
  --text:#3A2A1E;--text-muted:#7A6155;--text-dim:#A8958A;
  --sans:'Outfit',sans-serif;
}
html{scroll-behavior:smooth}
body{background:var(--cream);color:var(--text);font-family:var(--sans);font-weight:300;font-size:15px;line-height:1.7}
nav{position:fixed;top:0;left:0;right:0;z-index:100;background:rgba(247,242,236,0.92);backdrop-filter:blur(12px);border-bottom:1px solid rgba(196,98,45,0.12);display:flex;align-items:center;justify-content:space-between;padding:0 40px;height:60px}
.nav-logo{font-family:var(--sans);font-size:18px;font-weight:300;letter-spacing:0.18em;color:var(--terra);text-transform:uppercase}
.nav-links{display:flex;gap:32px;list-style:none}
.nav-links a{color:var(--text-muted);text-decoration:none;font-size:11px;letter-spacing:0.18em;text-transform:uppercase;font-weight:400;transition:color 0.2s}
.nav-links a:hover{color:var(--terra)}
section{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:100px 40px 60px;position:relative}
.section-inner{width:100%;max-width:900px}
#hero{text-align:center;background:radial-gradient(ellipse at 80% 20%,rgba(168,196,212,0.25) 0%,transparent 50%),radial-gradient(ellipse at 20% 80%,rgba(240,160,122,0.2) 0%,transparent 50%),radial-gradient(ellipse at 50% 50%,rgba(232,196,168,0.15) 0%,transparent 70%)}
.hero-eyebrow{font-size:11px;letter-spacing:0.3em;text-transform:uppercase;font-weight:400;color:var(--terra);margin-bottom:24px;display:flex;align-items:center;justify-content:center;gap:12px}
.hero-eyebrow::before,.hero-eyebrow::after{content:'';width:40px;height:1px;background:var(--peach);opacity:0.7}
.hero-name{font-family:var(--sans);font-size:clamp(48px,8vw,90px);font-weight:200;line-height:1.0;letter-spacing:0.06em;margin-bottom:8px;color:var(--terra);text-transform:uppercase}
.hero-subtitle{font-family:var(--sans);font-size:clamp(15px,2.5vw,22px);font-weight:300;color:var(--text-muted);margin-bottom:32px;letter-spacing:0.08em;text-transform:uppercase}
.hero-bio{max-width:520px;margin:0 auto 48px;font-size:16px;font-weight:300;color:var(--text-muted);line-height:1.8}
.hero-cta{display:inline-flex;gap:16px;flex-wrap:wrap;justify-content:center}
.btn-primary{background:var(--terra);color:var(--cream);padding:12px 32px;font-size:11px;letter-spacing:0.2em;text-transform:uppercase;font-weight:400;border:none;cursor:pointer;transition:all 0.2s;font-family:var(--sans);text-decoration:none;display:inline-block;border-radius:2px}
.btn-primary:hover{background:var(--warm)}
.btn-outline{border:1px solid rgba(196,98,45,0.4);color:var(--terra);padding:12px 32px;font-size:11px;letter-spacing:0.2em;text-transform:uppercase;font-weight:400;background:transparent;cursor:pointer;transition:all 0.2s;font-family:var(--sans);text-decoration:none;display:inline-block;border-radius:2px}
.btn-outline:hover{border-color:var(--terra);background:rgba(196,98,45,0.06)}
.scroll-hint{position:absolute;bottom:32px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:8px;color:var(--text-dim);font-size:10px;letter-spacing:0.25em;text-transform:uppercase;font-weight:400;animation:float 2s ease-in-out infinite}
.scroll-hint::after{content:'';width:1px;height:40px;background:linear-gradient(to bottom,var(--peach),transparent);opacity:0.6}
@keyframes float{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(6px)}}
.section-label{font-size:10px;letter-spacing:0.3em;text-transform:uppercase;font-weight:400;color:var(--terra);margin-bottom:16px;display:flex;align-items:center;gap:12px}
.section-label::after{content:'';height:1px;width:60px;background:var(--peach);opacity:0.6}
.section-title{font-family:var(--sans);font-size:clamp(32px,5vw,52px);font-weight:200;line-height:1.1;margin-bottom:48px;color:var(--text);letter-spacing:0.02em}
.section-title em{font-style:normal;font-weight:300;color:var(--terra)}
#sobre{background:linear-gradient(160deg,var(--sky-pale) 0%,var(--cream) 50%,var(--cream2) 100%)}
#sobre .section-inner{display:grid;grid-template-columns:1fr 1fr;gap:80px;align-items:center}
.sobre-quote{font-family:var(--sans);font-size:clamp(18px,2.2vw,24px);font-weight:300;line-height:1.6;color:var(--text);border-left:2px solid var(--peach);padding-left:28px;margin-bottom:32px}
.sobre-text{font-weight:300;color:var(--text-muted);line-height:1.9;margin-bottom:24px}
.stats-row{display:flex;gap:40px;margin-top:40px;padding-top:32px;border-top:1px solid rgba(196,98,45,0.12)}
.stat-number{font-family:var(--sans);font-size:40px;font-weight:200;color:var(--terra);line-height:1;margin-bottom:4px}
.stat-label{font-size:10px;font-weight:400;color:var(--text-dim);letter-spacing:0.15em;text-transform:uppercase}
.sobre-card{background:white;border:1px solid rgba(196,98,45,0.12);padding:40px;position:relative;box-shadow:0 4px 32px rgba(196,98,45,0.06)}
.sobre-card-text{font-family:var(--sans);font-size:17px;font-weight:300;color:var(--text-muted);line-height:1.7}
.sobre-tag{display:inline-block;background:var(--sky-pale);border:1px solid var(--sky-light);color:#4A7A90;font-size:10px;font-weight:400;padding:5px 14px;letter-spacing:0.12em;text-transform:uppercase;margin-top:20px;margin-right:8px;border-radius:20px}
#portfolio{background:var(--cream2)}
.portfolio-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:rgba(196,98,45,0.1)}
.portfolio-item{background:var(--cream2);padding:32px 28px;cursor:pointer;transition:background 0.2s;position:relative;min-height:180px;display:flex;flex-direction:column;justify-content:space-between;text-decoration:none}
.portfolio-item:hover{background:white}
.portfolio-item::after{content:'↗';position:absolute;top:24px;right:24px;color:var(--terra);opacity:0;font-size:16px;transition:opacity 0.2s}
.portfolio-item:hover::after{opacity:1}
.portfolio-index{font-size:10px;font-weight:400;color:var(--text-dim);letter-spacing:0.25em;margin-bottom:16px}
.portfolio-name{font-size:18px;font-weight:300;color:var(--text);margin-bottom:8px;line-height:1.2}
.portfolio-type{font-size:10px;font-weight:400;color:var(--terra);letter-spacing:0.15em;text-transform:uppercase}
.portfolio-bottom{display:flex;align-items:center;margin-top:20px;padding-top:16px;border-top:1px solid rgba(196,98,45,0.1)}
.portfolio-year{font-size:11px;font-weight:300;color:var(--text-dim)}
#servicos{background:radial-gradient(ellipse at 100% 0%,rgba(168,196,212,0.2) 0%,transparent 40%),radial-gradient(ellipse at 0% 100%,rgba(240,160,122,0.15) 0%,transparent 40%),var(--cream)}
.servicos-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1px;background:rgba(196,98,45,0.08)}
.servico-card{background:rgba(255,255,255,0.7);padding:44px 36px;position:relative;overflow:hidden;transition:background 0.3s}
.servico-card:hover{background:white}
.servico-card.featured{background:linear-gradient(135deg,rgba(240,160,122,0.12) 0%,rgba(255,255,255,0.9) 60%)}
.servico-number{font-family:var(--sans);font-size:56px;font-weight:200;color:rgba(196,98,45,0.07);line-height:1;position:absolute;top:20px;right:24px}
.servico-tag{font-size:10px;font-weight:400;letter-spacing:0.25em;text-transform:uppercase;color:var(--terra);margin-bottom:16px;display:block}
.servico-title{font-size:clamp(18px,2vw,22px);font-weight:300;line-height:1.3;margin-bottom:8px;color:var(--text)}
.servico-subtitle{font-size:12px;font-weight:300;color:var(--text-dim);margin-bottom:24px}
.servico-items{list-style:none;display:flex;flex-direction:column;gap:9px}
.servico-items li{font-size:13px;font-weight:300;color:var(--text-muted);display:flex;align-items:flex-start;gap:10px;line-height:1.5}
.servico-items li::before{content:'';width:4px;height:4px;border-radius:50%;background:var(--peach);margin-top:7px;flex-shrink:0}
.servico-divider{width:40px;height:1px;background:var(--peach);opacity:0.5;margin:20px 0}
#precos{background:var(--cream2)}
.precos-intro{max-width:560px;margin-bottom:56px;font-weight:300;color:var(--text-muted);font-size:16px;line-height:1.8}
.precos-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.preco-card{background:white;border:1px solid rgba(196,98,45,0.1);padding:32px 28px;position:relative;transition:all 0.2s;box-shadow:0 2px 16px rgba(196,98,45,0.04)}
.preco-card:hover{border-color:rgba(196,98,45,0.25);box-shadow:0 4px 24px rgba(196,98,45,0.08)}
.preco-card.destaque{border-color:rgba(196,98,45,0.25);background:linear-gradient(145deg,rgba(240,160,122,0.08) 0%,white 60%)}
.preco-badge{position:absolute;top:-1px;left:24px;background:var(--terra);color:var(--cream);font-size:9px;font-weight:400;letter-spacing:0.2em;text-transform:uppercase;padding:4px 12px;border-radius:0 0 2px 2px}
.preco-service{font-size:10px;font-weight:400;color:var(--terra);letter-spacing:0.2em;text-transform:uppercase;margin-bottom:10px}
.preco-name{font-size:20px;font-weight:300;margin-bottom:4px;color:var(--text);line-height:1.2}
.preco-desc{font-size:12px;font-weight:300;color:var(--text-dim);margin-bottom:24px}
.preco-valor{display:flex;align-items:baseline;gap:4px;margin-bottom:20px}
.preco-cifra{font-size:12px;font-weight:300;color:var(--text-muted);margin-bottom:2px}
.preco-numero{font-size:40px;font-weight:200;color:var(--terra);line-height:1}
.preco-periodo{font-size:12px;font-weight:300;color:var(--text-dim);align-self:flex-end;margin-bottom:3px}
.preco-items{list-style:none;border-top:1px solid rgba(196,98,45,0.08);padding-top:16px;display:flex;flex-direction:column;gap:7px}
.preco-items li{font-size:12px;font-weight:300;color:var(--text-muted);display:flex;align-items:flex-start;gap:8px}
.preco-items li::before{content:'—';color:var(--peach);font-size:10px;margin-top:2px;flex-shrink:0}
#contato{background:radial-gradient(ellipse at 30% 50%,rgba(168,196,212,0.2) 0%,transparent 50%),radial-gradient(ellipse at 70% 50%,rgba(240,160,122,0.15) 0%,transparent 50%),var(--cream);text-align:center}
.contato-text{font-size:16px;font-weight:300;color:var(--text-muted);max-width:480px;margin:0 auto 48px;line-height:1.8}
.contato-links{display:flex;gap:16px;justify-content:center;flex-wrap:wrap}
.footer-line{position:absolute;bottom:32px;left:50%;transform:translateX(-50%);font-size:11px;font-weight:300;color:var(--text-dim);letter-spacing:0.1em;white-space:nowrap}
.sky-accent{display:inline-block;background:var(--sky-pale);border:1px solid var(--sky-light);color:#4A7A90;font-size:10px;font-weight:400;padding:4px 14px;letter-spacing:0.12em;border-radius:20px;margin-bottom:16px;text-transform:uppercase}
@media(max-width:700px){nav{padding:0 20px}.nav-links{display:none}section{padding:80px 20px 60px}#sobre .section-inner{grid-template-columns:1fr;gap:40px}.portfolio-grid{grid-template-columns:1fr 1fr}.servicos-grid{grid-template-columns:1fr}.precos-grid{grid-template-columns:1fr}}
</style>
</head>
<body>

<nav>
  <div class="nav-logo">GW</div>
  <ul class="nav-links">
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#portfolio">Portfólio</a></li>
    <li><a href="#servicos">Serviços</a></li>
    <li><a href="#precos">Investimento</a></li>
    <li><a href="#contato">Contato</a></li>
  </ul>
</nav>

<section id="hero">
  <div class="section-inner">
    <div class="hero-eyebrow">Designer de Marca</div>
    <h1 class="hero-name">Gabriele Winkel</h1>
    <p class="hero-subtitle">Branding & Identidade Visual</p>
    <p class="hero-bio">Antes de se expressar, é preciso enxergar quem se é e para onde se vai<br>e eu te ajudo a tornar isso visível.</p>
    <div class="hero-cta">
      <a href="#servicos" class="btn-primary">Ver serviços</a>
      <a href="#portfolio" class="btn-outline">Portfólio</a>
    </div>
  </div>
  <div class="scroll-hint">scroll</div>
</section>

<section id="sobre">
  <div class="section-inner">
    <div>
      <div class="sky-accent">Pelotas, RS — disponível para projetos</div>
      <div class="section-label">Sobre</div>
      <div class="sobre-quote">Revelar o propósito de forma visual</div>
      <p class="sobre-text">Sou Gabriele Winkel, designer de marca, há 2 anos trabalho com branding e identidade visual, acompanhando marcas do zero da estratégia à expressão visual.</p>
      <p class="sobre-text">Acredito que uma marca forte começa de dentro para fora: primeiro encontramos a essência, depois revelamos de forma visual. É por isso que cada projeto começa com uma imersão profunda na história e no propósito do cliente.</p>
      <div class="stats-row">
        <div><div class="stat-number">2+</div><div class="stat-label">Anos de atuação</div></div>
        <div><div class="stat-number">5+</div><div class="stat-label">Projetos entregues</div></div>
        <div><div class="stat-number">3</div><div class="stat-label">Serviços ativos</div></div>
      </div>
    </div>
    <div>
      <div class="sobre-card">
        <p class="sobre-card-text">Não é só sobre criar algo belo,  é sobre revelar, com clareza, o significado que já existe em você.</p>
        <div>
          <span class="sobre-tag">Branding</span>
          <span class="sobre-tag">Identidade Visual</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="portfolio">
  <div class="section-inner">
    <div class="section-label">Portfólio</div>
    <h2 class="section-title">Projetos <em>selecionados</em></h2>
    <div class="portfolio-grid">
      <a class="portfolio-item" href="https://www.behance.net/gallery/232766627/MOVUP-O-MOVIMENTO-QUE-TE-LIBERTA" target="_blank">
        <div><div class="portfolio-index">01</div><div class="portfolio-name">MOVUP</div><div class="portfolio-type">Branding + Identidade Visual</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">2025</span></div>
      </a>
      <a class="portfolio-item" href="https://www.behance.net/gallery/231340243/Maes-de-Geracoes" target="_blank">
        <div><div class="portfolio-index">02</div><div class="portfolio-name">Mães de Gerações</div><div class="portfolio-type">Branding + Identidade Visual</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">2025</span></div>
      </a>
      <a class="portfolio-item" href="https://www.behance.net/gallery/227956751/GRAND-SLAM" target="_blank">
        <div><div class="portfolio-index">03</div><div class="portfolio-name">Grand Slam</div><div class="portfolio-type">Branding + Identidade Visual</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">2025</span></div>
      </a>
      <a class="portfolio-item" href="https://www.behance.net/gallery/227953543/ROSALVO-CABRAL-ADVOCACIA" target="_blank">
        <div><div class="portfolio-index">04</div><div class="portfolio-name">Rosalvo Cabral Advocacia</div><div class="portfolio-type">Branding + Identidade Visual</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">2025</span></div>
      </a>
      <a class="portfolio-item" href="https://www.behance.net/gallery/224705945/Pinz-Legacy" target="_blank">
        <div><div class="portfolio-index">05</div><div class="portfolio-name">Pinz Legacy</div><div class="portfolio-type">Branding + Identidade Visual</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">2024</span></div>
      </a>
      <a class="portfolio-item" href="https://www.behance.net/gabrielewinkel" target="_blank">
        <div><div class="portfolio-index">+</div><div class="portfolio-name">Ver todos</div><div class="portfolio-type">Behance</div></div>
        <div class="portfolio-bottom"><span class="portfolio-year">→</span></div>
      </a>
    </div>
  </div>
</section>

<section id="servicos">
  <div class="section-inner">
    <div class="section-label">Serviços</div>
    <h2 class="section-title">O que eu <em>ofereço</em></h2>
    <div class="servicos-grid">
      <div class="servico-card">
        <span class="servico-number">01</span>
        <span class="servico-tag">Visual</span>
        <h3 class="servico-title">Identidade Visual</h3>
        <p class="servico-subtitle">Expressão visual completa da marca</p>
        <div class="servico-divider"></div>
        <ul class="servico-items">
          <li>Logo e representações</li>
          <li>Tipografias</li>
          <li>Paleta de cor</li>
          <li>Grafismos</li>
        </ul>
      </div>
      <div class="servico-card">
        <span class="servico-number">02</span>
        <span class="servico-tag">Estratégia</span>
        <h3 class="servico-title">Branding</h3>
        <p class="servico-subtitle">Imersão e estratégia da marca</p>
        <div class="servico-divider"></div>
        <ul class="servico-items">
          <li>2 reuniões de imersão de diferenciação</li>
          <li>Voz da marca</li>
          <li>Persona</li>
          <li>Manifesto</li>
        </ul>
      </div>
      <div class="servico-card featured">
        <span class="servico-number">03</span>
        <span class="servico-tag">Mais completo</span>
        <h3 class="servico-title">Branding Completo</h3>
        <p class="servico-subtitle">Imersão estratégica + identidade visual</p>
        <div class="servico-divider"></div>
        <ul class="servico-items">
          <li>2 reuniões de imersão de diferenciação</li>
          <li>Voz da marca</li>
          <li>Persona</li>
          <li>Manifesto</li>
          <li>Logo e representações</li>
          <li>Tipografias</li>
          <li>Paleta de cor</li>
          <li>Grafismos</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="precos">
  <div class="section-inner">
    <div class="section-label">Investimento</div>
    <h2 class="section-title">Valores <em>transparentes</em></h2>
    <p class="precos-intro">Cada projeto é único. Os valores abaixo são referências para você ter clareza do investimento. Entre em contato para um orçamento personalizado.</p>
    <div class="precos-grid">
      <div class="preco-card">
        <div class="preco-service">Serviço 01</div>
        <div class="preco-name">Identidade Visual</div>
        <div class="preco-desc">Só a expressão visual</div>
        <div class="preco-valor">
          <div><div class="preco-cifra">a partir de R$</div><div class="preco-numero">1.500</div></div>
          <div class="preco-periodo">/ projeto</div>
        </div>
        <ul class="preco-items">
          <li>Logo e representações</li>
          <li>Tipografias e paleta de cor</li>
          <li>Grafismos e arquivos finais</li>
        </ul>
      </div>
      <div class="preco-card">
        <div class="preco-service">Serviço 02</div>
        <div class="preco-name">Branding</div>
        <div class="preco-desc">Só a estratégia da marca</div>
        <div class="preco-valor">
          <div><div class="preco-cifra">a partir de R$</div><div class="preco-numero">1.800</div></div>
          <div class="preco-periodo">/ projeto</div>
        </div>
        <ul class="preco-items">
          <li>Imersão + estratégia de marca</li>
          <li>Voz, persona e manifesto</li>
          <li>Documento estratégico completo</li>
        </ul>
      </div>
      <div class="preco-card destaque">
        <div class="preco-badge">Mais completo</div>
        <div style="margin-top:20px">
          <div class="preco-service">Serviço 03</div>
          <div class="preco-name">Branding Completo</div>
          <div class="preco-desc">Imersão + identidade visual</div>
          <div class="preco-valor">
            <div><div class="preco-cifra">a partir de R$</div><div class="preco-numero">3.500</div></div>
            <div class="preco-periodo">/ projeto</div>
          </div>
          <ul class="preco-items">
            <li>Imersão + estratégia de marca</li>
            <li>Identidade visual completa</li>
            <li>Logo, tipografias, paleta e grafismos</li>
            <li>Arquivos finais em múltiplos formatos</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="contato">
  <div class="section-inner" style="text-align:center">
    <div class="section-label" style="justify-content:center">Contato</div>
    <h2 class="section-title">Vamos <em>conversar?</em></h2>
    <p class="contato-text">Se você está pronta para construir uma marca que realmente expressa quem você é, eu adoraria fazer parte dessa jornada.</p>
    <div class="contato-links">
      <a href="https://www.instagram.com/gabiwinkell" target="_blank" class="btn-primary">@gabiwinkell</a>
      <a href="https://www.behance.net/gabrielewinkel" target="_blank" class="btn-outline">Behance</a>
    </div>
  </div>
  <div class="footer-line">© 2025 Gabriele Winkel — Designer de Marca</div>
</section>

<script>
document.querySelectorAll('a[href^="#"]').forEach(a=>{
  a.addEventListener('click',e=>{
    e.preventDefault();
    const el=document.querySelector(a.getAttribute('href'));
    if(el)el.scrollIntoView({behavior:'smooth'});
  });
});
</script>
</body>
</html>
