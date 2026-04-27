<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Painel Operacional</title>
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'Segoe UI', system-ui, sans-serif; background: #f4f5f7; color: #1a1a2e; min-height: 100vh; }
.container { max-width: 1100px; margin: 0 auto; padding: 24px 16px; }
header { margin-bottom: 24px; }
header h1 { font-size: 20px; font-weight: 600; color: #1a1a2e; }
header p { font-size: 13px; color: #666; margin-top: 2px; }
.nav { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 24px; background: #fff; border-radius: 12px; padding: 10px; border: 1px solid #e8e8ee; }
.nav-btn { background: transparent; border: none; border-radius: 8px; padding: 8px 16px; font-size: 13px; font-weight: 500; color: #666; cursor: pointer; transition: all 0.15s; }
.nav-btn:hover { background: #f4f5f7; color: #1a1a2e; }
.nav-btn.active { background: #1a56db; color: #fff; }
.panel { display: none; }
.panel.active { display: block; }
.sec-label { font-size: 11px; font-weight: 600; text-transform: uppercase; letter-spacing: 0.06em; color: #888; margin-bottom: 8px; margin-top: 16px; }
.sec-sub { font-size: 11px; color: #aaa; margin-top: -6px; margin-bottom: 8px; }
.grid-cards { display: grid; grid-template-columns: repeat(auto-fill, minmax(145px,1fr)); gap: 8px; margin-bottom: 8px; }
.card { background: #fff; border: 1.5px solid #e8e8ee; border-radius: 12px; padding: 10px 12px; cursor: pointer; user-select: none; transition: all 0.15s; }
.card:hover { border-color: #b0c4f8; box-shadow: 0 2px 8px rgba(26,86,219,0.07); }
.card.selected { border: 2px solid #1a56db; background: #eef3ff; }
.card.selected .cname { color: #1a56db; }
.initials { width: 32px; height: 32px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 12px; font-weight: 600; margin-bottom: 6px; }
.cname { font-size: 12px; font-weight: 600; color: #1a1a2e; margin-bottom: 2px; line-height: 1.3; }
.cvals { font-size: 11px; color: #888; line-height: 1.8; }
.cvals span { display: block; }
.ctag { display: inline-block; font-size: 10px; padding: 2px 7px; border-radius: 20px; margin-top: 5px; font-weight: 500; }
.result-box { background: #fff; border: 1px solid #e8e8ee; border-radius: 12px; padding: 18px; margin-top: 8px; }
.empty { color: #bbb; font-size: 13px; text-align: center; padding: 28px 0; }
.g2 { display: grid; grid-template-columns: repeat(2, minmax(0,1fr)); gap: 10px; margin-bottom: 12px; }
.g3 { display: grid; grid-template-columns: repeat(3, minmax(0,1fr)); gap: 10px; margin-bottom: 12px; }
.g4 { display: grid; grid-template-columns: repeat(4, minmax(0,1fr)); gap: 10px; margin-bottom: 12px; }
.g5 { display: grid; grid-template-columns: repeat(5, minmax(0,1fr)); gap: 8px; margin-bottom: 14px; }
.m { border-radius: 10px; padding: 11px 13px; }
.m .ml { font-size: 11px; margin-bottom: 3px; font-weight: 500; }
.m .mv { font-size: 17px; font-weight: 600; }
.mr { background: #fff1f1; } .mr .ml { color: #c0392b; } .mr .mv { color: #922b21; }
.mg { background: #eafaf1; } .mg .ml { color: #1e8449; } .mg .mv { color: #1a5e36; }
.mn { background: #f4f5f7; } .mn .ml { color: #888; } .mn .mv { color: #1a1a2e; }
.mb { background: #eef3ff; } .mb .ml { color: #1a56db; } .mb .mv { color: #1239a0; }
.team-block { border: 1px solid #e8e8ee; border-radius: 10px; padding: 14px; margin-bottom: 12px; }
.team-title { font-size: 12px; font-weight: 600; margin-bottom: 10px; }
.row-item { display:flex; justify-content:space-between; align-items:center; padding:7px 0; border-bottom:1px solid #f0f0f5; font-size:12px; flex-wrap:wrap; gap:4px; }
.row-item:last-child { border-bottom:none; }
.row-name { color:#1a1a2e; font-weight:600; }
.row-vals { display:flex; gap:12px; color:#888; flex-wrap:wrap; font-size:11px; }
.row-vals b { color:#1a1a2e; font-weight:600; }
.pct-bar-bg { background: #f0f0f5; border-radius:6px; height:7px; overflow:hidden; margin-top:4px; }
.pct-bar { height:7px; border-radius:6px; }
.divider { border:none; border-top:1px solid #f0f0f5; margin:14px 0; }
.day-card { border-radius:10px; padding:12px 8px; text-align:center; }
.day-card .dl { font-size:11px; font-weight:600; margin-bottom:4px; }
.day-card .dv { font-size:15px; font-weight:600; }
.mini-bar { height:4px; border-radius:2px; margin-top:4px; }
.op-table { width:100%; border-collapse:collapse; font-size:12px; }
.op-table th { background:#f9f9fb; padding:8px 10px; text-align:center; font-weight:600; color:#888; font-size:11px; border-bottom:1px solid #eee; }
.op-table th.left { text-align:left; }
.op-table td { padding:8px 10px; text-align:right; border-bottom:1px solid #f4f5f7; color:#1a1a2e; }
.op-table td.left { text-align:left; font-weight:600; }
.op-table td.center { text-align:center; }
.op-table tr:last-child td { border-bottom:none; }
.badge-up { display:inline-block; font-size:10px; padding:2px 7px; border-radius:20px; background:#eafaf1; color:#1e8449; font-weight:600; }
.badge-dn { display:inline-block; font-size:10px; padding:2px 7px; border-radius:20px; background:#fff1f1; color:#c0392b; font-weight:600; }
.badge-eq { display:inline-block; font-size:10px; padding:2px 7px; border-radius:20px; background:#f4f5f7; color:#888; }
.badge-desl { display:inline-block; font-size:10px; padding:2px 7px; border-radius:20px; background:#fff1f1; color:#c0392b; font-weight:600; }
.badge-new { display:inline-block; font-size:10px; padding:2px 7px; border-radius:20px; background:#eef3ff; color:#1a56db; font-weight:600; }
.hslider-row { display:flex; align-items:center; gap:10px; margin-bottom:14px; flex-wrap:wrap; background:#f9f9fb; border-radius:10px; padding:10px 14px; }
input[type=range] { accent-color: #1a56db; }
</style>
</head>
<body>
<div class="container">
  <header>
    <h1>Painel Operacional</h1>
    <p>Base: Fevereiro + Março 2026</p>
  </header>

  <div class="nav">
    <button class="nav-btn active" onclick="showPanel('perda',this)">Perda por Ausência</button>
    <button class="nav-btn" onclick="showPanel('medias',this)">Médias Fev+Mar</button>
    <button class="nav-btn" onclick="showPanel('semana',this)">Produção por Dia</button>
    <button class="nav-btn" onclick="showPanel('mes',this)">Mês a Mês</button>
  </div>

  <!-- P1: PERDA -->
  <div class="panel active" id="panel-perda">
    <div style="font-size:12px;color:#888;margin-bottom:10px;">Selecione os operadores ausentes</div>
    <div class="sec-label" style="color:#1a56db;">UME — Discador</div><div class="grid-cards" id="p1-ume-disc"></div>
    <div class="sec-label" style="color:#1a56db;">UME — Jovem Aprendiz</div><div class="sec-sub">Ter–Sex</div><div class="grid-cards" id="p1-ume-ja"></div>
    <div class="sec-label" style="color:#7f56d9;">UME — WhatsApp</div><div class="grid-cards" id="p1-ume-wp"></div>
    <div class="sec-label" style="color:#0d7a55;">ODRES — Discador</div><div class="grid-cards" id="p1-odres-disc"></div>
    <div class="sec-label" style="color:#276749;">ODRES — WhatsApp</div><div class="grid-cards" id="p1-odres-wp"></div>
    <div class="hslider-row">
      <label style="font-size:13px;color:#555;">Horas ausente hoje:</label>
      <input type="range" min="0.5" max="8" step="0.5" value="8" id="hslider" style="width:130px;">
      <span style="font-size:13px;font-weight:600;color:#1a1a2e;min-width:28px;" id="hval">8h</span>
    </div>
    <div class="result-box" id="p1-result"><div class="empty">Selecione um ou mais operadores acima</div></div>
  </div>

  <!-- P2: MÉDIAS -->
  <div class="panel" id="panel-medias">
    <div style="font-size:12px;color:#888;margin-bottom:10px;">Médias consolidadas Fevereiro + Março</div>
    <div class="sec-label" style="color:#1a56db;">UME — Discador</div><div class="grid-cards" id="p2-ume-disc"></div>
    <div class="sec-label" style="color:#1a56db;">UME — Jovem Aprendiz</div><div class="grid-cards" id="p2-ume-ja"></div>
    <div class="sec-label" style="color:#7f56d9;">UME — WhatsApp</div><div class="grid-cards" id="p2-ume-wp"></div>
    <div class="sec-label" style="color:#0d7a55;">ODRES — Discador</div><div class="grid-cards" id="p2-odres-disc"></div>
    <div class="sec-label" style="color:#276749;">ODRES — WhatsApp</div><div class="grid-cards" id="p2-odres-wp"></div>
  </div>

  <!-- P3: DIA DA SEMANA -->
  <div class="panel" id="panel-semana">
    <div style="font-size:12px;color:#888;margin-bottom:10px;">Selecione operadores para ver produção por dia da semana</div>
    <div class="sec-label" style="color:#1a56db;">UME</div><div class="grid-cards" id="p3-ume"></div>
    <div class="sec-label" style="color:#0d7a55;">ODRES</div><div class="grid-cards" id="p3-odres"></div>
    <div class="result-box" id="p3-result"><div class="empty">Selecione um ou mais operadores acima</div></div>
  </div>

  <!-- P4: MÊS A MÊS -->
  <div class="panel" id="panel-mes">
    <div style="font-size:12px;color:#888;margin-bottom:14px;">Comparativo de faturamento por operador — Fevereiro vs Março</div>
    <div id="p4-content"></div>
  </div>
</div>

<script>
const ops = [
  { name:'Andressa Bruna',   initials:'AB', color:'#dbeafe', tc:'#1e40af', fev:{total:15291,dias:20},  mar:{total:15174.46,dias:21}, equipe:'UME',   sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-ume-disc',   p2:'p2-ume-disc',   p3:'p3-ume'   },
  { name:'Raquel Moreira',   initials:'RM', color:'#dbeafe', tc:'#1e40af', fev:{total:8108,dias:20},   mar:{total:3882.26,dias:21},  equipe:'UME',   sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-ume-disc',   p2:'p2-ume-disc',   p3:'p3-ume'   },
  { name:'Rayara Danielle',  initials:'RD', color:'#dbeafe', tc:'#1e40af', fev:{total:5567,dias:20},   mar:{total:2670.92,dias:21},  equipe:'UME',   sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-ume-disc',   p2:'p2-ume-disc',   p3:'p3-ume'   },
  { name:'Vitória Ketelin',  initials:'VK', color:'#fee2e2', tc:'#991b1b', fev:{total:40069,dias:15},  mar:{total:4702.85,dias:5},   equipe:'UME',   sub:'Discador',       tag:'Desl.',  ativo:false, p1:'p1-ume-disc',   p2:'p2-ume-disc',   p3:'p3-ume'   },
  { name:'Pamela Moreira',   initials:'PM', color:'#fee2e2', tc:'#991b1b', fev:{total:8482,dias:15},   mar:{total:7336.73,dias:10},  equipe:'UME',   sub:'Discador',       tag:'Desl.',  ativo:false, p1:'p1-ume-disc',   p2:'p2-ume-disc',   p3:'p3-ume'   },
  { name:'Kayke Araújo',     initials:'KA', color:'#bfdbfe', tc:'#1e3a8a', fev:{total:18786,dias:16},  mar:{total:9241.93,dias:17},  equipe:'UME',   sub:'Jovem Aprendiz', tag:'J.A.',   ativo:true,  p1:'p1-ume-ja',     p2:'p2-ume-ja',     p3:'p3-ume'   },
  { name:'Pamela Isabelle',  initials:'PI', color:'#bfdbfe', tc:'#1e3a8a', fev:{total:29052,dias:16},  mar:{total:14813.61,dias:17}, equipe:'UME',   sub:'Jovem Aprendiz', tag:'J.A.',   ativo:true,  p1:'p1-ume-ja',     p2:'p2-ume-ja',     p3:'p3-ume'   },
  { name:'Lauane Stephanie', initials:'LS', color:'#ede9fe', tc:'#5b21b6', fev:{total:0,dias:0},       mar:{total:1125.50,dias:10},  equipe:'UME',   sub:'WhatsApp',       tag:'WP',     ativo:true,  p1:'p1-ume-wp',     p2:'p2-ume-wp',     p3:'p3-ume'   },
  { name:'Adriano Correia',  initials:'AC', color:'#d1fae5', tc:'#065f46', fev:{total:15910,dias:20},  mar:{total:5780.32,dias:21},  equipe:'ODRES', sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-odres-disc', p2:'p2-odres-disc', p3:'p3-odres' },
  { name:'Beatriz Santos',   initials:'BS', color:'#d1fae5', tc:'#065f46', fev:{total:13736,dias:20},  mar:{total:7349.76,dias:21},  equipe:'ODRES', sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-odres-disc', p2:'p2-odres-disc', p3:'p3-odres' },
  { name:'Larissa Rosário',  initials:'LR', color:'#d1fae5', tc:'#065f46', fev:{total:7792,dias:20},   mar:{total:7300.32,dias:21},  equipe:'ODRES', sub:'Discador',       tag:'Disc.',  ativo:true,  p1:'p1-odres-disc', p2:'p2-odres-disc', p3:'p3-odres' },
  { name:'Simone Gama',      initials:'SG', color:'#fee2e2', tc:'#991b1b', fev:{total:36851,dias:15},  mar:{total:29875.64,dias:10}, equipe:'ODRES', sub:'Discador',       tag:'Desl.',  ativo:false, p1:'p1-odres-disc', p2:'p2-odres-disc', p3:'p3-odres' },
  { name:'Talita Souza',     initials:'TS', color:'#d1fae5', tc:'#14532d', fev:{total:2124,dias:20},   mar:{total:0,dias:0},         equipe:'ODRES', sub:'WhatsApp',       tag:'WP',     ativo:true,  p1:'p1-odres-wp',   p2:'p2-odres-wp',   p3:'p3-odres' },
];

const rawMar = {
  'Andressa Bruna':  [2418.6,0,410.5,0,1014.4,1546.5,0,264.24,1210.74,69.64,3217.78,1406.28,0,266.53,0,928.39,565.91,200.09,385.73,100,398,516.13],
  'Raquel Moreira':  [0,0,0,1734.75,326.62,141,0,0,518.35,0,0,0,0,506.78,0,654.76,0,0,0,0,0,0],
  'Rayara Danielle': [0,0,0,0,0,0,0,0,0,0,0,395.69,0,0,1016.66,0,482.91,383.66,0,0,198,194],
  'Vitória Ketelin': [0,0,0,0,2812.68,0,0,1604.41,0,0,285.76,0,0,0,0,0,0,0,0,0,0,0],
  'Pamela Moreira':  [707.6,230.23,304,630.92,771.49,0,0,0,0,0,1297.02,148,0,1188.19,0,0,0,0,0,0,0,0],
  'Kayke Araújo':    [0,912.88,1788.66,1695.16,1284.87,0,0,280.46,228.74,428.36,0,0,0,922.96,0,0,0,0,395.86,0,0,1303.98],
  'Pamela Isabelle': [0,6648.44,282.61,1759.38,663.06,0,0,0,1310.49,428.42,0,0,0,583.9,0,0,0,0,2215.75,0,0,921.56],
  'Lauane Stephanie':[0,0,0,0,0,0,0,0,0,0,0,418,707.5,0,0,0,0,0,0,0,0,0],
  'Adriano Correia': [362,1469.97,485.55,0,927.37,226.4,0,130.05,184.44,0,0,241.78,0,450.5,0,0,526.8,371.13,404.33,0,0,0],
  'Beatriz Santos':  [2130.91,985.77,0,408.24,948.24,1127.91,0,0,0,0,462.21,82.21,301.68,304.45,0,277.67,0,0,0,220.47,0,100],
  'Larissa Rosário': [993.94,458.53,472.15,237.93,0,912.08,0,0,266.36,0,708.68,621.71,0,171.15,238,253.84,301.88,251.41,0,0,0,323.09],
  'Simone Gama':     [6321.53,3516.43,3345.01,932.54,1747.32,4858.88,191,0,890.3,0,1960.28,1092.72,908.38,801.46,0,791.46,893.91,1028.21,0,0,0,0],
  'Talita Souza':    [0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],
};

const calendario = [[0],[1],[2],[3],[4],[0],[1],[2],[3],[4],[0],[2],[3],[4],[0],[1],[2],[3],[4],[0],[1]];
const diasNome = ['Segunda','Terça','Quarta','Quinta','Sexta'];
const diasCor  = ['#eff6ff','#f0fdf4','#f5f3ff','#fffbeb','#fff7ed'];
const diasTxt  = ['#1e40af','#065f46','#5b21b6','#92400e','#9a3412'];
const diasBar  = ['#3b82f6','#22c55e','#8b5cf6','#f59e0b','#f97316'];

function calcMediaDia(nome){
  const vals=rawMar[nome]||[];
  const soma=[0,0,0,0,0],cont=[0,0,0,0,0];
  calendario.forEach(([ds],i)=>{const v=vals[i]||0;if(v>0){soma[ds]+=v;cont[ds]++;}});
  return soma.map((s,i)=>cont[i]>0?s/cont[i]:0);
}

ops.forEach(op=>{
  op.mediaDia=calcMediaDia(op.name);
  const td=op.fev.dias+op.mar.dias;
  op.mediaDiaCons=td>0?(op.fev.total+op.mar.total)/td:0;
  op.mediaHora=op.mediaDiaCons/8;
  op.mensalEst=op.mediaDiaCons*(op.sub==='Jovem Aprendiz'?17:20);
});

const totalMensal=ops.reduce((s,o)=>s+o.mensalEst,0);
const totalDia=ops.reduce((s,o)=>s+o.mediaDiaCons,0);
const fmt  = v=>v>0?'R$ '+v.toLocaleString('pt-BR',{minimumFractionDigits:2,maximumFractionDigits:2}):'—';
const fmt0 = v=>'R$ '+v.toLocaleString('pt-BR',{minimumFractionDigits:0,maximumFractionDigits:0});
const fmtV = v=>v===0?'—':'R$ '+v.toLocaleString('pt-BR',{minimumFractionDigits:2,maximumFractionDigits:2});
const pct  = v=>(v*100).toFixed(1)+'%';

const selP1=new Set(),selP3=new Set();
let horas=8;

function showPanel(id,btn){
  document.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById('panel-'+id).classList.add('active');
  btn.classList.add('active');
  if(id==='mes')renderP4();
}

function buildCard(op,i,container,selSet,renderFn,mode){
  const cont=document.getElementById(container);
  if(!cont)return;
  const div=document.createElement('div');
  div.className='card';
  let valsHtml='';
  if(mode==='medias'){
    valsHtml=`<div class="cvals">
      <span>Fev: <b style="color:#1a1a2e">${op.fev.total>0?fmt(op.fev.total):'—'}</b></span>
      <span>Mar: <b style="color:#1a1a2e">${op.mar.total>0?fmt(op.mar.total):'—'}</b></span>
      <span>Média/dia: <b style="color:#1a1a2e">${op.mediaDiaCons>0?fmt(op.mediaDiaCons):'—'}</b></span>
      <span>Média/hora: <b style="color:#1a1a2e">${op.mediaHora>0?fmt(op.mediaHora):'—'}</b></span>
    </div>`;
  }
  div.innerHTML=`
    <div class="initials" style="background:${op.color};color:${op.tc}">${op.initials}</div>
    <div class="cname">${op.name}</div>
    ${valsHtml}
    <span class="ctag" style="background:${op.color};color:${op.tc}">${op.equipe} · ${op.tag}</span>
  `;
  if(selSet){
    div.addEventListener('click',()=>{
      if(selSet.has(i))selSet.delete(i);else selSet.add(i);
      div.classList.toggle('selected',selSet.has(i));
      renderFn();
    });
  }
  cont.appendChild(div);
}

ops.forEach((op,i)=>{
  buildCard(op,i,op.p1,selP1,renderP1,'');
  buildCard(op,i,op.p2,null,null,'medias');
  buildCard(op,i,op.p3,selP3,renderP3,'');
});

document.getElementById('hslider').addEventListener('input',e=>{
  horas=parseFloat(e.target.value);
  document.getElementById('hval').textContent=horas+'h';
  renderP1();
});

function teamBlockP1(label,barColor,sel){
  if(!sel.length)return'';
  const pDia=sel.reduce((s,o)=>s+o.mediaDiaCons,0);
  const pHoje=sel.reduce((s,o)=>s+o.mediaHora*horas,0);
  const pMes=sel.reduce((s,o)=>s+o.mensalEst,0);
  const pctD=totalDia>0?pDia/totalDia:0;
  const pctM=totalMensal>0?pMes/totalMensal:0;
  return`<div class="team-block">
    <div class="team-title" style="color:${barColor}">${label} — ${sel.length} ausente${sel.length>1?'s':''}</div>
    <div class="g3">
      <div class="m mr"><div class="ml">Hoje (${horas}h)</div><div class="mv">${fmt(pHoje)}</div></div>
      <div class="m mr"><div class="ml">Dia completo</div><div class="mv">${fmt(pDia)}</div></div>
      <div class="m mr"><div class="ml">Mensal est.</div><div class="mv">${fmt(pMes)}</div></div>
    </div>
    <div class="g2">
      <div class="m mr"><div class="ml">% faturamento dia</div><div class="mv">${pct(pctD)}</div></div>
      <div class="m mr"><div class="ml">% faturamento mês</div><div class="mv">${pct(pctM)}</div></div>
    </div>
    <div style="margin-bottom:10px;">
      <div style="display:flex;justify-content:space-between;font-size:11px;color:#888;margin-bottom:3px;"><span>Impacto no dia</span><span style="color:#922b21;font-weight:600">${pct(pctD)}</span></div>
      <div class="pct-bar-bg"><div class="pct-bar" style="width:${Math.min(pctD*100,100).toFixed(0)}%;background:${barColor};"></div></div>
    </div>
    ${sel.map(o=>`<div class="row-item">
      <span class="row-name">${o.name}</span>
      <div class="row-vals">
        <span>hoje: <b>${fmt(o.mediaHora*horas)}</b></span>
        <span>dia: <b>${fmt(o.mediaDiaCons)}</b></span>
        <span>mês: <b>${fmt(o.mensalEst)}</b></span>
        <span style="color:#c0392b">dia: <b style="color:#922b21">${pct(totalDia>0?o.mediaDiaCons/totalDia:0)}</b></span>
      </div>
    </div>`).join('')}
  </div>`;
}

function renderP1(){
  const box=document.getElementById('p1-result');
  if(selP1.size===0){box.innerHTML='<div class="empty">Selecione um ou mais operadores acima</div>';return;}
  const sel=[...selP1].map(i=>ops[i]);
  const uD=sel.filter(o=>o.equipe==='UME'&&o.sub==='Discador');
  const uJ=sel.filter(o=>o.equipe==='UME'&&o.sub==='Jovem Aprendiz');
  const uW=sel.filter(o=>o.equipe==='UME'&&o.sub==='WhatsApp');
  const oD=sel.filter(o=>o.equipe==='ODRES'&&o.sub==='Discador');
  const oW=sel.filter(o=>o.equipe==='ODRES'&&o.sub==='WhatsApp');
  const pDia=sel.reduce((s,o)=>s+o.mediaDiaCons,0);
  const pHoje=sel.reduce((s,o)=>s+o.mediaHora*horas,0);
  const pMes=sel.reduce((s,o)=>s+o.mensalEst,0);
  box.innerHTML=`
    <div class="sec-label" style="margin-bottom:10px;">Total — ${sel.length} operador${sel.length>1?'es':''} ausente${sel.length>1?'s':''}</div>
    <div class="g3">
      <div class="m mr"><div class="ml">Hoje (${horas}h)</div><div class="mv">${fmt(pHoje)}</div></div>
      <div class="m mr"><div class="ml">Dia completo</div><div class="mv">${fmt(pDia)}</div></div>
      <div class="m mr"><div class="ml">Mensal est.</div><div class="mv">${fmt(pMes)}</div></div>
    </div>
    <div class="g2">
      <div class="m mr"><div class="ml">% faturamento dia</div><div class="mv">${pct(pDia/totalDia)}</div></div>
      <div class="m mr"><div class="ml">% faturamento mês</div><div class="mv">${pct(pMes/totalMensal)}</div></div>
    </div>
    <hr class="divider">
    ${teamBlockP1('UME — Discador','#1a56db',uD)}
    ${teamBlockP1('UME — Jovem Aprendiz','#1e40af',uJ)}
    ${teamBlockP1('UME — WhatsApp','#7f56d9',uW)}
    ${teamBlockP1('ODRES — Discador','#0d7a55',oD)}
    ${teamBlockP1('ODRES — WhatsApp','#276749',oW)}
  `;
}

function renderP3(){
  const box=document.getElementById('p3-result');
  if(selP3.size===0){box.innerHTML='<div class="empty">Selecione um ou mais operadores acima</div>';return;}
  const sel=[...selP3].map(i=>ops[i]);
  const totalPorDia=diasNome.map((_,d)=>sel.reduce((s,o)=>s+o.mediaDia[d],0));
  const maxDia=Math.max(...totalPorDia,1);
  const dayCards=diasNome.map((nome,d)=>`
    <div class="day-card" style="background:${diasCor[d]};">
      <div class="dl" style="color:${diasTxt[d]}">${nome}</div>
      <div class="dv" style="color:${diasTxt[d]}">${fmt0(totalPorDia[d])}</div>
      <div class="mini-bar" style="background:${diasBar[d]};width:${(totalPorDia[d]/maxDia*100).toFixed(0)}%;margin:4px auto 0;"></div>
    </div>`).join('');
  const rows=sel.map(o=>{
    const cells=o.mediaDia.map((v,d)=>`<td>${v>0?fmt0(v):'—'}${v>0?`<div class="mini-bar" style="background:${diasBar[d]};width:${(v/maxDia*100).toFixed(0)}%;margin:2px auto 0;"></div>`:''}</td>`).join('');
    return`<tr><td class="left">${o.name}<br><span style="font-size:10px;color:#aaa;">${o.equipe} · ${o.tag}</span></td>${cells}</tr>`;
  }).join('');
  box.innerHTML=`
    <div class="sec-label" style="margin-bottom:10px;">Produção média por dia — ${sel.length} operador${sel.length>1?'es':''}</div>
    <div class="g5">${dayCards}</div>
    <hr class="divider">
    <div style="overflow-x:auto;">
      <table class="op-table">
        <thead><tr><th class="left">Operador</th>${diasNome.map(n=>`<th>${n}</th>`).join('')}</tr></thead>
        <tbody>${rows}</tbody>
      </table>
    </div>
    <div style="font-size:11px;color:#bbb;margin-top:8px;">Média dos dias com produção em março.</div>
  `;
}

function renderP4(){
  const cont=document.getElementById('p4-content');
  const totalFev=ops.reduce((s,o)=>s+o.fev.total,0);
  const totalMar=ops.reduce((s,o)=>s+o.mar.total,0);
  const varTotal=totalFev>0?((totalMar-totalFev)/totalFev*100):0;
  const umeOps=ops.filter(o=>o.equipe==='UME');
  const odresOps=ops.filter(o=>o.equipe==='ODRES');
  const umeFev=umeOps.reduce((s,o)=>s+o.fev.total,0);
  const umeMar=umeOps.reduce((s,o)=>s+o.mar.total,0);
  const odresFev=odresOps.reduce((s,o)=>s+o.fev.total,0);
  const odresMar=odresOps.reduce((s,o)=>s+o.mar.total,0);
  const varUme=umeFev>0?((umeMar-umeFev)/umeFev*100):0;
  const varOdres=odresFev>0?((odresMar-odresFev)/odresFev*100):0;

  function vBadge(fev,mar){
    if(fev===0&&mar===0)return'<span class="badge-eq">—</span>';
    if(fev===0)return'<span class="badge-new">novo</span>';
    if(mar===0)return'<span class="badge-desl">inativo</span>';
    const v=(mar-fev)/fev*100;
    return v>=0?`<span class="badge-up">+${v.toFixed(1)}%</span>`:`<span class="badge-dn">${v.toFixed(1)}%</span>`;
  }

  function teamTable(label,color,teamOps){
    const tFev=teamOps.reduce((s,o)=>s+o.fev.total,0);
    const tMar=teamOps.reduce((s,o)=>s+o.mar.total,0);
    const tVar=tFev>0?((tMar-tFev)/tFev*100):0;
    const rows=teamOps.map(o=>{
      const mb=Math.max(o.fev.total,o.mar.total,1);
      return`<tr>
        <td class="left">
          <div style="display:flex;align-items:center;gap:6px;">
            <div style="width:26px;height:26px;border-radius:50%;background:${o.color};color:${o.tc};display:flex;align-items:center;justify-content:center;font-size:10px;font-weight:600;flex-shrink:0;">${o.initials}</div>
            <div>
              <div style="font-weight:600;font-size:12px;">${o.name}</div>
              <div style="font-size:10px;color:#aaa;">${o.sub} · ${o.ativo?'Ativo':'Desligado'}</div>
            </div>
          </div>
        </td>
        <td>
          <div style="font-size:12px;">${fmtV(o.fev.total)}</div>
          <div class="pct-bar-bg" style="margin-top:3px;"><div class="pct-bar" style="width:${(o.fev.total/mb*100).toFixed(0)}%;background:#93c5fd;"></div></div>
        </td>
        <td>
          <div style="font-size:12px;">${fmtV(o.mar.total)}</div>
          <div class="pct-bar-bg" style="margin-top:3px;"><div class="pct-bar" style="width:${(o.mar.total/mb*100).toFixed(0)}%;background:#6ee7b7;"></div></div>
        </td>
        <td class="center">${vBadge(o.fev.total,o.mar.total)}</td>
      </tr>`;
    }).join('');
    const tvb=tVar>=0?`<span class="badge-up">+${tVar.toFixed(1)}%</span>`:`<span class="badge-dn">${tVar.toFixed(1)}%</span>`;
    return`<div class="team-block">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px;">
        <div class="team-title" style="color:${color};margin-bottom:0;">${label}</div>
        <div style="display:flex;gap:8px;font-size:12px;color:#888;">
          <span>Fev: <b style="color:#1a1a2e;">${fmt0(tFev)}</b></span>
          <span>Mar: <b style="color:#1a1a2e;">${fmt0(tMar)}</b></span>
          ${tvb}
        </div>
      </div>
      <div style="overflow-x:auto;">
        <table class="op-table">
          <thead><tr><th class="left">Operador</th><th style="text-align:right;">Fevereiro</th><th style="text-align:right;">Março</th><th>Variação</th></tr></thead>
          <tbody>${rows}</tbody>
        </table>
      </div>
    </div>`;
  }

  cont.innerHTML=`
    <div class="g4" style="margin-bottom:16px;">
      <div class="m mb"><div class="ml">Total Fevereiro</div><div class="mv">${fmt0(totalFev)}</div></div>
      <div class="m mg"><div class="ml">Total Março</div><div class="mv">${fmt0(totalMar)}</div></div>
      <div class="m ${varTotal>=0?'mg':'mr'}"><div class="ml">Variação geral</div><div class="mv">${varTotal>=0?'+':''}${varTotal.toFixed(1)}%</div></div>
      <div class="m mn"><div class="ml">Diferença</div><div class="mv">${fmt0(Math.abs(totalMar-totalFev))}</div></div>
    </div>
    <div class="g2" style="margin-bottom:16px;">
      <div class="m mn">
        <div class="ml">UME — Fev vs Mar</div>
        <div style="display:flex;justify-content:space-between;align-items:center;margin-top:4px;">
          <div class="mv">${fmt0(umeFev)} → ${fmt0(umeMar)}</div>
          <span class="${varUme>=0?'badge-up':'badge-dn'}">${varUme>=0?'+':''}${varUme.toFixed(1)}%</span>
        </div>
      </div>
      <div class="m mn">
        <div class="ml">ODRES — Fev vs Mar</div>
        <div style="display:flex;justify-content:space-between;align-items:center;margin-top:4px;">
          <div class="mv">${fmt0(odresFev)} → ${fmt0(odresMar)}</div>
          <span class="${varOdres>=0?'badge-up':'badge-dn'}">${varOdres>=0?'+':''}${varOdres.toFixed(1)}%</span>
        </div>
      </div>
    </div>
    <div style="display:flex;gap:12px;margin-bottom:12px;font-size:12px;color:#888;">
      <span style="display:flex;align-items:center;gap:4px;"><span style="width:10px;height:10px;border-radius:2px;background:#93c5fd;display:inline-block;"></span>Fevereiro</span>
      <span style="display:flex;align-items:center;gap:4px;"><span style="width:10px;height:10px;border-radius:2px;background:#6ee7b7;display:inline-block;"></span>Março</span>
    </div>
    ${teamTable('UME','#1a56db',umeOps)}
    ${teamTable('ODRES','#0d7a55',odresOps)}
  `;
}
</script>
</body>
</html>
