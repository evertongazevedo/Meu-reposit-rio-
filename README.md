
Bem-vindo ao meu portfólio! Eu sou o Everton e este espaço foi criado para apresentar quem eu sou, o que sei fazer e o que busco para o meu futuro. Aqui você vai encontrar minhas habilidades em HTML, Java e Python, meus interesses e meu objetivo de trabalhar com cibersegurança. Fique à vontade para explorar e, se quiser conversar, é só entrar em contato!





Portfolio everton · HTML 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Everton – Portfólio</title>
<meta name="description" content="Portfólio de Everton: HTML, Java e Python, com foco em cibersegurança.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F2F5F7; --surface:#FFFFFF; --ink:#101B2D; --muted:#53627A; --line:#D5DCE4;
  --accent:#2F5BFF; --accent-ink:#FFFFFF;
  --term-bg:#0F1A2B; --term-text:#DCE6F5; --term-dim:#8396B3; --term-key:#7FA2FF; --term-ok:#6FD6A0;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0B1320; --surface:#131E30; --ink:#E8EEF8; --muted:#9AA9C2; --line:#25344C;
    --accent:#7FA2FF; --accent-ink:#0B1320; --term-bg:#070D17;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0B1320; --surface:#131E30; --ink:#E8EEF8; --muted:#9AA9C2; --line:#25344C;
  --accent:#7FA2FF; --accent-ink:#0B1320; --term-bg:#070D17; color-scheme:dark;
}
*,*::before,*::after{box-sizing:inherit}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"IBM Plex Sans",system-ui,sans-serif;line-height:1.65;font-size:17px}
a{color:inherit}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px;border-radius:4px}
.wrap{max-width:960px;margin:0 auto;padding:0 24px}
 
header.top{display:flex;justify-content:space-between;align-items:center;padding:22px 0}
.brand{font-family:"IBM Plex Mono",monospace;font-weight:500;text-decoration:none}
nav{display:flex;gap:22px;font-size:15px}
nav a{text-decoration:none;color:var(--muted)}
nav a:hover{color:var(--ink);text-decoration:underline;text-underline-offset:5px}
 
.hero{display:grid;grid-template-columns:1.1fr 1fr;gap:48px;align-items:center;padding:48px 0 72px}
h1{font-size:clamp(2.4rem,6vw,3.9rem);line-height:1.05;letter-spacing:-.03em;margin:0 0 20px;font-weight:600}
.lead{font-size:1.15rem;color:var(--muted);max-width:30em;margin:0 0 28px}
.cta{display:flex;flex-wrap:wrap;gap:12px}
.btn{display:inline-block;padding:12px 20px;border-radius:8px;font-weight:500;text-decoration:none;border:1.5px solid var(--ink)}
.btn.primary{background:var(--accent);border-color:var(--accent);color:var(--accent-ink)}
.btn:hover{transform:translateY(-1px)}
 
