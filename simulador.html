<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Simulador de Madurez Asociativa · EAN Rural × ICONE ialabs para CNCH</title>
<style>
  :root{
    --navy:#0F1B2D;
    --navy-2:#1A2230;
    --cyan:#0AA6C2;
    --cyan-2:#7FD6E3;
    --green:#0F6E3D;
    --chocolate:#4E2A14;
    --grey:#5A6573;
    --light:#F4F6F8;
    --line:#D8DEE6;
    --accent:#EAF6F3;
    --red:#B53A2F;
    --amber:#C77B0C;
  }
  *{box-sizing:border-box;-webkit-print-color-adjust:exact;print-color-adjust:exact}
  html,body{margin:0;padding:0;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Calibri,Roboto,Helvetica,Arial,sans-serif;background:#EEF1F4;color:var(--navy)}
  .container{max-width:1280px;margin:0 auto;padding:0 28px}

  /* ===== HEADER (band) ===== */
  header.band{background:linear-gradient(135deg,var(--navy) 0%,#11253F 100%);color:#fff;padding:22px 0 26px}
  header .row{display:flex;align-items:center;justify-content:space-between;gap:24px;flex-wrap:wrap}
  header .brand .eyebrow{font-size:11px;letter-spacing:.22em;color:#9FB6D4;font-weight:700;margin-bottom:6px}
  header .brand .title{font-size:24px;font-weight:800;letter-spacing:.02em}
  header .brand .title .x{color:var(--cyan);margin:0 8px}
  header .brand .subtitle{font-size:13px;color:#C9D4E5;margin-top:6px;font-style:italic}
  header .meta{font-size:12px;color:#9FB6D4;text-align:right;line-height:1.5}
  header .meta strong{color:#fff;font-weight:700}

  /* ===== HERO ===== */
  .hero{padding:30px 0 14px}
  .hero h1{font-size:30px;margin:0 0 8px;letter-spacing:-.01em}
  .hero p.lead{font-size:16px;color:var(--grey);margin:0;max-width:880px;line-height:1.55}

  /* ===== ASOC INPUT ===== */
  .asoc-card{margin:22px 0 24px;background:#fff;border:1px solid var(--line);border-radius:14px;padding:22px;display:grid;grid-template-columns:1.4fr 1fr 1fr auto;gap:18px;align-items:end}
  .field label{display:block;font-size:12px;font-weight:700;letter-spacing:.08em;color:var(--grey);text-transform:uppercase;margin-bottom:6px}
  .field input{width:100%;border:1px solid var(--line);border-radius:8px;padding:10px 12px;font-size:14px;font-family:inherit;color:var(--navy);background:#fff;transition:border-color .15s}
  .field input:focus{outline:none;border-color:var(--cyan);box-shadow:0 0 0 3px rgba(10,166,194,.15)}
  .asoc-actions{display:flex;gap:8px;flex-wrap:wrap}
  .btn{border:none;cursor:pointer;font-family:inherit;font-weight:700;font-size:13px;padding:10px 16px;border-radius:8px;transition:all .15s;letter-spacing:.02em}
  .btn-primary{background:var(--cyan);color:#fff}
  .btn-primary:hover{background:#089ab4}
  .btn-ghost{background:transparent;color:var(--navy);border:1px solid var(--line)}
  .btn-ghost:hover{border-color:var(--navy)}
  .btn-dark{background:var(--navy);color:#fff}
  .btn-dark:hover{background:#04101F}

  /* ===== SECTION HEADER ===== */
  .sec-title{display:flex;align-items:center;gap:12px;margin:30px 0 14px}
  .sec-title .dot{width:10px;height:10px;border-radius:50%}
  .sec-title h2{font-size:15px;letter-spacing:.18em;text-transform:uppercase;margin:0;font-weight:800}
  .sec-title.td .dot{background:var(--cyan)}
  .sec-title.ef .dot{background:var(--green)}
  .sec-title.res .dot{background:var(--chocolate)}

  /* ===== QUESTION CARDS ===== */
  .qgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(380px,1fr));gap:16px}
  .qcard{background:#fff;border:1px solid var(--line);border-radius:12px;padding:18px;display:flex;flex-direction:column;gap:14px;transition:border-color .2s,box-shadow .2s;position:relative;overflow:hidden}
  .qcard::before{content:"";position:absolute;top:0;left:0;width:4px;height:100%;background:var(--line);transition:background .2s}
  .qcard.td-card::before{background:var(--cyan-2)}
  .qcard.ef-card::before{background:#94C9A8}
  .qcard.answered::before{background:var(--navy)}
  .qcard.answered{box-shadow:0 1px 3px rgba(0,0,0,.04)}
  .qcard .qnum{font-size:11px;font-weight:800;color:var(--grey);letter-spacing:.16em}
  .qcard .qtext{font-size:14px;line-height:1.45;color:var(--navy);font-weight:600}
  .opts{display:flex;flex-direction:column;gap:6px}
  .opt{display:flex;gap:10px;padding:9px 11px;border:1px solid var(--line);border-radius:7px;cursor:pointer;transition:all .15s;font-size:13px;line-height:1.35;align-items:flex-start}
  .opt:hover{border-color:var(--navy);background:var(--light)}
  .opt input{margin-top:2px;accent-color:var(--cyan)}
  .opt.selected{background:var(--accent);border-color:var(--cyan);color:var(--navy)}
  .opt.selected .points{background:var(--cyan);color:#fff}
  .opt .points{min-width:22px;height:22px;border-radius:6px;background:#E5EAF1;color:var(--navy);font-weight:800;font-size:12px;display:inline-flex;align-items:center;justify-content:center;margin-left:auto;flex-shrink:0}

  /* ===== RESULTS PANEL ===== */
  .results{margin:36px 0 32px;display:grid;grid-template-columns:1.2fr 1fr;gap:20px}
  .res-card{background:#fff;border-radius:14px;border:1px solid var(--line);padding:24px}
  .res-card.dark{background:linear-gradient(135deg,var(--navy) 0%,#11253F 100%);color:#fff;border:none}
  .res-card.dark .eyebrow{color:#9FB6D4}
  .res-card .eyebrow{font-size:11px;letter-spacing:.22em;color:var(--grey);font-weight:800;text-transform:uppercase;margin-bottom:14px}
  .score-headline{display:flex;align-items:baseline;gap:14px;margin-bottom:8px}
  .score-headline .big{font-size:62px;font-weight:800;line-height:.95;letter-spacing:-.02em}
  .score-headline .of{font-size:18px;color:#9FB6D4}
  .score-headline .badge{margin-left:auto;padding:6px 12px;border-radius:999px;font-size:12px;font-weight:800;letter-spacing:.06em;text-transform:uppercase}
  .badge.inicial{background:var(--red);color:#fff}
  .badge.transicion{background:var(--amber);color:#fff}
  .badge.consolidacion{background:var(--cyan);color:#fff}
  .badge.avanzada{background:var(--green);color:#fff}
  .score-desc{font-size:13px;color:#C9D4E5;line-height:1.55;margin:0 0 18px}
  .ejes{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:8px}
  .eje{padding:14px 16px;border-radius:10px;background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.08)}
  .eje .label{font-size:11px;letter-spacing:.18em;text-transform:uppercase;color:#9FB6D4;font-weight:700;margin-bottom:6px}
  .eje .value{font-size:26px;font-weight:800;line-height:1}
  .eje .out{font-size:13px;color:#9FB6D4;margin-left:4px}
  .bar{height:6px;background:rgba(255,255,255,.1);border-radius:4px;margin-top:10px;overflow:hidden}
  .bar > div{height:100%;border-radius:4px;transition:width .4s ease}
  .bar.td > div{background:var(--cyan)}
  .bar.ef > div{background:#3FA869}

  /* radar */
  .radar-wrap{display:flex;align-items:center;justify-content:center;min-height:340px}
  .radar svg{max-width:100%;height:auto}

  /* plan */
  .plan{margin-top:22px;background:#fff;border-radius:14px;border:1px solid var(--line);padding:24px}
  .plan h3{margin:0 0 6px;font-size:18px}
  .plan .sub{color:var(--grey);font-size:13px;margin-bottom:18px}
  .plan .actions{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:14px}
  .action{border-left:4px solid var(--cyan);background:var(--light);padding:14px 16px;border-radius:0 10px 10px 0}
  .action .prio{font-size:11px;font-weight:800;letter-spacing:.14em;text-transform:uppercase;color:var(--cyan);margin-bottom:6px}
  .action.high{border-color:var(--red)}
  .action.high .prio{color:var(--red)}
  .action.med{border-color:var(--amber)}
  .action.med .prio{color:var(--amber)}
  .action .what{font-weight:700;font-size:14px;line-height:1.4;margin-bottom:4px}
  .action .how{font-size:13px;color:var(--grey);line-height:1.5}
  .empty-plan{text-align:center;padding:30px;color:var(--grey);font-size:14px;border:2px dashed var(--line);border-radius:10px}

  /* benchmark */
  .benchmark{margin-top:22px;background:#fff;border-radius:14px;border:1px solid var(--line);padding:24px}
  .benchmark h3{margin:0 0 6px;font-size:18px}
  .benchmark .sub{color:var(--grey);font-size:13px;margin-bottom:18px}
  .bench-table{width:100%;border-collapse:collapse;font-size:13px}
  .bench-table th{text-align:left;padding:10px 12px;background:var(--navy);color:#fff;font-size:11px;letter-spacing:.14em;text-transform:uppercase;font-weight:800}
  .bench-table th:first-child{border-radius:8px 0 0 8px}
  .bench-table th:last-child{border-radius:0 8px 8px 0;text-align:center}
  .bench-table td{padding:11px 12px;border-bottom:1px solid var(--line)}
  .bench-table td:last-child{text-align:center;font-weight:700}
  .bench-table tr:hover{background:var(--light)}
  .pill{display:inline-block;padding:3px 10px;border-radius:999px;font-size:11px;font-weight:800;text-transform:uppercase;letter-spacing:.06em}
  .pill.inicial{background:#FCE0DD;color:var(--red)}
  .pill.transicion{background:#FBEAD2;color:var(--amber)}
  .pill.consolidacion{background:#DCF1F5;color:#0A7589}
  .pill.avanzada{background:#D7EBDF;color:var(--green)}
  .empty-bench{padding:18px;color:var(--grey);font-size:14px;text-align:center;border:2px dashed var(--line);border-radius:10px}
  .row-delete{background:transparent;border:none;color:var(--red);cursor:pointer;font-size:12px;font-weight:700}

  /* footer */
  footer{margin:40px 0 24px;text-align:center;color:var(--grey);font-size:12px;line-height:1.6}
  footer strong{color:var(--navy)}

  @media (max-width: 900px){
    .results{grid-template-columns:1fr}
    .asoc-card{grid-template-columns:1fr;gap:12px}
    .ejes{grid-template-columns:1fr}
    header .row{flex-direction:column;align-items:flex-start}
    header .meta{text-align:left}
  }
  @media print{
    body{background:#fff}
    .asoc-actions, .btn, .row-delete{display:none !important}
    header.band{break-inside:avoid}
    .results, .plan, .benchmark{break-inside:avoid}
  }
</style>
</head>
<body>

<header class="band">
  <div class="container row">
    <div class="brand">
      <div class="eyebrow">ALIANZA ESTRATÉGICA</div>
      <div class="title">EAN Rural<span class="x">×</span>ICONE ialabs</div>
      <div class="subtitle">Simulador de Madurez Asociativa  ·  Propuesta para Compañía Nacional de Chocolates</div>
    </div>
    <div class="meta">
      <strong>Demo en vivo</strong><br>
      Capa analítica sobre el instrumento CNCH<br>
      <span id="today"></span>
    </div>
  </div>
</header>

<main class="container">

  <section class="hero">
    <h1>Diagnóstico de Madurez Asociativa</h1>
    <p class="lead">Captura las 10 preguntas del instrumento CNCH y obtén — en tiempo real — el score, nivel de madurez, gráfico radar y plan de acción auto-generado por cada asociación. Esta es la capa analítica que la alianza EAN Rural × ICONE entregaría sobre el Dashboard propio de CNCH.</p>
  </section>

  <div class="asoc-card">
    <div class="field">
      <label>Nombre de la asociación</label>
      <input id="asocName" type="text" placeholder="Ej. ASOPROCACAO Arauquita">
    </div>
    <div class="field">
      <label>Municipio / Región</label>
      <input id="asocRegion" type="text" placeholder="Ej. Arauca">
    </div>
    <div class="field">
      <label>N° de productores asociados</label>
      <input id="asocCount" type="number" min="0" placeholder="Ej. 120">
    </div>
    <div class="asoc-actions">
      <button class="btn btn-primary" id="saveBtn">Guardar y comparar</button>
      <button class="btn btn-ghost" id="resetBtn">Limpiar</button>
      <button class="btn btn-dark" id="printBtn">Imprimir / PDF</button>
    </div>
  </div>

  <!-- TRANSFORMACIÓN DIGITAL -->
  <div class="sec-title td">
    <span class="dot"></span>
    <h2>EJE 1 · Transformación Digital</h2>
  </div>
  <div class="qgrid" id="grid-td"></div>

  <!-- EDUCACIÓN FINANCIERA -->
  <div class="sec-title ef">
    <span class="dot"></span>
    <h2>EJE 2 · Educación Financiera</h2>
  </div>
  <div class="qgrid" id="grid-ef"></div>

  <!-- RESULTADOS -->
  <div class="sec-title res">
    <span class="dot"></span>
    <h2>Resultados en vivo</h2>
  </div>

  <section class="results">
    <div class="res-card dark">
      <div class="eyebrow">Score global y nivel de madurez</div>
      <div class="score-headline">
        <span class="big" id="bigScore">0</span>
        <span class="of">/ 20 puntos</span>
        <span class="badge inicial" id="badge">Inicial</span>
      </div>
      <p class="score-desc" id="scoreDesc">Responde el cuestionario para ver el diagnóstico de la asociación.</p>
      <div class="ejes">
        <div class="eje">
          <div class="label">Transformación Digital</div>
          <div class="value"><span id="tdScore">0</span><span class="out">/10</span></div>
          <div class="bar td"><div id="tdBar" style="width:0%"></div></div>
        </div>
        <div class="eje">
          <div class="label">Educación Financiera</div>
          <div class="value"><span id="efScore">0</span><span class="out">/10</span></div>
          <div class="bar ef"><div id="efBar" style="width:0%"></div></div>
        </div>
      </div>
    </div>
    <div class="res-card">
      <div class="eyebrow">Perfil de Madurez por dimensión</div>
      <div class="radar-wrap"><div class="radar" id="radar"></div></div>
    </div>
  </section>

  <!-- PLAN DE ACCIÓN -->
  <div class="plan">
    <h3>Plan de acción auto-generado por IA</h3>
    <p class="sub">Generado a partir de las brechas detectadas en el instrumento. La alianza EAN Rural × ICONE convierte cada brecha en una acción concreta y medible.</p>
    <div class="actions" id="plan"></div>
  </div>

  <!-- BENCHMARK -->
  <div class="benchmark">
    <h3>Benchmark entre asociaciones</h3>
    <p class="sub">Cada asociación guardada queda comparable bajo el mismo modelo. Esta capa permitiría a CNCH ver el avance trimestral en todas las asociaciones de su red.</p>
    <div id="benchWrap"></div>
  </div>

</main>

<footer>
  <strong>Alianza EAN Rural × ICONE ialabs</strong>  ·  Propuesta para Compañía Nacional de Chocolates<br>
  William Mojica — Líder Impacta Rural y Diverso · wfmojica@universidadean.edu.co  ·
  Jorge Hugo Pérez — Founder & CEO ICONE ialabs · jorgehugoperez@iconeialabs.com · +57 315 894 0980
</footer>

<script>
// =========================================================
// INSTRUMENTO CNCH — definición
// =========================================================
const QUESTIONS = [
  { id:"td1", eje:"td", short:"Historial digitalizado de comercialización",
    text:"¿La organización cuenta con historial digitalizado de su comercialización?",
    opts:["Sí cuenta con historial digitalizado","Sí cuenta con historial físico pero no digital","No cuenta con historial ni físico ni digital"] },
  { id:"td2", eje:"td", short:"Equipos de cómputo en operación",
    text:"¿La organización cuenta con equipos de cómputo y los utilizan en su operación?",
    opts:["Sí cuentan con equipos y actualmente los utilizan","Sí cuentan con equipos pero están obsoletos o no los utilizan","No cuenta con equipos"] },
  { id:"td3", eje:"td", short:"Internet en punto de compra",
    text:"¿La organización tiene acceso a internet en el punto de compra?",
    opts:["Sí cuentan con acceso y actualmente lo utilizan","Sí cuentan con acceso pero es deficiente","No cuenta con acceso a internet"] },
  { id:"td4", eje:"td", short:"Soluciones tecnológicas implementadas",
    text:"¿La organización ha implementado soluciones tecnológicas en su operación (apps, software contable, inventarios, facturación)?",
    opts:["Sí cuentan con herramientas y actualmente las utilizan","Sí cuentan con herramientas pero no las utilizan o no saben usarlas","No cuenta con herramientas"] },
  { id:"td5", eje:"td", short:"Capacitación tecnológica a la Junta",
    text:"¿Los miembros de la Junta Directiva han recibido capacitación en el uso de herramientas tecnológicas?",
    opts:["Todos los miembros han recibido capacitación exhaustiva","Esfuerzos limitados o parciales en algunos miembros","Los miembros no han recibido capacitación"] },
  { id:"ef1", eje:"ef", short:"Ingresos vs. gastos",
    text:"¿Los ingresos de la organización superan a sus gastos, permitiendo acumular patrimonio?",
    opts:["Los ingresos son mayores a los gastos","Los ingresos son iguales a los gastos","Los gastos son mayores a los ingresos"] },
  { id:"ef2", eje:"ef", short:"Programas de ahorro",
    text:"¿La organización implementa, promueve o fomenta programas para incentivar el ahorro de los productores?",
    opts:["Programas activos, promovidos y exitosos","Esfuerzos limitados o esporádicos","No implementa programas de ahorro"] },
  { id:"ef3", eje:"ef", short:"Costo de comercialización por kg",
    text:"¿La organización tiene definido el cálculo del costo de comercialización por kg de cacao? (debe conocerlo la junta directiva)",
    opts:["Definido y con seguimiento activo","Definido pero no implementado","No tiene definido el cálculo"] },
  { id:"ef4", eje:"ef", short:"Registros en finca",
    text:"¿La organización promueve activamente registros en finca de costos de producción e ingresos por ventas?",
    opts:["Lo promueven y los productores lo implementan","Lo promueven pero los productores no lo implementan","No lo promueven"] },
  { id:"ef5", eje:"ef", short:"Comprobantes a agricultores",
    text:"¿La organización entrega comprobantes/facturas a los agricultores por las entregas de cacao?",
    opts:["Siempre entrega comprobante con soporte","Entrega ocasionalmente algún tipo de comprobante","No entrega ningún tipo de comprobante"] },
];

// Acciones recomendadas por pregunta cuando el score es 0 (high), 1 (med), 2 (none)
const ACTIONS = {
  td1:{ what:"Digitalizar el historial de comercialización", how:"Implementar plantilla en la nube (Sheets/Excel) con plantillas pre-cargadas EAN × ICONE para las últimas 3 cosechas." },
  td2:{ what:"Equipar al punto de compra con cómputo básico", how:"Definir paquete mínimo viable (laptop o tablet) y capacitación de uso. Plantilla de inversión incluida." },
  td3:{ what:"Resolver conectividad en el punto de compra", how:"Diagnóstico de cobertura, alternativas satelitales y operadores. Manual de continuidad operativa offline-first." },
  td4:{ what:"Implementar herramientas digitales mínimas viables", how:"App simple de registro de compras + plantilla con IA para conciliación. ICONE lidera implementación." },
  td5:{ what:"Capacitar a la Junta Directiva en herramientas digitales", how:"Diplomado certificado EAN ‘Junta Directiva Digital’ — 8 a 12 semanas, modalidad híbrida." },
  ef1:{ what:"Estabilizar la ecuación ingresos vs. gastos", how:"Mentoría 1:1 ICONE Method al gerente + plantilla de presupuesto mensual con semáforo." },
  ef2:{ what:"Diseñar e implementar programa de ahorro asociativo", how:"Modelo de fondo de ahorro entre productores con o sin aliado financiero. Pieza diferenciadora." },
  ef3:{ what:"Definir y monitorear costo de comercialización por kg", how:"Hoja conectada con cálculo del costo unitario y dashboard mensual para la junta." },
  ef4:{ what:"Crear cultura de registros en finca", how:"Capacitación a productores y entrega de bitácora física + app simple. Indicador trimestral." },
  ef5:{ what:"Formalizar comprobantes y facturación", how:"Implementar comprobantes digitales/físicos con soporte. Base para certificaciones y Ley antideforestación UE." },
};

const LEVELS = [
  { min:0,  max:5,  key:"inicial",       name:"Inicial",       desc:"Brecha amplia. La asociación necesita intervención profunda y acompañamiento sostenido en al menos uno de los dos ejes para alcanzar un piso operativo confiable." },
  { min:6,  max:10, key:"transicion",    name:"En transición", desc:"Hay fundamentos parciales. La asociación tiene avances aislados, pero todavía no consolida un sistema confiable de gestión digital y financiera." },
  { min:11, max:15, key:"consolidacion", name:"En consolidación", desc:"Buena base instalada. La asociación opera con criterio, requiere optimización selectiva y disciplina en los puntos blandos detectados." },
  { min:16, max:20, key:"avanzada",      name:"Avanzada",      desc:"Madurez alta. La asociación puede actuar como referente regional y candidata a programas de fortalecimiento de segundo nivel y certificaciones internacionales." },
];

const STORAGE_KEY = "cnch_simulador_asociaciones_v1";

// =========================================================
// RENDER cuestionario
// =========================================================
const state = { answers:{} };

function renderQuestion(q, idx){
  return `
    <div class="qcard ${q.eje}-card" data-id="${q.id}">
      <div class="qnum">PREGUNTA ${String(idx+1).padStart(2,"0")} · ${q.eje==="td"?"TRANSFORMACIÓN DIGITAL":"EDUCACIÓN FINANCIERA"}</div>
      <div class="qtext">${q.text}</div>
      <div class="opts">
        ${q.opts.map((o, i) => {
          const score = 2 - i;
          return `<label class="opt" data-q="${q.id}" data-score="${score}">
            <input type="radio" name="${q.id}" value="${score}">
            <span>${o}</span>
            <span class="points">${score}</span>
          </label>`;
        }).join("")}
      </div>
    </div>`;
}

function mountQuestions(){
  const td = QUESTIONS.filter(q=>q.eje==="td");
  const ef = QUESTIONS.filter(q=>q.eje==="ef");
  document.getElementById("grid-td").innerHTML = td.map((q,i)=>renderQuestion(q,i)).join("");
  document.getElementById("grid-ef").innerHTML = ef.map((q,i)=>renderQuestion(q,i+5)).join("");
  document.querySelectorAll(".opt").forEach(el => {
    el.addEventListener("click", () => {
      const q = el.dataset.q, s = parseInt(el.dataset.score,10);
      state.answers[q] = s;
      document.querySelectorAll(`.opt[data-q="${q}"]`).forEach(o=>o.classList.remove("selected"));
      el.classList.add("selected");
      el.querySelector("input").checked = true;
      document.querySelector(`.qcard[data-id="${q}"]`).classList.add("answered");
      update();
    });
  });
}

// =========================================================
// CÁLCULO + UI
// =========================================================
function totals(answers){
  const tdQs = QUESTIONS.filter(q=>q.eje==="td");
  const efQs = QUESTIONS.filter(q=>q.eje==="ef");
  const td = tdQs.reduce((a,q)=>a + (answers[q.id] ?? 0), 0);
  const ef = efQs.reduce((a,q)=>a + (answers[q.id] ?? 0), 0);
  return { td, ef, total: td+ef };
}
function levelOf(total){ return LEVELS.find(l => total >= l.min && total <= l.max); }

function update(){
  const t = totals(state.answers);
  const lvl = levelOf(t.total);

  document.getElementById("bigScore").textContent = t.total;
  document.getElementById("tdScore").textContent = t.td;
  document.getElementById("efScore").textContent = t.ef;
  document.getElementById("tdBar").style.width = (t.td/10*100)+"%";
  document.getElementById("efBar").style.width = (t.ef/10*100)+"%";

  const badge = document.getElementById("badge");
  badge.className = "badge " + lvl.key;
  badge.textContent = lvl.name;
  document.getElementById("scoreDesc").textContent = lvl.desc;

  renderRadar();
  renderPlan();
}

// =========================================================
// RADAR SVG
// =========================================================
function renderRadar(){
  const target = document.getElementById("radar");
  const W = 420, H = 340, cx = W/2, cy = H/2 + 6, R = 120;
  const items = QUESTIONS.map(q => ({ label:q.short, score: state.answers[q.id] ?? 0, eje:q.eje }));
  const n = items.length;
  const angle = i => -Math.PI/2 + (2*Math.PI*i)/n;
  const point = (i,r) => [cx + Math.cos(angle(i))*r, cy + Math.sin(angle(i))*r];

  // grid rings (0.5, 1, 1.5, 2)
  const rings = [0.5,1,1.5,2].map(v => {
    const pts = Array.from({length:n}, (_,i)=>point(i, R*v/2));
    return `<polygon points="${pts.map(p=>p.join(",")).join(" ")}" fill="none" stroke="#D8DEE6" stroke-width="1" />`;
  }).join("");

  // axes lines
  const axes = Array.from({length:n}, (_,i) => {
    const [x,y] = point(i, R);
    return `<line x1="${cx}" y1="${cy}" x2="${x}" y2="${y}" stroke="#E5EAF1" stroke-width="1" />`;
  }).join("");

  // data polygon
  const dataPts = items.map((it,i) => point(i, R*it.score/2));
  const dataPoly = `<polygon points="${dataPts.map(p=>p.join(",")).join(" ")}" fill="rgba(10,166,194,.22)" stroke="#0AA6C2" stroke-width="2" />`;
  const dots = items.map((it,i) => {
    const [x,y] = point(i, R*it.score/2);
    const color = it.eje==="td" ? "#0AA6C2" : "#0F6E3D";
    return `<circle cx="${x}" cy="${y}" r="4" fill="${color}" stroke="#fff" stroke-width="1.5" />`;
  }).join("");

  // labels
  const labels = items.map((it,i)=>{
    const [x,y] = point(i, R+22);
    const color = it.eje==="td" ? "#0AA6C2" : "#0F6E3D";
    // Truncate long labels
    const short = it.label.length > 20 ? it.label.substring(0,18)+"…" : it.label;
    // Position-aware anchor
    const a = angle(i);
    let anchor = "middle";
    if (Math.cos(a) > 0.3) anchor = "start";
    else if (Math.cos(a) < -0.3) anchor = "end";
    return `<text x="${x}" y="${y+4}" text-anchor="${anchor}" font-size="10" font-weight="700" fill="${color}">${short}</text>`;
  }).join("");

  target.innerHTML = `<svg viewBox="0 0 ${W} ${H}" width="${W}" height="${H}">
    ${rings}${axes}${dataPoly}${dots}${labels}
  </svg>`;
}

// =========================================================
// PLAN DE ACCIÓN
// =========================================================
function renderPlan(){
  const plan = document.getElementById("plan");
  const gaps = QUESTIONS.map(q => ({ q, score: state.answers[q.id] }))
    .filter(x => x.score !== undefined && x.score < 2)
    .sort((a,b) => a.score - b.score);

  if (Object.keys(state.answers).length === 0){
    plan.innerHTML = `<div class="empty-plan">El plan de acción aparece aquí en cuanto se respondan las preguntas. Cada brecha genera una acción priorizada por la alianza EAN Rural × ICONE.</div>`;
    return;
  }
  if (gaps.length === 0){
    plan.innerHTML = `<div class="empty-plan" style="border-color:#0F6E3D;color:#0F6E3D;background:#EFF8F3"><strong>Sin brechas detectadas.</strong> La asociación califica como referente. Plan sugerido: programa de fortalecimiento de segundo nivel (certificaciones internacionales, exportación, formalización avanzada).</div>`;
    return;
  }

  plan.innerHTML = gaps.map(g => {
    const cls = g.score === 0 ? "high" : "med";
    const lbl = g.score === 0 ? "Prioridad alta" : "Prioridad media";
    const a = ACTIONS[g.q.id];
    return `<div class="action ${cls}">
      <div class="prio">${lbl}  ·  ${g.q.eje==="td"?"Digital":"Financiero"}</div>
      <div class="what">${a.what}</div>
      <div class="how">${a.how}</div>
    </div>`;
  }).join("");
}

// =========================================================
// BENCHMARK / persistencia
// =========================================================
function loadStored(){
  try { return JSON.parse(localStorage.getItem(STORAGE_KEY)) || []; }
  catch(e){ return []; }
}
function saveStored(list){ localStorage.setItem(STORAGE_KEY, JSON.stringify(list)); }

function renderBench(){
  const list = loadStored();
  const wrap = document.getElementById("benchWrap");
  if (list.length === 0){
    wrap.innerHTML = `<div class="empty-bench">Aún no hay asociaciones guardadas. Completa el cuestionario y haz clic en <strong>Guardar y comparar</strong> para ver el benchmark.</div>`;
    return;
  }
  list.sort((a,b)=>b.total - a.total);
  wrap.innerHTML = `<table class="bench-table">
    <thead><tr>
      <th>Asociación</th><th>Región</th><th>Productores</th><th>T. Digital</th><th>E. Financiera</th><th>Total</th><th>Nivel</th><th></th>
    </tr></thead>
    <tbody>
      ${list.map((a,i)=>`<tr>
        <td><strong>${escapeHtml(a.name)}</strong></td>
        <td>${escapeHtml(a.region||"—")}</td>
        <td>${a.count||"—"}</td>
        <td>${a.td}/10</td>
        <td>${a.ef}/10</td>
        <td>${a.total}/20</td>
        <td><span class="pill ${a.level.key}">${a.level.name}</span></td>
        <td><button class="row-delete" data-idx="${i}">Quitar</button></td>
      </tr>`).join("")}
    </tbody></table>`;

  wrap.querySelectorAll(".row-delete").forEach(b=>{
    b.addEventListener("click", ()=>{
      const list = loadStored();
      list.splice(parseInt(b.dataset.idx,10),1);
      saveStored(list); renderBench();
    });
  });
}

function escapeHtml(s){ return String(s).replace(/[&<>"']/g, c => ({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c])); }

// =========================================================
// Botones
// =========================================================
function bindActions(){
  document.getElementById("saveBtn").addEventListener("click", ()=>{
    const name = document.getElementById("asocName").value.trim();
    if (!name){ alert("Pon un nombre de asociación antes de guardar."); return; }
    const answered = Object.keys(state.answers).length;
    if (answered < 10){ if (!confirm(`Aún faltan ${10-answered} preguntas por responder. ¿Guardar de todos modos?`)) return; }
    const t = totals(state.answers);
    const lvl = levelOf(t.total);
    const list = loadStored();
    list.push({
      name, region: document.getElementById("asocRegion").value.trim(),
      count: document.getElementById("asocCount").value.trim(),
      td:t.td, ef:t.ef, total:t.total, level:{key:lvl.key,name:lvl.name},
      answers:{...state.answers}, savedAt: new Date().toISOString()
    });
    saveStored(list);
    renderBench();
    // Visual feedback
    const btn = document.getElementById("saveBtn");
    const original = btn.textContent;
    btn.textContent = "✓ Guardada";
    btn.style.background = "#0F6E3D";
    setTimeout(()=>{ btn.textContent = original; btn.style.background = ""; }, 1400);
  });

  document.getElementById("resetBtn").addEventListener("click", ()=>{
    state.answers = {};
    document.querySelectorAll(".opt.selected").forEach(o=>o.classList.remove("selected"));
    document.querySelectorAll(".qcard.answered").forEach(c=>c.classList.remove("answered"));
    document.querySelectorAll('input[type="radio"]').forEach(r=>r.checked=false);
    document.getElementById("asocName").value = "";
    document.getElementById("asocRegion").value = "";
    document.getElementById("asocCount").value = "";
    update();
  });

  document.getElementById("printBtn").addEventListener("click", ()=>window.print());
}

// =========================================================
// INIT
// =========================================================
function init(){
  const fecha = new Date().toLocaleDateString("es-CO",{year:"numeric",month:"long",day:"numeric"});
  document.getElementById("today").textContent = fecha;
  mountQuestions();
  bindActions();
  update();
  renderBench();
}
init();
</script>
</body>
</html>
