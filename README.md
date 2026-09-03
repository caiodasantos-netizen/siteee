<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Caio Ribeiro — História de um ex-jogador</title>
<style>
:root{
  --bg:#07111f; --card:#0e1d30; --card2:#122842; --text:#f4f7fb;
  --muted:#a9b8ca; --accent:#29a9ff; --accent2:#65d5ff; --line:#24415e;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:Arial,Helvetica,sans-serif;background:linear-gradient(135deg,#06101d,#0a1728 55%,#07111f);color:var(--text);line-height:1.6}
header{padding:70px 20px 55px;text-align:center;background:radial-gradient(circle at top,#164b73 0,#0a1b2e 42%,transparent 72%)}
.badge{display:inline-block;padding:7px 14px;border:1px solid #2d668d;border-radius:999px;color:var(--accent2);font-size:.85rem}
h1{font-size:clamp(2.3rem,7vw,5rem);margin:15px 0 8px}
.subtitle{max-width:760px;margin:auto;color:var(--muted);font-size:1.08rem}
nav{position:sticky;top:0;z-index:10;background:rgba(6,16,29,.92);backdrop-filter:blur(10px);border-bottom:1px solid var(--line);padding:12px}
.nav-inner{max-width:1050px;margin:auto;display:flex;gap:8px;overflow:auto}
nav button{white-space:nowrap;background:transparent;color:var(--muted);border:1px solid transparent;padding:10px 15px;border-radius:10px;cursor:pointer;font-weight:700}
nav button:hover,nav button.active{background:var(--card2);color:white;border-color:#2a5578}
main{max-width:1050px;margin:35px auto;padding:0 20px}
section{display:none;animation:fade .3s ease}
section.active{display:block}
@keyframes fade{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
.card{background:linear-gradient(145deg,var(--card),#0b192a);border:1px solid var(--line);border-radius:18px;padding:22px}
.card h3{margin-top:0;color:var(--accent2)}
.big{font-size:2rem;font-weight:800}
.muted{color:var(--muted)}
.timeline{position:relative;margin:25px 0;padding-left:28px;border-left:2px solid var(--line)}
.event{position:relative;margin:0 0 24px}
.event:before{content:"";position:absolute;left:-37px;top:6px;width:14px;height:14px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 5px #0b2136}
.year{color:var(--accent2);font-weight:800}
.club{font-size:1.15rem;font-weight:800}
table{width:100%;border-collapse:collapse;background:var(--card);border-radius:16px;overflow:hidden}
th,td{padding:13px;text-align:left;border-bottom:1px solid var(--line)}
th{color:var(--accent2);background:#10243a}
footer{text-align:center;color:var(--muted);padding:40px 20px;border-top:1px solid var(--line);margin-top:50px}
a{color:var(--accent2)}
.quote{font-size:1.25rem;border-left:4px solid var(--accent);padding:8px 18px;color:#dce9f6}
@media(max-width:600px){main{padding:0 14px}.card{padding:18px}th,td{padding:9px;font-size:.9rem}}
</style>
</head>
<body>

<header>
  <span class="badge">HISTÓRIA DO FUTEBOL BRASILEIRO</span>
  <h1>Caio Ribeiro</h1>
  <p class="subtitle">A trajetória do ex-atacante que começou no São Paulo, passou por clubes do Brasil e da Europa, vestiu a Seleção Brasileira e depois construiu uma carreira na comunicação esportiva.</p>
</header>

<nav>
  <div class="nav-inner">
    <button class="active" onclick="showTab('inicio',this)">Início</button>
    <button onclick="showTab('inicio',this)">Biografia</button>
    <button onclick="showTab('carreira',this)">Carreira</button>
    <button onclick="showTab('selecao',this)">Seleção</button>
    <button onclick="showTab('titulos',this)">Títulos</button>
    <button onclick="showTab('pos',this)">Depois dos gramados</button>
    <button onclick="showTab('fontes',this)">Fontes</button>
  </div>
</nav>

<main>
<section id="inicio" class="active">
  <div class="grid">
    <div class="card"><div class="big">1975</div><div class="muted">Ano de nascimento</div><p>Caio Ribeiro Decoussau nasceu em São Paulo, em 16 de agosto.</p></div>
    <div class="card"><div class="big">Atacante</div><div class="muted">Posição</div><p>Atuava no ataque e ganhou destaque ainda jovem no São Paulo.</p></div>
    <div class="card"><div class="big">São Paulo</div><div class="muted">Formação</div><p>Foi formado nas categorias de base do clube e chegou ao profissional.</p></div>
    <div class="card"><div class="big">Europa</div><div class="muted">Experiência internacional</div><p>Defendeu Internazionale e Napoli na década de 1990.</p></div>
  </div>
  <div class="card" style="margin-top:18px">
    <h2>Quem foi Caio Ribeiro?</h2>
    <p>Caio Ribeiro foi um atacante brasileiro que teve uma carreira marcada por uma ascensão rápida. Revelado pelo São Paulo, ganhou espaço no início dos anos 1990 e, após se destacar nas categorias de base da Seleção, foi contratado pela Internazionale, da Itália.</p>
    <p>Depois da experiência europeia, retornou ao Brasil e passou por Santos, Flamengo, Fluminense, Grêmio e Botafogo, além de uma passagem pelo futebol alemão. Mais tarde, transformou sua experiência no esporte em uma nova carreira como comentarista.</p>
  </div>
</section>

<section id="carreira">
  <h2>Carreira — uma viagem no tempo</h2>
  <div class="timeline">
    <div class="event"><div class="year">Início dos anos 1990</div><div class="club">São Paulo</div><p>Caio surgiu nas categorias de base do clube e estreou profissionalmente em 1994. Segundo o arquivo do São Paulo FC, terminou sua passagem com 95 jogos e 33 gols.</p></div>
    <div class="event"><div class="year">1995–1996</div><div class="club">Internazionale</div><p>Após se destacar no Mundial Sub-20, foi contratado pelo clube italiano. Teve poucas oportunidades na equipe principal.</p></div>
    <div class="event"><div class="year">1996–1997</div><div class="club">Napoli</div><p>Foi emprestado ao Napoli, encerrando sua primeira experiência no futebol italiano antes de retornar ao Brasil.</p></div>
    <div class="event"><div class="year">1997</div><div class="club">Santos</div><p>De volta ao Brasil, atuou pelo Santos e conquistou o Torneio Rio-São Paulo.</p></div>
    <div class="event"><div class="year">1998–1999</div><div class="club">Flamengo</div><p>No Flamengo, ganhou carinho da torcida e viveu uma fase de destaque, inclusive ao lado de grandes nomes do ataque.</p></div>
    <div class="event"><div class="year">2000–2004</div><div class="club">Santos, Fluminense, Flamengo, Grêmio e Rot-Weiß Oberhausen</div><p>Seguiu sua trajetória por diferentes clubes brasileiros e teve uma nova experiência internacional no futebol alemão.</p></div>
    <div class="event"><div class="year">2004–2005</div><div class="club">Botafogo</div><p>O Botafogo foi seu último clube profissional. Caio encerrou a carreira ainda jovem, aos 30 anos, após mais de uma década no futebol.</p></div>
  </div>
</section>

<section id="selecao">
  <h2>Caio e a Seleção Brasileira</h2>
  <div class="grid">
    <div class="card"><h3>Mundial Sub-20</h3><p>Em 1995, Caio integrou a Seleção Brasileira Sub-20 e recebeu reconhecimento individual por seu desempenho na competição.</p></div>
    <div class="card"><h3>Seleção principal</h3><p>Em 1996, atuou pela Seleção Brasileira principal. Registros de carreira apontam 4 partidas e 3 gols.</p></div>
    <div class="card"><h3>Uma fase de grande expectativa</h3><p>O bom momento como jovem atacante ajudou a colocá-lo no radar de clubes europeus, contribuindo para sua transferência para a Itália.</p></div>
  </div>
</section>

<section id="titulos">
  <h2>Títulos e conquistas</h2>
  <table>
    <thead><tr><th>Ano</th><th>Conquista</th><th>Clube/Seleção</th></tr></thead>
    <tbody>
      <tr><td>1994</td><td>Recopa Sul-Americana</td><td>São Paulo</td></tr>
      <tr><td>1994</td><td>Copa CONMEBOL</td><td>São Paulo</td></tr>
      <tr><td>1997</td><td>Torneio Rio-São Paulo</td><td>Santos</td></tr>
      <tr><td>1999</td><td>Copa Mercosul</td><td>Flamengo</td></tr>
      <tr><td>1995</td><td>Reconhecimento individual no Mundial Sub-20</td><td>Brasil Sub-20</td></tr>
    </tbody>
  </table>
  <p class="muted">As listas de títulos podem variar conforme a fonte e o critério utilizado para considerar uma conquista individual ou coletiva.</p>
</section>

<section id="pos">
  <h2>Depois dos gramados</h2>
  <div class="card">
    <p>Após deixar o futebol profissional, Caio Ribeiro estudou Gestão do Esporte e iniciou uma nova etapa no jornalismo e na televisão.</p>
    <p>Ele passou a trabalhar como comentarista esportivo e tornou-se conhecido do público por sua participação em transmissões e programas de futebol.</p>
    <p class="quote">Sua história mostra uma transição interessante: do jogador dentro de campo para o profissional que passou a analisar o futebol diante das câmeras.</p>
  </div>
</section>

<section id="fontes">
  <h2>Fontes consultadas</h2>
  <div class="card">
    <p><strong>São Paulo Futebol Clube — Fichário:</strong> dados da passagem de Caio pelo clube, incluindo jogos, gols e títulos.</p>
    <p><strong>Terceiro Tempo:</strong> biografia, clubes, Seleção e trajetória profissional.</p>
    <p><strong>UOL/NaTelinha:</strong> dados biográficos e resumo da carreira.</p>
    <p><strong>Goal Brasil:</strong> panorama dos clubes e conquistas.</p>
    <p class="muted">Este site foi criado para fins educativos e de apresentação. Os dados foram organizados e resumidos a partir das fontes acima.</p>
  </div>
</section>
</main>

<footer>
  Site educativo • História de Caio Ribeiro • Desenvolvido em HTML, CSS e JavaScript
</footer>

<script>
function showTab(id, btn){
  document.querySelectorAll('section').forEach(s=>s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));
  if(btn) btn.classList.add('active');
  window.scrollTo({top:0,behavior:'smooth'});
}
</script>
</body>
</html>