.term{background:var(--term-bg);color:var(--term-text);border-radius:12px;font-family:"IBM Plex Mono",monospace;font-size:14px;line-height:1.7;overflow:hidden;box-shadow:0 18px 40px -22px rgba(16,27,45,.55)}
.term-bar{display:flex;gap:7px;padding:12px 16px;border-bottom:1px solid rgba(255,255,255,.08)}
.term-bar i{width:11px;height:11px;border-radius:50%;background:#3A4A66;display:block}
.term-body{padding:18px 20px 22px;min-height:236px;overflow-x:auto;white-space:pre-wrap;word-break:break-word}
.p{color:var(--term-ok)} .k{color:var(--term-key)} .d{color:var(--term-dim)}
.caret{display:inline-block;width:8px;height:1.1em;background:var(--term-text);vertical-align:-2px;animation:blink 1s steps(1) infinite}
@keyframes blink{50%{opacity:0}}
 
section{padding:56px 0;border-top:1px solid var(--line)}
h2{font-size:1.9rem;letter-spacing:-.02em;margin:0 0 24px;font-weight:600}
.about{max-width:38em}
.about p{margin:0 0 16px}
 
.skills{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.skill{background:var(--surface);border:1px solid var(--line);border-radius:10px;padding:24px}
.skill h3{font-family:"IBM Plex Mono",monospace;font-size:1.25rem;margin:0 0 8px;font-weight:500}
.skill p{margin:0;color:var(--muted);font-size:.98rem}
 
.split{display:grid;grid-template-columns:1fr 1fr;gap:40px}
.split h3{font-size:1.15rem;margin:0 0 10px}
.split p{margin:0;color:var(--muted)}
.focus{border-left:4px solid var(--accent);padding-left:20px}
 
.contact-list{list-style:none;margin:0;padding:0;display:grid;gap:14px;max-width:34em}
.contact-list li{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;padding:16px 20px;background:var(--surface);border:1px solid var(--line);border-radius:10px}
.contact-list span{color:var(--muted)}
.contact-list a{font-weight:500;text-underline-offset:4px}
 
footer{padding:32px 0 48px;border-top:1px solid var(--line);color:var(--muted);font-size:.92rem}
 
@media (max-width:820px){
  .hero,.split{grid-template-columns:1fr}
  .skills{grid-template-columns:1fr}
  .hero{gap:36px;padding-top:24px}
  nav{gap:16px}
}
@media (max-width:480px){
  header.top{flex-direction:column;align-items:flex-start;gap:10px}
  .contact-list li{flex-direction:column;gap:2px}
}
@media (prefers-reduced-motion: reduce){
  html{scroll-behavior:auto}.caret{animation:none}.btn:hover{transform:none}
}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <a class="brand" href="#inicio">everton.dev</a>
    <nav aria-label="Principal">
      <a href="#sobre">Sobre</a>
      <a href="#habilidades">Habilidades</a>
      <a href="#objetivo">Objetivo</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>
 
  <main id="inicio">
    <div class="hero">
      <div>
        <h1>Olá, eu sou o Everton.</h1>
        <p class="lead">Programo em HTML, Java e Python e estou construindo meu caminho para a área de cibersegurança.</p>
        <div class="cta">
          <a class="btn primary" href="#contato">Entrar em contato</a>
          <a class="btn" href="#habilidades">Ver habilidades</a>
        </div>
      </div>
      <div class="term" role="img" aria-label="Terminal mostrando o perfil de Everton: linguagens HTML, Java e Python, objetivo cibersegurança">
        <div class="term-bar" aria-hidden="true"><i></i><i></i><i></i></div>
        <div class="term-body" id="term" aria-hidden="true"></div>
      </div>
    </div>
 
    <section id="sobre">
      <h2>Sobre mim</h2>
      <div class="about">
        <p>Sou o Everton e tenho experiência com programação em HTML, Java e Python. Gosto de aprender como as coisas funcionam por dentro e de transformar o que estudo em código.</p>
        <p>Fora do computador e dentro dele, meus momentos de lazer são jogar e estudar. Os dois me ensinam a persistir, resolver problemas e pensar com estratégia.</p>
      </div>
    </section>
 
    <section id="habilidades">
      <h2>Habilidades</h2>
      <div class="skills">
        <article class="skill">
          <h3>HTML</h3>
          <p>Estrutura de páginas e sites com marcação organizada e acessível.</p>
        </article>
        <article class="skill">
          <h3>Java</h3>
          <p>Programação orientada a objetos e lógica para criar aplicações.</p>
        </article>
        <article class="skill">
          <h3>Python</h3>
          <p>Scripts e automações, uma linguagem muito usada em segurança da informação.</p>
        </article>
      </div>
    </section>
 
    <section id="objetivo">
      <h2>Interesses e objetivo</h2>
      <div class="split">
        <div class="focus">
          <h3>Cibersegurança</h3>
          <p>Quero trabalhar na área de cibersegurança, protegendo sistemas e dados. Estou me preparando para isso estudando e praticando programação.</p>
        </div>
        <div>
          <h3>Lazer: jogar e estudar</h3>
          <p>Jogos treinam raciocínio rápido e persistência. Os estudos me mantêm evoluindo todos os dias.</p>
        </div>
      </div>
    </section>
 
    <section id="contato">
      <h2>Contato</h2>
      <ul class="contact-list">
        <li><span>Telefone</span><a href="tel:+5583986938284">(83) 98693-8284</a></li>
        <li><span>WhatsApp</span><a href="https://wa.me/5583986938284">Enviar mensagem</a></li>
        <li><span>E-mail</span><a href="mailto:evertongermany86@gmail.com">evertongermany86@gmail.com</a></li>
      </ul>
    </section>
  </main>
 
  <footer>© <span id="ano">2026</span> Everton. Todos os direitos reservados.</footer>
</div>
 
<script>
(function(){
  document.getElementById('ano').textContent = new Date().getFullYear();
  var el = document.getElementById('term');
  var lines = [
    '<span class="p">$</span> whoami',
    'everton',
    '<span class="p">$</span> cat linguagens.txt',
    '<span class="k">HTML</span>  <span class="k">Java</span>  <span class="k">Python</span>',
    '<span class="p">$</span> cat lazer.txt',
    'jogar, estudar',
    '<span class="p">$</span> echo $OBJETIVO',
    '<span class="k">cibersegurança</span>'
  ];
  var reduce = window.matchMedia && matchMedia('(prefers-reduced-motion: reduce)').matches;
  var caret = '<span class="caret"></span>';
  if (reduce){ el.innerHTML = lines.join('\n') + '\n<span class="p">$</span> ' + caret; return; }
  var i = 0;
  function next(){
    if (i >= lines.length){ el.innerHTML = lines.join('\n') + '\n<span class="p">$</span> ' + caret; return; }
    i++;
    el.innerHTML = lines.slice(0,i).join('\n') + '\n' + caret;
    setTimeout(next, lines[i-1].indexOf('$') > -1 ? 550 : 330);
  }
  next();
})();
</script>
</body>
</html>
 
