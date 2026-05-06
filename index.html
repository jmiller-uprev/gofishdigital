<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Joybird × Go Fish Digital — 2026 Strategy</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=DM+Sans:wght@300;400;500;600&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --navy: #0A1628;
    --navy-mid: #112040;
    --navy-light: #1a3060;
    --cream: #F5F0E8;
    --cream-dim: #c8c0b0;
    --coral: #E8714A;
    --gold: #C9A84C;
    --gold-light: #e8c46a;
    --green: #4CAF7D;
    --red: #E05252;
    --blue-accent: #4A90D9;
    --white: #ffffff;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--navy);
    color: var(--cream);
    overflow-x: hidden;
  }

  /* ── TOP NAV ── */
  #topnav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    display: flex; align-items: center; justify-content: space-between;
    padding: 0 48px;
    height: 56px;
    background: rgba(10,22,40,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid rgba(201,168,76,0.15);
  }
  #topnav .brand { font-family: 'DM Mono', monospace; font-size: 12px; letter-spacing: 0.1em; color: var(--gold); text-transform: uppercase; }
  #topnav .chapter-label { font-size: 12px; color: var(--cream-dim); letter-spacing: 0.06em; }

  /* ── SIDE DOTS ── */
  #sidenav {
    position: fixed; right: 28px; top: 50%; transform: translateY(-50%);
    z-index: 100; display: flex; flex-direction: column; gap: 10px;
  }
  .sdot {
    width: 8px; height: 8px; border-radius: 50%;
    background: rgba(245,240,232,0.2);
    cursor: pointer; transition: all 0.3s ease;
    border: 1px solid rgba(245,240,232,0.2);
  }
  .sdot:hover { background: var(--gold); transform: scale(1.3); }
  .sdot.active { background: var(--coral); border-color: var(--coral); transform: scale(1.2); }

  /* ── SECTIONS ── */
  .section {
    min-height: 100vh; padding: 80px 80px 60px;
    display: flex; flex-direction: column; justify-content: center;
    position: relative; overflow: hidden;
  }
  .section-inner { max-width: 1200px; margin: 0 auto; width: 100%; }

  /* ── FADE IN ANIMATION ── */
  .fadein { opacity: 0; transform: translateY(32px); transition: opacity 0.7s ease, transform 0.7s ease; }
  .fadein.visible { opacity: 1; transform: translateY(0); }
  .fadein.d1 { transition-delay: 0.1s; }
  .fadein.d2 { transition-delay: 0.22s; }
  .fadein.d3 { transition-delay: 0.34s; }
  .fadein.d4 { transition-delay: 0.46s; }
  .fadein.d5 { transition-delay: 0.58s; }
  .fadein.d6 { transition-delay: 0.70s; }

  /* ── CHAPTER TAG ── */
  .ch-tag {
    display: inline-flex; align-items: center; gap: 8px;
    font-family: 'DM Mono', monospace; font-size: 11px;
    letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--gold); margin-bottom: 20px;
  }
  .ch-tag::before { content: ''; display: block; width: 28px; height: 1px; background: var(--gold); }

  /* ── HEADINGS ── */
  h1.hero { font-family: 'Cormorant Garamond', serif; font-size: clamp(52px, 7vw, 96px); font-weight: 300; line-height: 1.02; letter-spacing: -0.02em; }
  h2.section-title { font-family: 'Cormorant Garamond', serif; font-size: clamp(36px, 5vw, 64px); font-weight: 300; line-height: 1.1; margin-bottom: 16px; }
  h3.card-title { font-family: 'Cormorant Garamond', serif; font-size: 26px; font-weight: 400; margin-bottom: 8px; }

  /* ── DIVIDER ── */
  .divider { width: 48px; height: 2px; background: var(--coral); margin-bottom: 28px; }

  /* ── STAT CARDS ── */
  .stat-row { display: flex; gap: 24px; margin-top: 56px; }
  .stat-card {
    flex: 1; border: 1px solid rgba(201,168,76,0.25);
    padding: 28px 24px; border-radius: 4px;
    background: rgba(255,255,255,0.03);
    position: relative; overflow: hidden;
  }
  .stat-card::before {
    content: ''; position: absolute; top: 0; left: 0; right: 0; height: 2px;
    background: linear-gradient(90deg, var(--coral), var(--gold));
  }
  .stat-num { font-family: 'Cormorant Garamond', serif; font-size: 52px; font-weight: 300; color: var(--gold); line-height: 1; }
  .stat-label { font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--cream-dim); margin-top: 6px; }

  /* ── CTA BUTTON ── */
  .btn-primary {
    display: inline-flex; align-items: center; gap: 10px;
    padding: 14px 32px; background: var(--coral);
    color: white; font-size: 13px; font-weight: 500; letter-spacing: 0.06em;
    text-transform: uppercase; border: none; cursor: pointer; border-radius: 2px;
    margin-top: 48px; transition: all 0.25s ease;
  }
  .btn-primary:hover { background: #d4603a; transform: translateX(4px); }
  .btn-secondary {
    display: inline-flex; align-items: center; gap: 10px;
    padding: 14px 32px; background: transparent;
    color: var(--cream); font-size: 13px; font-weight: 500; letter-spacing: 0.06em;
    text-transform: uppercase; border: 1px solid rgba(245,240,232,0.3); cursor: pointer; border-radius: 2px;
    margin-top: 48px; transition: all 0.25s ease;
  }
  .btn-secondary:hover { border-color: var(--gold); color: var(--gold); }

  /* ── BG DECOR ── */
  .bg-circle {
    position: absolute; border-radius: 50%; pointer-events: none;
    background: radial-gradient(circle, rgba(232,113,74,0.08), transparent 70%);
  }

  /* ═══════════════════════════════════════════
     SECTION 1 — HERO
  ═══════════════════════════════════════════ */
  #s1 { background: var(--navy); }
  #s1 .bg-circle.c1 { width: 700px; height: 700px; top: -200px; right: -200px; }
  #s1 .bg-circle.c2 { width: 400px; height: 400px; bottom: -100px; left: 100px; background: radial-gradient(circle, rgba(201,168,76,0.06), transparent 70%); }
  #s1 .eyebrow { font-family: 'DM Mono', monospace; font-size: 11px; letter-spacing: 0.18em; text-transform: uppercase; color: var(--coral); margin-bottom: 24px; }
  #s1 h1 em { font-style: italic; color: var(--gold); }
  #s1 .hero-sub { font-size: 18px; font-weight: 300; color: var(--cream-dim); max-width: 560px; margin-top: 20px; line-height: 1.6; }
  #s1 .byline { font-family: 'DM Mono', monospace; font-size: 11px; letter-spacing: 0.1em; color: rgba(245,240,232,0.35); margin-top: 40px; border-left: 2px solid var(--gold); padding-left: 14px; }

  /* ═══════════════════════════════════════════
     SECTION 2 — CLIENT OVERVIEW
  ═══════════════════════════════════════════ */
  #s2 { background: linear-gradient(160deg, var(--navy) 0%, var(--navy-mid) 100%); }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 64px; align-items: start; margin-top: 40px; }
  .info-block { margin-bottom: 20px; }
  .info-label { font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--gold); margin-bottom: 4px; }
  .info-val { font-size: 14px; color: var(--cream); }
  .highlight-box {
    border: 1px solid rgba(232,113,74,0.3); border-radius: 4px;
    padding: 20px 24px; margin-top: 28px;
    background: rgba(232,113,74,0.06);
  }
  .highlight-box h4 { font-size: 12px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--coral); margin-bottom: 8px; }
  .highlight-box p { font-size: 14px; line-height: 1.7; color: var(--cream-dim); }

  /* Competitor Matrix */
  .matrix-wrap { position: relative; width: 100%; height: 340px; }
  .matrix-bg {
    position: absolute; inset: 40px;
    border-left: 1px solid rgba(245,240,232,0.12);
    border-bottom: 1px solid rgba(245,240,232,0.12);
  }
  .axis-label { position: absolute; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--cream-dim); }
  .ax-x-left { bottom: 20px; left: 40px; }
  .ax-x-right { bottom: 20px; right: 0; }
  .ax-y-top { top: 10px; left: 40px; }
  .ax-y-bot { bottom: 40px; left: 0; writing-mode: vertical-rl; transform: rotate(180deg); }
  .brand-dot {
    position: absolute; width: 12px; height: 12px; border-radius: 50%;
    transform: translate(-50%, 50%); cursor: pointer;
    transition: transform 0.2s ease;
  }
  .brand-dot:hover { transform: translate(-50%, 50%) scale(1.5); }
  .brand-dot-label {
    position: absolute; font-size: 11px; color: var(--cream); white-space: nowrap;
    transform: translateX(-50%); top: -22px;
  }
  .brand-dot-wrap { position: absolute; }
  .matrix-grid-h, .matrix-grid-v {
    position: absolute;
    background: rgba(245,240,232,0.04);
    pointer-events: none;
  }

  /* Persona / contact cards */
  .contact-card {
    border: 1px solid rgba(201,168,76,0.2); border-radius: 4px;
    padding: 20px; margin-top: 28px;
    background: rgba(201,168,76,0.04);
  }
  .contact-card .name { font-family: 'Cormorant Garamond', serif; font-size: 20px; }
  .contact-card .title-role { font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--gold); margin-bottom: 12px; }
  .contact-pill {
    display: inline-block; font-size: 11px; padding: 3px 10px;
    border-radius: 20px; margin: 3px 3px 0 0;
    background: rgba(245,240,232,0.08); color: var(--cream-dim);
  }

  /* ═══════════════════════════════════════════
     SECTION 3 — SWOT
  ═══════════════════════════════════════════ */
  #s3 { background: var(--navy); }
  .swot-tabs { display: flex; gap: 0; margin-bottom: 32px; border-bottom: 1px solid rgba(245,240,232,0.1); }
  .swot-tab {
    padding: 12px 28px; font-size: 12px; letter-spacing: 0.1em; text-transform: uppercase;
    cursor: pointer; color: var(--cream-dim); border-bottom: 2px solid transparent;
    transition: all 0.25s ease; margin-bottom: -1px;
  }
  .swot-tab:hover { color: var(--cream); }
  .swot-tab.active { color: var(--coral); border-bottom-color: var(--coral); }
  .swot-panel { display: none; }
  .swot-panel.active { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .swot-q {
    padding: 28px; border-radius: 4px;
    border: 1px solid;
  }
  .swot-q.s { border-color: rgba(76,175,125,0.3); background: rgba(76,175,125,0.06); }
  .swot-q.w { border-color: rgba(224,82,82,0.3); background: rgba(224,82,82,0.06); }
  .swot-q.o { border-color: rgba(74,144,217,0.3); background: rgba(74,144,217,0.06); }
  .swot-q.t { border-color: rgba(201,168,76,0.3); background: rgba(201,168,76,0.06); }
  .swot-q-label { font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.14em; text-transform: uppercase; margin-bottom: 14px; }
  .swot-q.s .swot-q-label { color: var(--green); }
  .swot-q.w .swot-q-label { color: var(--red); }
  .swot-q.o .swot-q-label { color: var(--blue-accent); }
  .swot-q.t .swot-q-label { color: var(--gold); }
  .swot-item { font-size: 13px; color: var(--cream-dim); line-height: 1.6; padding: 6px 0; border-bottom: 1px solid rgba(245,240,232,0.06); }
  .swot-item:last-child { border-bottom: none; }

  /* ═══════════════════════════════════════════
     SECTION 4 — STRATEGIC RECOMMENDATIONS
  ═══════════════════════════════════════════ */
  #s4 { background: linear-gradient(160deg, var(--navy-mid) 0%, var(--navy) 100%); }
  .strategy-tabs { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 32px; }
  .strat-tab {
    padding: 8px 20px; font-size: 12px; letter-spacing: 0.08em;
    cursor: pointer; border-radius: 2px;
    border: 1px solid rgba(245,240,232,0.15);
    color: var(--cream-dim); transition: all 0.25s ease;
  }
  .strat-tab:hover { border-color: var(--gold); color: var(--gold); }
  .strat-tab.active { background: var(--coral); border-color: var(--coral); color: white; }
  .strat-panel { display: none; }
  .strat-panel.active { display: grid; grid-template-columns: 1fr 1.6fr; gap: 48px; align-items: start; }
  .strat-icon { font-size: 48px; margin-bottom: 16px; }
  .strat-goal { font-size: 12px; text-transform: uppercase; letter-spacing: 0.1em; color: var(--gold); margin-bottom: 8px; }
  .strat-headline { font-family: 'Cormorant Garamond', serif; font-size: 36px; font-weight: 300; line-height: 1.1; margin-bottom: 16px; }
  .strat-desc { font-size: 14px; color: var(--cream-dim); line-height: 1.7; }
  .tactic-list { list-style: none; }
  .tactic-list li {
    padding: 14px 0; border-bottom: 1px solid rgba(245,240,232,0.07);
    font-size: 14px; color: var(--cream-dim); line-height: 1.6;
    display: flex; gap: 12px; align-items: flex-start;
  }
  .tactic-list li::before { content: '→'; color: var(--coral); flex-shrink: 0; margin-top: 1px; }
  .budget-badge {
    display: inline-block; padding: 4px 12px; border-radius: 2px;
    background: rgba(201,168,76,0.12); border: 1px solid rgba(201,168,76,0.3);
    font-size: 11px; color: var(--gold); letter-spacing: 0.08em; margin-top: 16px;
  }

  /* ═══════════════════════════════════════════
     SECTION 5 — KPIs
  ═══════════════════════════════════════════ */
  #s5 { background: var(--navy); }
  .kpi-banner {
    display: flex; gap: 24px; margin-bottom: 40px;
    padding: 20px 28px; border-radius: 4px;
    background: linear-gradient(135deg, rgba(232,113,74,0.12), rgba(201,168,76,0.08));
    border: 1px solid rgba(232,113,74,0.2);
  }
  .kpi-banner-item { flex: 1; text-align: center; }
  .kpi-banner-num { font-family: 'Cormorant Garamond', serif; font-size: 36px; color: var(--gold); }
  .kpi-banner-label { font-size: 11px; letter-spacing: 0.08em; color: var(--cream-dim); margin-top: 4px; }
  .kpi-cols { display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; }
  .kpi-col { border: 1px solid rgba(245,240,232,0.08); border-radius: 4px; padding: 24px; }
  .kpi-col-title { font-size: 12px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--coral); margin-bottom: 16px; padding-bottom: 12px; border-bottom: 1px solid rgba(245,240,232,0.08); }
  .kpi-item { display: flex; align-items: center; gap: 10px; padding: 8px 0; border-bottom: 1px solid rgba(245,240,232,0.05); }
  .kpi-item:last-child { border-bottom: none; }
  .kpi-dot { width: 6px; height: 6px; border-radius: 50%; flex-shrink: 0; }
  .kpi-text { font-size: 13px; color: var(--cream-dim); line-height: 1.5; }
  .cadence-row { display: flex; gap: 0; margin-top: 36px; }
  .cadence-item { flex: 1; text-align: center; padding: 20px; border-top: 2px solid; position: relative; }
  .cadence-item:nth-child(1) { border-color: var(--coral); }
  .cadence-item:nth-child(2) { border-color: var(--gold); }
  .cadence-item:nth-child(3) { border-color: var(--green); }
  .cadence-item:nth-child(4) { border-color: var(--blue-accent); }
  .cadence-freq { font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.12em; text-transform: uppercase; color: var(--cream-dim); }
  .cadence-what { font-family: 'Cormorant Garamond', serif; font-size: 20px; margin-top: 6px; }

  /* ═══════════════════════════════════════════
     SECTION 6 — INNOVATION
  ═══════════════════════════════════════════ */
  #s6 { background: linear-gradient(160deg, var(--navy) 0%, var(--navy-mid) 100%); }
  .inno-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; margin-top: 36px; }
  .inno-card {
    border: 1px solid rgba(245,240,232,0.1); border-radius: 4px; padding: 28px;
    background: rgba(255,255,255,0.02); position: relative; overflow: hidden;
    transition: border-color 0.3s ease, background 0.3s ease;
  }
  .inno-card:hover { border-color: rgba(232,113,74,0.4); background: rgba(232,113,74,0.04); }
  .inno-num { font-family: 'Cormorant Garamond', serif; font-size: 72px; font-weight: 300; color: rgba(201,168,76,0.1); position: absolute; top: 8px; right: 16px; line-height: 1; pointer-events: none; }
  .inno-icon { font-size: 28px; margin-bottom: 14px; }
  .inno-title { font-family: 'Cormorant Garamond', serif; font-size: 22px; margin-bottom: 8px; }
  .inno-desc { font-size: 13px; color: var(--cream-dim); line-height: 1.7; margin-bottom: 16px; }
  .inno-highlight {
    padding: 12px 14px; border-radius: 3px;
    background: rgba(201,168,76,0.08); border-left: 2px solid var(--gold);
    font-size: 12px; color: var(--cream-dim); line-height: 1.6;
  }
  .inno-highlight strong { color: var(--gold); }

  /* QUIZ */
  #quiz-wrap { margin-top: 40px; border: 1px solid rgba(232,113,74,0.25); border-radius: 4px; padding: 36px; background: rgba(232,113,74,0.04); }
  .quiz-title { font-family: 'Cormorant Garamond', serif; font-size: 28px; margin-bottom: 6px; }
  .quiz-sub { font-size: 13px; color: var(--cream-dim); margin-bottom: 28px; }
  .quiz-question { font-size: 15px; font-weight: 500; margin-bottom: 16px; }
  .quiz-options { display: flex; flex-wrap: wrap; gap: 10px; }
  .quiz-opt {
    padding: 10px 20px; border: 1px solid rgba(245,240,232,0.2);
    border-radius: 2px; font-size: 13px; cursor: pointer;
    color: var(--cream-dim); transition: all 0.2s ease;
  }
  .quiz-opt:hover { border-color: var(--coral); color: var(--cream); }
  .quiz-opt.selected { border-color: var(--coral); background: rgba(232,113,74,0.15); color: var(--cream); }
  .quiz-progress { display: flex; gap: 6px; margin-bottom: 20px; }
  .quiz-step { height: 3px; flex: 1; border-radius: 2px; background: rgba(245,240,232,0.1); transition: background 0.4s; }
  .quiz-step.done { background: var(--coral); }
  .quiz-result { display: none; padding: 28px; border: 1px solid rgba(201,168,76,0.3); border-radius: 4px; background: rgba(201,168,76,0.06); }
  .quiz-result.show { display: block; }
  .result-persona { font-family: 'Cormorant Garamond', serif; font-size: 36px; color: var(--gold); margin-bottom: 8px; }
  .result-desc { font-size: 14px; color: var(--cream-dim); line-height: 1.7; margin-bottom: 16px; }
  .result-product { font-size: 13px; color: var(--cream); }
  .result-product strong { color: var(--coral); }
  .quiz-restart { margin-top: 16px; padding: 8px 18px; border: 1px solid rgba(245,240,232,0.2); background: transparent; color: var(--cream-dim); font-size: 12px; cursor: pointer; border-radius: 2px; transition: all 0.2s; }
  .quiz-restart:hover { border-color: var(--coral); color: var(--coral); }

  /* ═══════════════════════════════════════════
     SECTION 7 — PROJECT MANAGEMENT
  ═══════════════════════════════════════════ */
  #s7 { background: var(--navy); }
  .gantt-wrap { margin-top: 36px; overflow-x: auto; }
  .gantt-header { display: grid; grid-template-columns: 140px repeat(6, 1fr); gap: 0; margin-bottom: 4px; }
  .gantt-month { text-align: center; font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--gold); padding: 8px 4px; }
  .gantt-row { display: grid; grid-template-columns: 140px repeat(6, 1fr); gap: 0; margin-bottom: 8px; align-items: center; }
  .gantt-label { font-size: 11px; color: var(--cream-dim); padding-right: 12px; letter-spacing: 0.04em; }
  .gantt-cell { padding: 2px; height: 28px; }
  .gantt-bar {
    height: 100%; border-radius: 2px; display: flex; align-items: center;
    padding: 0 8px; font-size: 10px; color: white; font-weight: 500;
    letter-spacing: 0.04em; white-space: nowrap; overflow: hidden;
  }
  .bar-seo { background: rgba(74,144,217,0.7); }
  .bar-paid { background: rgba(232,113,74,0.7); }
  .bar-pr { background: rgba(201,168,76,0.7); }
  .bar-rep { background: rgba(76,175,125,0.7); }
  .bar-found { background: rgba(160,120,220,0.7); }
  .gantt-milestone {
    display: flex; align-items: center; justify-content: center;
    height: 28px;
  }
  .diamond { width: 12px; height: 12px; background: var(--coral); transform: rotate(45deg); }
  .team-chart { display: flex; flex-direction: column; align-items: center; margin-top: 40px; }
  .team-node {
    padding: 12px 24px; border: 1px solid; border-radius: 3px;
    text-align: center; font-size: 13px;
  }
  .team-node.you { border-color: var(--coral); color: var(--coral); background: rgba(232,113,74,0.08); font-weight: 600; }
  .team-node.lead { border-color: rgba(74,144,217,0.4); color: var(--cream-dim); background: rgba(74,144,217,0.05); }
  .team-node.client { border-color: rgba(201,168,76,0.4); color: var(--gold); background: rgba(201,168,76,0.05); }
  .team-row { display: flex; gap: 16px; margin-top: 4px; }
  .team-connector { width: 1px; height: 24px; background: rgba(245,240,232,0.15); margin: 0 auto; }
  .team-connector-h { display: flex; align-items: center; gap: 0; margin-bottom: 4px; }

  /* ═══════════════════════════════════════════
     SECTION 8 — COMMUNICATION
  ═══════════════════════════════════════════ */
  #s8 { background: linear-gradient(160deg, var(--navy-mid) 0%, var(--navy) 100%); }
  .comm-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 48px; margin-top: 36px; }
  .cadence-card {
    border: 1px solid rgba(245,240,232,0.08); border-radius: 4px; padding: 24px;
    background: rgba(255,255,255,0.02); margin-bottom: 12px;
    display: grid; grid-template-columns: 80px 1fr; gap: 16px; align-items: start;
  }
  .cad-freq { font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--coral); padding-top: 3px; }
  .cad-title { font-size: 15px; font-weight: 500; margin-bottom: 4px; }
  .cad-desc { font-size: 12px; color: var(--cream-dim); line-height: 1.6; }
  .protocol-item { display: flex; gap: 14px; padding: 16px 0; border-bottom: 1px solid rgba(245,240,232,0.06); align-items: flex-start; }
  .protocol-icon { font-size: 20px; flex-shrink: 0; }
  .protocol-text { font-size: 13px; color: var(--cream-dim); line-height: 1.6; }
  .protocol-text strong { color: var(--cream); }

  /* Jane card */
  .jane-card {
    border: 1px solid rgba(201,168,76,0.25); border-radius: 4px; padding: 28px;
    background: rgba(201,168,76,0.04); margin-top: 24px;
  }
  .jane-card .jane-name { font-family: 'Cormorant Garamond', serif; font-size: 28px; margin-bottom: 4px; }
  .jane-card .jane-title { font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--gold); margin-bottom: 16px; }
  .jane-row { display: flex; gap: 8px; align-items: flex-start; margin-bottom: 8px; }
  .jane-key { font-family: 'DM Mono', monospace; font-size: 10px; text-transform: uppercase; letter-spacing: 0.1em; color: var(--cream-dim); min-width: 100px; padding-top: 2px; }
  .jane-val { font-size: 13px; color: var(--cream); }

  /* ═══════════════════════════════════════════
     SECTION 9 — IMPACT + CASE STUDY
  ═══════════════════════════════════════════ */
  #s9 { background: var(--navy); }
  .impact-cards { display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px; margin-top: 36px; }
  .impact-card { padding: 24px; border-radius: 4px; border: 1px solid rgba(245,240,232,0.08); text-align: center; }
  .impact-now { font-size: 11px; letter-spacing: 0.08em; text-transform: uppercase; color: var(--cream-dim); margin-bottom: 6px; }
  .impact-arrow { font-size: 20px; color: var(--gold); margin: 8px 0; }
  .impact-target { font-family: 'Cormorant Garamond', serif; font-size: 32px; color: var(--green); }
  .impact-metric { font-size: 12px; color: var(--cream-dim); margin-top: 4px; }

  /* Funnel */
  .funnel-wrap { margin-top: 40px; }
  .funnel-row {
    display: flex; align-items: center; gap: 16px; margin-bottom: 8px;
    cursor: pointer; padding: 14px 20px; border-radius: 3px;
    transition: background 0.2s ease;
  }
  .funnel-row:hover { background: rgba(255,255,255,0.04); }
  .funnel-label { font-family: 'DM Mono', monospace; font-size: 11px; letter-spacing: 0.1em; text-transform: uppercase; min-width: 120px; }
  .funnel-bar { height: 28px; border-radius: 2px; display: flex; align-items: center; padding: 0 12px; transition: width 0.6s ease; }
  .funnel-bar-text { font-size: 11px; color: white; white-space: nowrap; overflow: hidden; }
  .funnel-detail { font-size: 12px; color: var(--cream-dim); margin-left: auto; }

  /* Case study */
  .case-study {
    border: 1px solid rgba(245,240,232,0.1); border-radius: 4px; padding: 36px;
    margin-top: 40px; background: rgba(255,255,255,0.02);
    display: grid; grid-template-columns: 1fr 1fr; gap: 40px;
  }
  .cs-label { font-family: 'DM Mono', monospace; font-size: 10px; letter-spacing: 0.14em; text-transform: uppercase; color: var(--coral); margin-bottom: 8px; }
  .cs-title { font-family: 'Cormorant Garamond', serif; font-size: 28px; font-weight: 300; margin-bottom: 16px; }
  .cs-text { font-size: 14px; color: var(--cream-dim); line-height: 1.7; }
  .cs-result { display: flex; align-items: center; gap: 16px; padding: 14px 0; border-bottom: 1px solid rgba(245,240,232,0.06); }
  .cs-num { font-family: 'Cormorant Garamond', serif; font-size: 36px; color: var(--gold); min-width: 80px; }
  .cs-desc { font-size: 13px; color: var(--cream-dim); }

  /* Final CTA */
  .final-cta { margin-top: 48px; padding: 48px; border-radius: 4px; text-align: center; background: linear-gradient(135deg, rgba(232,113,74,0.12), rgba(201,168,76,0.08)); border: 1px solid rgba(201,168,76,0.2); }
  .final-cta h2 { font-family: 'Cormorant Garamond', serif; font-size: 48px; font-weight: 300; margin-bottom: 12px; }
  .final-cta p { font-size: 15px; color: var(--cream-dim); max-width: 500px; margin: 0 auto 32px; }
  .cta-btns { display: flex; gap: 16px; justify-content: center; flex-wrap: wrap; }
  .btn-final {
    padding: 14px 36px; font-size: 12px; letter-spacing: 0.1em; text-transform: uppercase;
    border: 1px solid; cursor: pointer; border-radius: 2px; transition: all 0.25s;
  }
  .btn-final.primary { background: var(--coral); border-color: var(--coral); color: white; }
  .btn-final.primary:hover { background: #d4603a; }
  .btn-final.secondary { background: transparent; border-color: rgba(245,240,232,0.3); color: var(--cream); }
  .btn-final.secondary:hover { border-color: var(--gold); color: var(--gold); }

  /* Tooltip */
  .tooltip {
    position: absolute; padding: 8px 12px; background: var(--navy-mid);
    border: 1px solid rgba(201,168,76,0.3); border-radius: 3px;
    font-size: 12px; color: var(--cream); pointer-events: none;
    z-index: 200; white-space: nowrap; display: none;
  }

  /* Legend */
  .legend { display: flex; gap: 20px; flex-wrap: wrap; margin-top: 12px; }
  .legend-item { display: flex; align-items: center; gap: 6px; font-size: 11px; color: var(--cream-dim); }
  .legend-dot { width: 10px; height: 10px; border-radius: 2px; }

  @media (max-width: 900px) {
    .section { padding: 80px 24px 48px; }
    .two-col, .strat-panel.active, .comm-grid, .case-study { grid-template-columns: 1fr; gap: 32px; }
    .impact-cards { grid-template-columns: 1fr 1fr; }
    .kpi-cols { grid-template-columns: 1fr; }
    .inno-grid { grid-template-columns: 1fr; }
    .stat-row { flex-direction: column; }
    #topnav { padding: 0 20px; }
    #sidenav { display: none; }
  }
</style>
</head>
<body>

<!-- TOP NAV -->
<nav id="topnav">
  <div class="brand">Joybird × Go Fish Digital</div>
  <div class="chapter-label" id="chapterlabel">2026 Digital Strategy</div>
</nav>

<!-- SIDE DOTS -->
<div id="sidenav">
  <div class="sdot active" onclick="scrollTo(0)" title="Intro"></div>
  <div class="sdot" onclick="scrollToSec(1)" title="Client Overview"></div>
  <div class="sdot" onclick="scrollToSec(2)" title="Parent Company"></div>
  <div class="sdot" onclick="scrollToSec(3)" title="Assessment"></div>
  <div class="sdot" onclick="scrollToSec(4)" title="Strategy"></div>
  <div class="sdot" onclick="scrollToSec(5)" title="KPIs"></div>
  <div class="sdot" onclick="scrollToSec(6)" title="Innovation"></div>
  <div class="sdot" onclick="scrollToSec(7)" title="PM Plan"></div>
  <div class="sdot" onclick="scrollToSec(8)" title="Communication"></div>
  <div class="sdot" onclick="scrollToSec(9)" title="Impact"></div>
</div>

<!-- ════════════════════════════════════════════════
     S1 — HERO
════════════════════════════════════════════════ -->
<section class="section" id="s1">
  <div class="bg-circle c1"></div>
  <div class="bg-circle c2"></div>
  <div class="section-inner">
    <div style="margin-bottom:36px;display:flex;align-items:center;gap:20px;" class="fadein">
      <!-- GO FISH wordmark -->
      <svg width="96" height="44" viewBox="0 0 96 44" xmlns="http://www.w3.org/2000/svg">
        <rect width="96" height="44" rx="3" fill="#102050"/>
        <text x="48" y="17" text-anchor="middle" font-family="Arial Black,Impact,sans-serif" font-weight="900" font-size="14" fill="white" letter-spacing="2">GO</text>
        <text x="48" y="35" text-anchor="middle" font-family="Arial Black,Impact,sans-serif" font-weight="900" font-size="14" fill="white" letter-spacing="2">FiSH</text>
      </svg>
      <!-- separator -->
      <span style="font-family:'Cormorant Garamond',serif;font-size:28px;font-weight:300;color:rgba(201,168,76,0.6);line-height:1;">×</span>
      <!-- JOYBIRD wordmark -->
      <svg width="130" height="44" viewBox="0 0 130 44" xmlns="http://www.w3.org/2000/svg">
        <rect width="130" height="44" rx="3" fill="rgba(255,255,255,0.04)" stroke="rgba(245,240,232,0.15)" stroke-width="1"/>
        <text x="65" y="28" text-anchor="middle" font-family="Arial,Helvetica,sans-serif" font-weight="700" font-size="15" fill="#F5F0E8" letter-spacing="4">JOYBIRD</text>
      </svg>
    </div>
    <div class="eyebrow fadein d1">2026 Digital Marketing Strategy</div>
    <h1 class="hero fadein d2">Your Space.<br><em>Your Vibe.</em><br>Your Growth.</h1>
    <p class="hero-sub fadein d3">A comprehensive digital marketing strategy for Joybird — built on a decade of partnership and designed for the next decade of growth.</p>
    <div class="stat-row fadein d4">
      <div class="stat-card">
        <div class="stat-num" data-count="10" data-suffix="+">0</div>
        <div class="stat-label">Years of Partnership</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-count="4" data-suffix=":1">0</div>
        <div class="stat-label">Target ROI</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-count="15" data-suffix="%">0</div>
        <div class="stat-label">Revenue Growth Goal</div>
      </div>
      <div class="stat-card">
        <div class="stat-num" data-prefix="$" data-count="275" data-suffix="K">0</div>
        <div class="stat-label">Annual Paid Media Budget</div>
      </div>
    </div>
    <button class="btn-primary fadein d5" onclick="scrollToSec(1)">Explore the Strategy &nbsp;→</button>

  </div>
</section>

<!-- ════════════════════════════════════════════════
     S2 — CLIENT OVERVIEW
════════════════════════════════════════════════ -->
<section class="section" id="s2">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 01</div>
    <h2 class="section-title fadein d1">Client Overview</h2>
    <div class="divider fadein d2"></div>

    <div class="two-col">
      <div class="fadein d2">
        <div class="info-block">
          <div class="info-label">Brand</div>
          <div class="info-val" style="font-family:'Cormorant Garamond',serif;font-size:22px;">Joybird</div>
        </div>
        <div class="info-block">
          <div class="info-label">Category</div>
          <div class="info-val">Design-forward DTC furniture — sofas, loveseats, sectionals</div>
        </div>
        <div class="info-block">
          <div class="info-label">Platform &amp; Stack</div>
          <div class="info-val">Shopify &nbsp;·&nbsp; Google Analytics 4 &nbsp;·&nbsp; HubSpot CRM</div>
        </div>
        <div class="info-block">
          <div class="info-label">Priority Products</div>
          <div class="info-val">Loveseats &nbsp;·&nbsp; Sofas &nbsp;·&nbsp; Sectionals</div>
        </div>
        <div class="info-block">
          <div class="info-label">Key Competitors</div>
          <div class="info-val">Article &nbsp;·&nbsp; Burrow &nbsp;·&nbsp; West Elm &nbsp;·&nbsp; Pottery Barn</div>
        </div>
        <div class="info-block" style="margin-top:24px;">
          <div class="info-label">What We're Here to Do</div>
          <div class="info-val" style="font-size:15px;line-height:1.7;color:var(--cream);">Ten years of partnership gives us a clear baseline. The 2026 strategy builds on that foundation with a more integrated, data-connected approach — one that closes the loop between marketing activity and revenue outcomes across every channel.</div>
        </div>
      </div>

      <div class="fadein d3">
        <div style="margin-bottom:12px;">
          <div class="info-label">Competitive Positioning Matrix</div>
          <div style="font-size:12px;color:var(--cream-dim);margin-top:2px;">Hover over a brand dot to learn more</div>
        </div>
        <div class="matrix-wrap" id="matrix">
          <div class="matrix-bg"></div>
          <!-- Axis labels -->
          <span class="axis-label ax-x-left">Budget →</span>
          <span class="axis-label ax-x-right">← Premium</span>
          <span class="axis-label ax-y-top">High Customization</span>
          <span class="axis-label" style="bottom:50px;left:6px;font-size:9px;writing-mode:vertical-rl;transform:rotate(180deg);letter-spacing:0.1em;text-transform:uppercase;color:var(--cream-dim);">Generic</span>

          <!-- Brand dots: left=budget x-axis%, top=from-top (low custom=high top) -->
          <!-- Joybird: premium + high custom → right, top -->
          <div class="brand-dot-wrap" style="left:82%;bottom:75%;">
            <div class="brand-dot" style="background:var(--coral);" data-tip="Joybird: Premium price, unmatched true customization. Your unique moat."></div>
            <div class="brand-dot-label" style="color:var(--coral);font-weight:600;">Joybird</div>
          </div>
          <!-- West Elm: premium + mid custom -->
          <div class="brand-dot-wrap" style="left:75%;bottom:50%;">
            <div class="brand-dot" style="background:var(--cream-dim);" data-tip="West Elm: Premium but limited customization. Retail-backed scale."></div>
            <div class="brand-dot-label">West Elm</div>
          </div>
          <!-- Burrow: mid-premium + low-mid custom -->
          <div class="brand-dot-wrap" style="left:55%;bottom:35%;">
            <div class="brand-dot" style="background:var(--blue-accent);" data-tip="Burrow: DTC, good UX, moderate customization. Strong paid presence."></div>
            <div class="brand-dot-label">Burrow</div>
          </div>
          <!-- Article: mid + low custom -->
          <div class="brand-dot-wrap" style="left:42%;bottom:20%;">
            <div class="brand-dot" style="background:var(--gold);" data-tip="Article: Well-designed, budget-friendly, no true customization."></div>
            <div class="brand-dot-label">Article</div>
          </div>
          <!-- Pottery Barn: premium + very low custom -->
          <div class="brand-dot-wrap" style="left:70%;bottom:18%;">
            <div class="brand-dot" style="background:#a0a0b0;" data-tip="Pottery Barn: Retail premium, very limited personalization."></div>
            <div class="brand-dot-label">Pottery Barn</div>
          </div>

          <div class="tooltip" id="matrix-tooltip"></div>
        </div>

        <div class="info-block" style="margin-top:20px;">
          <div class="info-label">Primary Business Goals</div>
          <div style="display:flex;gap:10px;flex-wrap:wrap;margin-top:6px;">
            <span style="padding:6px 14px;border:1px solid rgba(232,113,74,0.3);border-radius:2px;font-size:12px;color:var(--coral);">Increase Revenue</span>
            <span style="padding:6px 14px;border:1px solid rgba(201,168,76,0.3);border-radius:2px;font-size:12px;color:var(--gold);">4:1 ROI on Marketing</span>
            <span style="padding:6px 14px;border:1px solid rgba(76,175,125,0.3);border-radius:2px;font-size:12px;color:var(--green);">+15% YoY Revenue</span>
            <span style="padding:6px 14px;border:1px solid rgba(74,144,217,0.3);border-radius:2px;font-size:12px;color:var(--blue-accent);">Improve Online Reputation</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S2b — LA-Z-BOY PARENT INTELLIGENCE
════════════════════════════════════════════════ -->
<section class="section" id="s2b" style="background:linear-gradient(160deg,#0e1f40 0%,#0A1628 100%);">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 02</div>
    <h2 class="section-title fadein d1">Joybird is one bet<br>inside a $2B portfolio.</h2>
    <div class="divider fadein d2"></div>
    <p class="fadein d2" style="font-size:15px;color:var(--cream-dim);max-width:680px;line-height:1.7;margin-bottom:36px;">Understanding La-Z-Boy Inc.'s strategic direction sharpens both the urgency of 2026 — and the scale of the opportunity on the other side of it.</p>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:40px;" class="fadein d3">

      <!-- LEFT: Portfolio map -->
      <div>
        <div style="font-size:11px;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-bottom:20px;">La-Z-Boy Inc. Brand Portfolio</div>

        <div style="margin-bottom:10px;padding:16px 20px;border-radius:4px;border:1px solid rgba(232,113,74,0.35);background:rgba(232,113,74,0.07);">
          <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--coral);margin-bottom:6px;">Upholstery — Core Growth Engine</div>
          <div style="display:flex;flex-wrap:wrap;gap:8px;">
            <span style="padding:5px 12px;border-radius:2px;background:rgba(232,113,74,0.2);font-size:12px;color:var(--cream);">La-Z-Boy <span style="color:var(--green);font-size:10px;">↑ +11% Q3</span></span>
            <span style="padding:5px 12px;border-radius:2px;background:rgba(245,240,232,0.06);font-size:12px;color:var(--cream);">England Furniture <span style="color:var(--cream-dim);font-size:10px;">stable</span></span>
            <span style="padding:5px 12px;border-radius:2px;background:rgba(201,168,76,0.15);border:1px solid rgba(201,168,76,0.3);font-size:12px;color:var(--gold);">Joybird ← We are here</span>
          </div>
        </div>

        <div style="margin-bottom:10px;padding:16px 20px;border-radius:4px;border:1px solid rgba(224,82,82,0.25);background:rgba(224,82,82,0.05);">
          <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--red);margin-bottom:6px;">Casegoods — Declining / Being Exited</div>
          <div style="display:flex;flex-wrap:wrap;gap:8px;">
            <span style="padding:5px 12px;border-radius:2px;background:rgba(245,240,232,0.04);font-size:12px;color:var(--cream-dim);text-decoration:line-through;opacity:0.6;">Kincaid Furniture</span>
            <span style="padding:5px 12px;border-radius:2px;background:rgba(245,240,232,0.04);font-size:12px;color:var(--cream-dim);text-decoration:line-through;opacity:0.6;">American Drew</span>
            <span style="padding:5px 12px;border-radius:2px;background:rgba(245,240,232,0.04);font-size:12px;color:var(--cream-dim);opacity:0.6;">Hammary</span>
          </div>
        </div>

        <div style="padding:16px 20px;border-radius:4px;border:1px solid rgba(74,144,217,0.25);background:rgba(74,144,217,0.05);">
          <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--blue-accent);margin-bottom:6px;">Retail Segment — Fastest Growing</div>
          <div style="font-size:13px;color:var(--cream-dim);line-height:1.6;">La-Z-Boy Furniture Galleries (company-owned) — <span style="color:var(--green);">+11% Q3 2026</span>. La-Z-Boy is actively shifting from manufacturer to retailer/operator to capture more margin and stabilize demand.</div>
        </div>

        <div style="margin-top:20px;padding:14px 18px;border-left:2px solid var(--coral);background:rgba(232,113,74,0.06);border-radius:0 4px 4px 0;font-size:13px;color:var(--cream-dim);line-height:1.6;">
          <strong style="color:var(--cream);">Joybird's status within La-Z-Boy:</strong> A strategically important DTC brand targeting younger demographics — but currently showing a <span style="color:var(--red);">–10% to –13% decline</span> in written sales. This isn't a liability — it's our mandate. Turning Joybird around is exactly why we're here.
        </div>
      </div>

      <!-- RIGHT: Threat + Opportunity -->
      <div>
        <div style="font-size:11px;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-bottom:20px;">Strategic Implications for Go Fish Digital</div>

        <div style="margin-bottom:16px;padding:20px 24px;border-radius:4px;border:1px solid rgba(224,82,82,0.3);background:rgba(224,82,82,0.06);">
          <div style="font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--red);margin-bottom:10px;">⚠ The Threat — Urgency Is Real</div>
          <div style="font-size:13px;color:var(--cream-dim);line-height:1.7;">
            <div style="padding:6px 0;border-bottom:1px solid rgba(245,240,232,0.06);">Joybird is currently a drag on La-Z-Boy's portfolio — underperformance increases internal pressure and the risk of budget cuts or brand consolidation</div>
            <div style="padding:6px 0;border-bottom:1px solid rgba(245,240,232,0.06);">La-Z-Boy's shift to a flagship-brand retail model means Joybird must prove its value as a differentiated DTC asset — or risk being de-prioritized</div>
            <div style="padding:6px 0;">If we don't move the needle measurably in 2026, the engagement itself may be at risk — regardless of relationship tenure</div>
          </div>
        </div>

        <div style="padding:20px 24px;border-radius:4px;border:1px solid rgba(76,175,125,0.3);background:rgba(76,175,125,0.06);">
          <div style="font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--green);margin-bottom:10px;">✦ The Opportunity — A Portfolio Play</div>
          <div style="font-size:13px;color:var(--cream-dim);line-height:1.7;">
            <div style="padding:6px 0;border-bottom:1px solid rgba(245,240,232,0.06);">Joybird is our entry point into a <strong style="color:var(--cream);">$2B+ publicly traded company</strong>. Delivering results here opens the door to La-Z-Boy Furniture Galleries digital, England Furniture, and the broader retail segment</div>
            <div style="padding:6px 0;border-bottom:1px solid rgba(245,240,232,0.06);">La-Z-Boy's aggressive retail expansion (+11% Q3) means there is significant appetite for digital investment — particularly in paid media, local SEO, and reputation management across gallery locations</div>
            <div style="padding:6px 0;border-bottom:1px solid rgba(245,240,232,0.06);">England Furniture operates in dealer networks where digital PR and content strategy are vastly underutilized</div>
            <div style="padding:6px 0;">Our HubSpot + RevOps capability positions us to pitch a unified CRM and attribution architecture across the entire La-Z-Boy brand family — a conversation no other agency in this relationship can credibly have</div>
          </div>
        </div>

        <div style="margin-top:16px;padding:14px 18px;border-radius:4px;background:rgba(201,168,76,0.08);border:1px solid rgba(201,168,76,0.2);font-size:13px;color:var(--cream-dim);line-height:1.6;">
          <strong style="color:var(--gold);">The frame:</strong> We are not just Joybird's agency. We are Go Fish Digital's foothold in the La-Z-Boy portfolio. Every result we deliver for Joybird is a proof point for the next conversation.
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S3 — SWOT
════════════════════════════════════════════════ -->
<section class="section" id="s3">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 03</div>
    <h2 class="section-title fadein d1">Digital Marketing Assessment</h2>
    <div class="divider fadein d2"></div>
    <p class="fadein d2" style="font-size:15px;color:var(--cream-dim);max-width:600px;line-height:1.7;margin-bottom:32px;">A clear-eyed look at where Joybird stands — and where the opportunity lies. Select a channel below.</p>

    <div class="swot-tabs fadein d3">
      <div class="swot-tab active" onclick="switchSwot('seo',this)">SEO</div>
      <div class="swot-tab" onclick="switchSwot('paid',this)">Paid Media</div>
      <div class="swot-tab" onclick="switchSwot('pr',this)">Digital PR</div>
      <div class="swot-tab" onclick="switchSwot('rep',this)">Reputation</div>
    </div>

    <!-- SEO SWOT -->
    <div class="swot-panel active" id="swot-seo">
      <div class="swot-q s"><div class="swot-q-label">Strengths</div>
        <div class="swot-item">High-quality product photography supports visual-first search intent</div>
        <div class="swot-item">Recognized brand with built-in authority signals</div>
        <div class="swot-item">Shopify platform with structured data support</div>
      </div>
      <div class="swot-q w"><div class="swot-q-label">Weaknesses</div>
        <div class="swot-item">Under-optimized product & category pages — thin content on PLPs</div>
        <div class="swot-item">Site speed & Core Web Vitals need improvement</div>
        <div class="swot-item">Limited internal linking and content depth for long-tail queries</div>
      </div>
      <div class="swot-q o"><div class="swot-q-label">Opportunities</div>
        <div class="swot-item">Lifestyle content clusters: "best sofa for small apartments," "maximalist living room ideas"</div>
        <div class="swot-item">GEO optimization to appear in ChatGPT, Gemini & Perplexity answers</div>
        <div class="swot-item">AI Overview targeting with FAQ schema and structured Q&A content</div>
        <div class="swot-item">Quiz-result landing pages optimized for style-persona search intent</div>
      </div>
      <div class="swot-q t"><div class="swot-q-label">Threats</div>
        <div class="swot-item">Article & Burrow scaling long-form content and buyer guides aggressively</div>
        <div class="swot-item">AI-generated search results reducing organic click-through rates</div>
        <div class="swot-item">Zero-click search growth eroding top-of-funnel traffic</div>
      </div>
    </div>

    <!-- PAID SWOT -->
    <div class="swot-panel" id="swot-paid">
      <div class="swot-q s"><div class="swot-q-label">Strengths</div>
        <div class="swot-item">Visually compelling product line — ideal creative for Meta and Google</div>
        <div class="swot-item">Higher price points allow more room for efficient ROAS</div>
        <div class="swot-item">Existing Google Ads management by Jim provides institutional knowledge</div>
      </div>
      <div class="swot-q w"><div class="swot-q-label">Weaknesses</div>
        <div class="swot-item">Custom furniture's long consideration cycle requires deep nurturing</div>
        <div class="swot-item">Account structure likely not optimized for Performance Max</div>
        <div class="swot-item">Limited persona-based segmentation in current creative strategy</div>
      </div>
      <div class="swot-q o"><div class="swot-q-label">Opportunities</div>
        <div class="swot-item">Persona-based dynamic retargeting tied to quiz result segments</div>
        <div class="swot-item">Performance Max campaigns with strong audience signals and custom assets</div>
        <div class="swot-item">TikTok & Meta UGC amplification of influencer content at scale</div>
        <div class="swot-item">Shopping feed optimization to improve product visibility and CTR</div>
      </div>
      <div class="swot-q t"><div class="swot-q-label">Threats</div>
        <div class="swot-item">Rising CPCs — high-volume competitors commanding algorithmic favor</div>
        <div class="swot-item">iOS privacy changes limiting Meta audience precision</div>
        <div class="swot-item">Economic sensitivity to big-ticket furniture purchases</div>
      </div>
    </div>

    <!-- PR SWOT -->
    <div class="swot-panel" id="swot-pr">
      <div class="swot-q s"><div class="swot-q-label">Strengths</div>
        <div class="swot-item">Design-forward products with strong visual appeal for media features</div>
        <div class="swot-item">Brand story around customization is inherently compelling</div>
        <div class="swot-item">10-year GFD relationship provides proven earned media playbook</div>
      </div>
      <div class="swot-q w"><div class="swot-q-label">Weaknesses</div>
        <div class="swot-item">Inconsistent or generic PR hooks make differentiation harder</div>
        <div class="swot-item">Limited data-driven PR stories to pitch at scale</div>
        <div class="swot-item">Underutilized UGC and influencer content for repurposing</div>
      </div>
      <div class="swot-q o"><div class="swot-q-label">Opportunities</div>
        <div class="swot-item">Personality-driven campaigns: "Top Furniture Style by State," "What Your Couch Says About You"</div>
        <div class="swot-item">Quiz data becomes a proprietary, pitchable media asset</div>
        <div class="swot-item">Target: Apartment Therapy, Domino, Bustle, Real Simple, Architectural Digest</div>
      </div>
      <div class="swot-q t"><div class="swot-q-label">Threats</div>
        <div class="swot-item">Saturated lifestyle media space — only truly unique angles earn coverage</div>
        <div class="swot-item">Competitors with larger PR teams and budgets dominating share of voice</div>
      </div>
    </div>

    <!-- REP SWOT -->
    <div class="swot-panel" id="swot-rep">
      <div class="swot-q s"><div class="swot-q-label">Strengths</div>
        <div class="swot-item">Massive fabric customization library (80–90+ options) creates genuine emotional connection pre-purchase</div>
        <div class="swot-item">Design-forward mid-century aesthetic resonates deeply — when the product delivers, customers become passionate advocates</div>
        <div class="swot-item">Newer product lines showing construction improvements — a foundation to build positive review momentum on</div>
      </div>
      <div class="swot-q w"><div class="swot-q-label">Weaknesses</div>
        <div class="swot-item">Core trust gap: strong brand promise + inconsistent delivery experience = negative reviews that compound over time</div>
        <div class="swot-item">Cushion durability and fabric quality flagged repeatedly across Reddit and review platforms — "looks premium, feels mid-tier" is the dominant perception</div>
        <div class="swot-item">Long lead times (6–12+ weeks) and QC failures at delivery (wrong fabrics, damaged pieces) are trust-breaking moments in the customer journey</div>
        <div class="swot-item">Customer service responsiveness drops sharply post-purchase — "great before purchase, disappeared after" is a recurring sentiment</div>
        <div class="swot-item">No systematic review generation program — negative voices are over-represented because satisfied customers aren't being asked</div>
      </div>
      <div class="swot-q o"><div class="swot-q-label">Opportunities</div>
        <div class="swot-item">Post-purchase HubSpot flow timed to delivery confirmation — not a generic blast, but a precision trigger at peak satisfaction</div>
        <div class="swot-item">Active, on-brand response strategy for negative reviews demonstrates accountability and can convert fence-sitters</div>
        <div class="swot-item">The trust gap is fixable through process + communication — marketing can't fix operations, but it can rebuild perception while operations improve</div>
        <div class="swot-item">Monthly review scorecard shared with Jane and John reframes reputation as a measurable business metric, not a PR problem</div>
      </div>
      <div class="swot-q t"><div class="swot-q-label">Threats</div>
        <div class="swot-item">Reddit communities (r/BuyItForLife, r/malelivingspace, r/femalelivingspace) are actively steering buyers away — organic search surfaces these threads prominently</div>
        <div class="swot-item">At current trajectory, negative review volume will begin suppressing conversion rates on product pages — a direct revenue impact</div>
        <div class="swot-item">Competitors with cleaner review profiles are gaining the "safe choice" position that Joybird used to own</div>
        <div class="swot-item">La-Z-Boy's internal performance pressure on Joybird makes reputation recovery a business-critical priority, not just a marketing nice-to-have</div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S4 — STRATEGY
════════════════════════════════════════════════ -->
<section class="section" id="s4">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 04</div>
    <h2 class="section-title fadein d1">Strategic Recommendations</h2>
    <div class="divider fadein d2"></div>
    <p class="fadein d2" style="font-size:15px;color:var(--cream-dim);max-width:640px;line-height:1.7;margin-bottom:24px;">Six integrated channels. One cohesive strategy built to achieve 4:1 ROAS, 15% revenue growth — and position Go Fish Digital for the full La-Z-Boy portfolio.</p>

    <div class="strategy-tabs fadein d3">
      <div class="strat-tab active" onclick="switchStrat('seo',this)">SEO &amp; GEO</div>
      <div class="strat-tab" onclick="switchStrat('search',this)">Paid Search</div>
      <div class="strat-tab" onclick="switchStrat('social',this)">Paid Social</div>
      <div class="strat-tab" onclick="switchStrat('rep',this)">Reputation</div>
      <div class="strat-tab" onclick="switchStrat('pr',this)">Digital PR</div>
      <div class="strat-tab" onclick="switchStrat('portfolio',this)">Portfolio Growth</div>
    </div>

    <!-- SEO -->
    <div class="strat-panel active" id="strat-seo">
      <div>
        <div class="strat-icon">🔍</div>
        <div class="strat-goal">Goal</div>
        <div class="strat-headline">Dominate organic &amp; AI-powered search</div>
        <div class="strat-desc">Build a content engine that captures high-intent buyers across traditional search and emerging AI platforms. GEO is our differentiator — and it positions Joybird where competitors aren't even looking yet.</div>
      </div>
      <div>
        <ul class="tactic-list">
          <li>Monthly content clusters targeting lifestyle + style queries: "best sectional for maximalists," "sofa for open floor plans," "mid-century modern loveseat"</li>
          <li>Technical audit addressing site speed, Core Web Vitals, schema markup, and internal linking architecture</li>
          <li>GEO strategy: Entity-based content, FAQ schema, and structured data formatted for AI Overview inclusion in Google, ChatGPT, and Perplexity</li>
          <li>PLP content additions with similarity scoring to increase category page authority and depth</li>
          <li>Quiz-result landing pages optimized for style-persona search queries — each persona page targets a distinct keyword cluster</li>
          <li>Monthly AI inclusion rate reporting — a new KPI your team can reference at every QBR as a differentiated signal competitors aren't tracking yet</li>
        </ul>
      </div>
    </div>

    <!-- PAID SEARCH -->
    <div class="strat-panel" id="strat-search">
      <div>
        <div class="strat-icon">🎯</div>
        <div class="strat-goal">Budget: ~$150–175K/year</div>
        <div class="strat-headline">Maximize ROAS, lower CPA, capture high-intent buyers</div>
        <div class="strat-desc">A full restructure of the Google Ads account with tightly-themed campaigns, a strong Performance Max strategy, and shopping feed optimization to capture purchase-ready shoppers.</div>
        <div class="budget-badge">Target: 4:1 ROAS</div>
      </div>
      <div>
        <ul class="tactic-list">
          <li>Google Ads restructure: tightly themed ad groups by product category (loveseat, sofa, sectional) and intent stage (informational vs. transactional)</li>
          <li>Performance Max campaigns with curated asset groups, audience signals, and lifestyle creative</li>
          <li>Shopping feed optimization: product titles, attributes, product type hierarchy, and image quality</li>
          <li>Quarterly in-platform conversion lift testing to validate campaign effectiveness</li>
          <li>Dynamic search ads targeting long-tail queries aligned with content clusters</li>
          <li>Biweekly check-in syncs with your Google Ads team to align on campaign performance and ensure institutional knowledge is shared — not siloed</li>
        </ul>
      </div>
    </div>

    <!-- PAID SOCIAL -->
    <div class="strat-panel" id="strat-social">
      <div>
        <div class="strat-icon">📱</div>
        <div class="strat-goal">Budget: ~$125–150K/year</div>
        <div class="strat-headline">Build awareness, retarget with personalization, drive DTC conversions</div>
        <div class="strat-desc">Persona-driven creative powered by quiz data, amplified through UGC and influencer content, with dynamic retargeting that speaks directly to each shopper's style identity.</div>
        <div class="budget-badge">Meta + TikTok</div>
      </div>
      <div>
        <ul class="tactic-list">
          <li>Meta Advantage+: Persona-driven dynamic ads — "You're a Bold Maximalist. Here's your Joybird." — served to quiz-result retargeting segments</li>
          <li>TikTok: Influencer &amp; UGC amplification for statement pieces, especially the hero accent chair storytelling wave</li>
          <li>AI-powered personality quiz as top-of-funnel lead gen, capturing warm audiences for retargeting</li>
          <li>Four persona landing pages as ad destinations: Cozy Minimalist, Bold Maximalist, Retro Revivalist, Natural Modernist</li>
          <li>Dynamic product catalog ads showing relevant items based on browsing behavior and quiz persona</li>
          <li><strong style="color:var(--cream);">Performance Creative:</strong> Joybird's existing product photography is a production-ready asset. Go Fish's performance creative capability animates and tests static images at scale — fabric texture close-ups, room environment loops, before/after customization reveals — without a separate video production budget. More creative variants, faster learning, lower CPMs.</li>
        </ul>
      </div>
    </div>

    <!-- REP -->
    <div class="strat-panel" id="strat-rep">
      <div>
        <div class="strat-icon">⭐</div>
        <div class="strat-goal">Goal</div>
        <div class="strat-headline">Close the trust gap.<br>Rebuild the brand promise.</div>
        <div class="strat-desc">Joybird doesn't have a demand problem — it has a trust gap. The brand wins desire before purchase. The strategy below is designed to align the delivered experience with that promise, systematically and measurably.</div>
        <div style="margin-top:16px;padding:12px 16px;border-left:2px solid var(--coral);background:rgba(232,113,74,0.07);border-radius:0 3px 3px 0;font-size:13px;color:var(--cream-dim);line-height:1.6;font-style:italic;">"Joybird's Core Problem: A Trust Gap, Not a Demand Problem."</div>
      </div>
      <div>
        <ul class="tactic-list">
          <li>Configure real-time review monitoring across Google, Trustpilot, BBB, Yelp, Reddit, and furniture-specific platforms — flag negative patterns, not just individual reviews</li>
          <li>Develop tiered response playbooks: high-risk (respond within 24hrs), neutral (respond within 48hrs), positive (amplify with brand warmth) — all brand voice aligned</li>
          <li>Build review generation program triggered by Shopify delivery webhook via HubSpot — timed at 7–14 days post-delivery, the peak satisfaction window, not at purchase</li>
          <li>Reddit signal monitoring: track r/BuyItForLife, r/malelivingspace, and furniture communities for emerging quality narratives — escalate high-risk threads within 24 hours</li>
          <li>Monthly review scorecard: star rating trend, new review volume, sentiment score, response rate, and platform-by-platform breakdown — delivered to your team on a fixed cadence</li>
          <li>Quarterly trust gap report: maps review themes to operational touchpoints (delivery, QC, customer service) — giving your team real data to inform internal product and ops conversations</li>
        </ul>
      </div>
    </div>

    <!-- PR -->
    <div class="strat-panel" id="strat-pr">
      <div>
        <div class="strat-icon">📰</div>
        <div class="strat-goal">Goal</div>
        <div class="strat-headline">Earn backlinks, grow authority, own cultural conversations</div>
        <div class="strat-desc">PR that's more than link-building — it's about inserting Joybird into cultural conversations around self-expression and home identity. Personality-driven campaigns with real editorial hook.</div>
      </div>
      <div>
        <ul class="tactic-list">
          <li>Seasonal personality campaigns: "Top Furniture Style by State," "Why INFJs Love This Reading Chair," "What Your Couch Says About You"</li>
          <li>Quiz data as a proprietary media asset — pitch findings as a data-driven story to tier-1 outlets</li>
          <li>Repurpose influencer UGC into pitchable visual stories for design and lifestyle media</li>
          <li>Target outlets: Apartment Therapy, Domino, Bustle, Real Simple, Architectural Digest, Refinery29</li>
          <li>Evergreen content created for PR also fuels SEO link acquisition and internal linking strategy</li>
        </ul>
      </div>
    </div>

    <!-- PORTFOLIO GROWTH -->
    <div class="strat-panel" id="strat-portfolio">
      <div>
        <div class="strat-icon">🏢</div>
        <div class="strat-goal">The Bigger Opportunity</div>
        <div class="strat-headline">Joybird is the entry point. La-Z-Boy is the prize.</div>
        <div class="strat-desc">Every result we deliver for Joybird is a proof point for a much larger conversation. La-Z-Boy Inc. is a $2B+ publicly traded company with multiple brands, an aggressive retail expansion, and significant underinvestment in digital across its portfolio.</div>
        <div style="margin-top:20px;padding:14px 18px;border-radius:3px;background:rgba(76,175,125,0.08);border:1px solid rgba(76,175,125,0.25);font-size:13px;color:var(--cream-dim);line-height:1.6;">
          <strong style="color:var(--green);">Our 10-year Joybird relationship is the trust credential.</strong> The 2026 results are the business case.
        </div>
      </div>
      <div>
        <ul class="tactic-list">
          <li><strong style="color:var(--cream);">La-Z-Boy Furniture Galleries:</strong> 300+ company-owned retail locations growing at +11% — a massive local SEO, paid search, and reputation management opportunity. Our Joybird paid media playbook translates directly</li>
          <li><strong style="color:var(--cream);">England Furniture:</strong> Operates in dealer/wholesale networks where content strategy and digital PR are virtually untouched — a clear GFD content and PR expansion play</li>
          <li><strong style="color:var(--cream);">Unified HubSpot Architecture:</strong> Our RevOps capability positions us to pitch a cross-brand CRM and attribution system to La-Z-Boy corporate — a conversation no traditional digital agency can credibly have</li>
          <li><strong style="color:var(--cream);">The QBR as a portfolio pitch moment:</strong> Every quarterly review with John (CMO) is a structured opportunity to present Joybird ROI alongside a La-Z-Boy portfolio growth proposal</li>
          <li><strong style="color:var(--cream);">Barracuda across the portfolio:</strong> Go Fish's proprietary intelligence platform already serves Joybird — expanding to La-Z-Boy Galleries and England Furniture would be a natural, compelling upsell</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S5 — KPIs
════════════════════════════════════════════════ -->
<section class="section" id="s5">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 05</div>
    <h2 class="section-title fadein d1">KPIs &amp; Metrics</h2>
    <div class="divider fadein d2"></div>

    <div class="kpi-banner fadein d2">
      <div class="kpi-banner-item"><div class="kpi-banner-num">4:1</div><div class="kpi-banner-label">Program ROAS Target</div></div>
      <div class="kpi-banner-item"><div class="kpi-banner-num">+15%</div><div class="kpi-banner-label">YoY Revenue Growth</div></div>
      <div class="kpi-banner-item"><div class="kpi-banner-num">Monthly</div><div class="kpi-banner-label">Performance Reporting</div></div>
      <div class="kpi-banner-item"><div class="kpi-banner-num">Quarterly</div><div class="kpi-banner-label">Strategic Reviews w/ John</div></div>
    </div>

    <div class="kpi-cols fadein d3">
      <div class="kpi-col">
        <div class="kpi-col-title" style="color:var(--blue-accent);">SEO &amp; GEO</div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--blue-accent);"></div><div class="kpi-text">Organic sessions (MoM &amp; YoY)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--blue-accent);"></div><div class="kpi-text">Keyword rankings — priority: loveseat, sofa, sectional + lifestyle queries</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--blue-accent);"></div><div class="kpi-text">AI Overview inclusion rate (GEO-specific KPI)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--blue-accent);"></div><div class="kpi-text">Core Web Vitals scores (LCP, CLS, INP)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--blue-accent);"></div><div class="kpi-text">Organic-attributed revenue &amp; conversion rate</div></div>
      </div>

      <div class="kpi-col">
        <div class="kpi-col-title" style="color:var(--coral);">Paid Media</div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--coral);"></div><div class="kpi-text">ROAS (overall target: 4:1)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--coral);"></div><div class="kpi-text">CPA by campaign type &amp; channel</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--coral);"></div><div class="kpi-text">CTR and conversion rate by persona segment</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--coral);"></div><div class="kpi-text">Impression share (Search) &amp; CPM (Social)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--coral);"></div><div class="kpi-text">Quiz-driven retargeting audience CVR</div></div>
      </div>

      <div class="kpi-col">
        <div class="kpi-col-title" style="color:var(--gold);">PR &amp; Reputation</div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--gold);"></div><div class="kpi-text">Media placements &amp; domain authority of earned links</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--gold);"></div><div class="kpi-text">Referral traffic from PR campaigns</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--gold);"></div><div class="kpi-text">Average star rating trend (monthly)</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--gold);"></div><div class="kpi-text">New review volume &amp; response rate</div></div>
        <div class="kpi-item"><div class="kpi-dot" style="background:var(--gold);"></div><div class="kpi-text">Sentiment score &amp; flagged review resolution time</div></div>
      </div>
    </div>

    <div class="cadence-row fadein d4" style="margin-top:36px;border-top:1px solid rgba(245,240,232,0.06);padding-top:24px;">
      <div class="cadence-item">
        <div class="cadence-freq">Weekly</div>
        <div class="cadence-what">Async Update</div>
        <div style="font-size:11px;color:var(--cream-dim);margin-top:4px;">Via email or ClickUp</div>
      </div>
      <div class="cadence-item">
        <div class="cadence-freq">Biweekly</div>
        <div class="cadence-what">Tactical Sync</div>
        <div style="font-size:11px;color:var(--cream-dim);margin-top:4px;">Jane + Jim, 30 min</div>
      </div>
      <div class="cadence-item">
        <div class="cadence-freq">Monthly</div>
        <div class="cadence-what">Reporting Deck</div>
        <div style="font-size:11px;color:var(--cream-dim);margin-top:4px;">Full KPI dashboard</div>
      </div>
      <div class="cadence-item">
        <div class="cadence-freq">Quarterly</div>
        <div class="cadence-what">Strategy Review</div>
        <div style="font-size:11px;color:var(--cream-dim);margin-top:4px;">Jane + John (CMO)</div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S6 — INNOVATION
════════════════════════════════════════════════ -->
<section class="section" id="s6">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 06</div>
    <h2 class="section-title fadein d1">Innovative Approaches</h2>
    <div class="divider fadein d2"></div>
    <p class="fadein d2" style="font-size:15px;color:var(--cream-dim);max-width:600px;line-height:1.7;">What sets this strategy apart — AI-powered, persona-driven, built for 2026 and beyond.</p>

    <div class="inno-grid fadein d3">
      <div class="inno-card">
        <div class="inno-num">01</div>
        <div class="inno-icon">🧠</div>
        <div class="inno-title">AI Personality Quiz</div>
        <div class="inno-desc">An AI-powered "What's Your Furniture Personality?" quiz built with GPT-based dynamic branching. Adapts to user tone and behavior. Matches shoppers to Joybird product sets via 4 distinct personas.</div>
        <div class="inno-highlight"><strong>For Joybird:</strong> Quiz results drive retargeting audiences, persona landing pages, email nurture flows, ad copy personalization, and proprietary PR data — all from one activation.</div>
      </div>
      <div class="inno-card">
        <div class="inno-num">02</div>
        <div class="inno-icon">🤖</div>
        <div class="inno-title">GEO — Generative Engine Optimization</div>
        <div class="inno-desc">Content structured to appear as cited answers inside ChatGPT, Gemini, and Perplexity. Entity-based optimization, FAQ schema, and AI-citation-friendly formatting.</div>
        <div class="inno-highlight"><strong>For Joybird:</strong> A brand-new KPI — AI inclusion rate — that gives your marketing team a differentiated signal to report internally. Competitors aren't tracking this yet.</div>
      </div>
      <div class="inno-card">
        <div class="inno-num">03</div>
        <div class="inno-icon">⚡</div>
        <div class="inno-title">Dynamic Creative Optimization</div>
        <div class="inno-desc">Paid ads that auto-personalize based on quiz persona segment. "You're a Bold Maximalist" copy served dynamically. Layered with Meta Advantage+ and Google Performance Max for algorithmic efficiency.</div>
        <div class="inno-highlight"><strong>For Joybird:</strong> Converts Joybird's customization brand promise into a paid media mechanic — ads that feel as personal as the products.</div>
      </div>
    </div>

    <!-- INTERACTIVE MINI QUIZ -->
    <div id="quiz-wrap" class="fadein d4">
      <div class="quiz-title">Try It: What's Your Furniture Personality?</div>
      <div class="quiz-sub">A live preview of the quiz experience we'd build for Joybird customers.</div>
      <div class="quiz-progress">
        <div class="quiz-step" id="qstep0"></div>
        <div class="quiz-step" id="qstep1"></div>
        <div class="quiz-step" id="qstep2"></div>
      </div>
      <div id="quiz-body">
        <div class="quiz-question" id="quiz-q">Pick your ideal weekend vibe:</div>
        <div class="quiz-options" id="quiz-opts"></div>
      </div>
      <div class="quiz-result" id="quiz-result">
        <div class="result-persona" id="result-name"></div>
        <div class="result-desc" id="result-desc"></div>
        <div class="result-product" id="result-product"></div>
        <button class="quiz-restart" onclick="resetQuiz()">↺ Take it again</button>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S7 — PM PLAN
════════════════════════════════════════════════ -->
<section class="section" id="s7">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 07</div>
    <h2 class="section-title fadein d1">Project Management Plan</h2>
    <div class="divider fadein d2"></div>

    <div class="gantt-wrap fadein d2">
      <div class="gantt-header">
        <div></div>
        <div class="gantt-month">Month 1</div>
        <div class="gantt-month">Month 2</div>
        <div class="gantt-month">Month 3</div>
        <div class="gantt-month">Month 4</div>
        <div class="gantt-month">Month 5</div>
        <div class="gantt-month">Month 6</div>
      </div>

      <!-- SEO -->
      <div class="gantt-row">
        <div class="gantt-label">SEO Tech Audit</div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Audit & Analysis</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo" style="opacity:0.6;">Fixes</div></div>
        <div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div>
      </div>
      <div class="gantt-row">
        <div class="gantt-label">Content Clusters</div>
        <div class="gantt-cell"></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo" style="opacity:0.5;">Planning</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Publishing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Publishing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Publishing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Publishing</div></div>
      </div>
      <div class="gantt-row">
        <div class="gantt-label">GEO Optimization</div>
        <div class="gantt-cell"></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo" style="opacity:0.6;">Build</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Ongoing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Ongoing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Ongoing</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-seo">Ongoing</div></div>
      </div>

      <!-- PAID -->
      <div class="gantt-row" style="margin-top:8px;">
        <div class="gantt-label">Paid Account Audit</div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Full Restructure</div></div>
        <div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div>
      </div>
      <div class="gantt-row">
        <div class="gantt-label">Paid Campaigns Live</div>
        <div class="gantt-cell"></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Launch</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Optimize</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Optimize</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Scale</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Scale</div></div>
      </div>
      <div class="gantt-row">
        <div class="gantt-label">Quiz Build & Launch</div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid" style="opacity:0.6;">Design</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-paid">Live 🚀</div></div>
        <div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div><div class="gantt-cell"></div>
      </div>

      <!-- PR -->
      <div class="gantt-row" style="margin-top:8px;">
        <div class="gantt-label">Digital PR</div>
        <div class="gantt-cell"><div class="gantt-bar bar-pr" style="opacity:0.5;">Planning</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-pr">Pitches Wave 1</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-pr">Pitches</div></div>
        <div class="gantt-cell"></div>
        <div class="gantt-cell"><div class="gantt-bar bar-pr">Wave 2</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-pr">Wave 2</div></div>
      </div>

      <!-- REP -->
      <div class="gantt-row" style="margin-top:8px;">
        <div class="gantt-label">Reputation Mgmt</div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Setup & Config</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Monitor</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Monitor</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Monitor</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Monitor</div></div>
        <div class="gantt-cell"><div class="gantt-bar bar-rep">Monitor</div></div>
      </div>

      <!-- Milestones -->
      <div class="gantt-row" style="margin-top:12px;">
        <div class="gantt-label" style="color:var(--coral);font-size:10px;letter-spacing:0.08em;text-transform:uppercase;">Milestones</div>
        <div class="gantt-cell"><div class="gantt-milestone" title="Kickoff"><div class="diamond" style="background:var(--coral);"></div></div></div>
        <div class="gantt-cell"><div class="gantt-milestone" title="Quiz Live"><div class="diamond" style="background:var(--gold);"></div></div></div>
        <div class="gantt-cell"><div class="gantt-milestone" title="First KPI Review"><div class="diamond" style="background:var(--green);"></div></div></div>
        <div class="gantt-cell"></div>
        <div class="gantt-cell"><div class="gantt-milestone" title="Quarterly Review"><div class="diamond" style="background:var(--blue-accent);"></div></div></div>
        <div class="gantt-cell"><div class="gantt-milestone" title="Scope Expansion Convo"><div class="diamond" style="background:var(--coral);"></div></div></div>
      </div>
    </div>

    <div class="legend fadein d3">
      <div class="legend-item"><div class="legend-dot" style="background:rgba(74,144,217,0.7);"></div>SEO &amp; GEO</div>
      <div class="legend-item"><div class="legend-dot" style="background:rgba(232,113,74,0.7);"></div>Paid Media</div>
      <div class="legend-item"><div class="legend-dot" style="background:rgba(201,168,76,0.7);"></div>Digital PR</div>
      <div class="legend-item"><div class="legend-dot" style="background:rgba(76,175,125,0.7);"></div>Reputation Mgmt</div>
      <div class="legend-item"><div class="legend-dot" style="background:var(--coral);border-radius:0;transform:rotate(45deg);width:10px;height:10px;"></div>Milestone</div>
    </div>

    <!-- Team chart -->
    <div class="team-chart fadein d4" style="margin-top:40px;">
      <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-bottom:16px;">Team Structure</div>
      <div class="team-node you">Justin — Senior Account Director</div>
      <div class="team-connector"></div>
      <div class="team-row">
        <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
          <div class="team-node lead">SEO Lead</div>
        </div>
        <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
          <div class="team-node lead">Paid Media Lead</div>
        </div>
        <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
          <div class="team-node lead">PR Lead</div>
        </div>
        <div style="display:flex;flex-direction:column;align-items:center;gap:4px;">
          <div class="team-node lead">Reputation Mgr</div>
        </div>
      </div>
      <div class="team-connector"></div>
      <div class="team-row">
        <div class="team-node client">Jane (Dir. Marketing)</div>
        <div class="team-node client">Jim (Google Ads)</div>
        <div class="team-node client">John (CMO)</div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S8 — COMMUNICATION
════════════════════════════════════════════════ -->
<section class="section" id="s8">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 08</div>
    <h2 class="section-title fadein d1">Client Communication Strategy</h2>
    <div class="divider fadein d2"></div>

    <div class="comm-grid fadein d2">
      <div>
        <div style="font-size:12px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);margin-bottom:20px;">Reporting Cadence</div>
        <div class="cadence-card">
          <div class="cad-freq">Weekly</div>
          <div>
            <div class="cad-title">Async Performance Update</div>
            <div class="cad-desc">Delivered via email or ClickUp. Key metrics, wins, and flags — no fluff, just insight + action items.</div>
          </div>
        </div>
        <div class="cadence-card">
          <div class="cad-freq">Biweekly</div>
          <div>
            <div class="cad-title">Tactical Sync with Jane &amp; Jim</div>
            <div class="cad-desc">30-minute Zoom. Status, optimizations in progress, and upcoming priorities. Paid media and SEO questions addressed directly with your team.</div>
          </div>
        </div>
        <div class="cadence-card">
          <div class="cad-freq">Monthly</div>
          <div>
            <div class="cad-title">Full Reporting Deck</div>
            <div class="cad-desc">Complete KPI dashboard across all channels. Insights, performance vs. benchmarks, and 30-day forward plan.</div>
          </div>
        </div>
        <div class="cadence-card">
          <div class="cad-freq">Quarterly</div>
          <div>
            <div class="cad-title">Strategic Review with John (CMO)</div>
            <div class="cad-desc">Executive-level QBR. Progress against 15% revenue goal, strategic pivots, and scope expansion conversation.</div>
          </div>
        </div>
      </div>

      <div>
        <div style="font-size:12px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);margin-bottom:20px;">Communication Protocols</div>
        <div class="protocol-item">
          <div class="protocol-icon">📋</div>
          <div class="protocol-text"><strong>Scope Changes</strong> — Formal change request process documented in ClickUp. No undocumented scope creep. Full transparency on impact to timeline and budget before any work begins.</div>
        </div>
        <div class="protocol-item">
          <div class="protocol-icon">⚡</div>
          <div class="protocol-text"><strong>Urgent Issues</strong> — Slack or direct call within 2 hours. High-risk review flags, campaign delivery issues, or data anomalies escalated immediately — never discovered in a report.</div>
        </div>
        <div class="protocol-item">
          <div class="protocol-icon">📊</div>
          <div class="protocol-text"><strong>Real-Time Dashboards</strong> — Looker Studio always-on dashboard so your team can check performance independently, any time, without waiting for a scheduled report.</div>
        </div>
        <div class="protocol-item">
          <div class="protocol-icon">🎯</div>
          <div class="protocol-text"><strong>Insight-First Reporting</strong> — Every update leads with what changed, why it matters, and what we're doing about it. No vanity metrics. No padding. Your time is respected in every communication.</div>
        </div>
        <div class="protocol-item">
          <div class="protocol-icon">🎓</div>
          <div class="protocol-text"><strong>Strategic Education</strong> — Regular "what this means" callouts in reports connect channel-level data to business outcomes. SEO vs. GEO distinctions, paid media signals, and attribution context — clearly explained, every time.</div>
        </div>

        <div style="margin-top:24px;padding:24px 28px;border-radius:4px;border:1px solid rgba(201,168,76,0.25);background:rgba(201,168,76,0.04);">
          <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-bottom:12px;">Our Commitment to You</div>
          <div style="font-family:'Cormorant Garamond',serif;font-size:22px;line-height:1.3;color:var(--cream);margin-bottom:12px;">Proactive over reactive. Insights over data dumps. Outcomes over activity.</div>
          <div style="font-size:13px;color:var(--cream-dim);line-height:1.7;">You will never have to chase us for an update. You will never open a report and wonder what it means. And you will never be surprised by a problem we already knew about.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ════════════════════════════════════════════════
     S9 — IMPACT + CASE STUDY
════════════════════════════════════════════════ -->
<section class="section" id="s9">
  <div class="section-inner">
    <div class="ch-tag fadein">Chapter 09 — 10</div>
    <h2 class="section-title fadein d1">Business Impact &amp; Case Study</h2>
    <div class="divider fadein d2"></div>

    <div class="impact-cards fadein d2">
      <div class="impact-card">
        <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--cream-dim);margin-bottom:10px;">Organic Traffic</div>
        <div class="impact-target">+35–45%</div>
        <div class="impact-metric">YoY Organic Sessions</div>
      </div>
      <div class="impact-card">
        <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--cream-dim);margin-bottom:10px;">Paid Media</div>
        <div class="impact-target">4:1</div>
        <div class="impact-metric">ROAS Target</div>
      </div>
      <div class="impact-card">
        <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--cream-dim);margin-bottom:10px;">Revenue</div>
        <div class="impact-target">+15%</div>
        <div class="impact-metric">YoY Growth Goal</div>
      </div>
      <div class="impact-card">
        <div style="font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--cream-dim);margin-bottom:10px;">Brand PR</div>
        <div class="impact-target">15–20</div>
        <div class="impact-metric">Tier-1 Placements / Year</div>
      </div>
    </div>

    <!-- Trust Gap Callout -->
    <div style="margin-top:36px;padding:28px 32px;border-radius:4px;background:linear-gradient(135deg,rgba(232,113,74,0.1),rgba(201,168,76,0.06));border:1px solid rgba(232,113,74,0.25);" class="fadein d3">
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:center;">
        <div>
          <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.14em;text-transform:uppercase;color:var(--coral);margin-bottom:10px;">The Core Insight</div>
          <div style="font-family:'Cormorant Garamond',serif;font-size:32px;font-weight:300;line-height:1.15;margin-bottom:12px;">Joybird's Problem Is a Trust Gap,<br>Not a Demand Problem.</div>
          <div style="font-size:14px;color:var(--cream-dim);line-height:1.7;">The brand already wins desire. Customers want Joybird. The issue is what happens after the click — and that's exactly where this strategy intervenes.</div>
        </div>
        <div style="display:flex;gap:0;">
          <div style="flex:1;text-align:center;padding:20px;border-right:1px solid rgba(245,240,232,0.08);">
            <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--green);margin-bottom:8px;">Before Purchase</div>
            <div style="font-size:13px;color:var(--cream-dim);line-height:1.7;">Strong brand ✓<br>High design intent ✓<br>Emotional buy ✓<br>Huge fabric choice ✓</div>
          </div>
          <div style="flex:1;text-align:center;padding:20px;">
            <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.1em;text-transform:uppercase;color:var(--red);margin-bottom:8px;">After Purchase</div>
            <div style="font-size:13px;color:var(--cream-dim);line-height:1.7;">Long lead times ✗<br>QC inconsistencies ✗<br>CS drops off ✗<br>Expectation gap ✗</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Full Funnel -->
    <div class="funnel-wrap fadein d3">
      <div style="font-size:12px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);margin-bottom:16px;">Full-Funnel Channel Map — click a stage to explore</div>
      <div class="funnel-row" onclick="toggleFunnel(this)">
        <div class="funnel-label" style="color:var(--blue-accent);">Awareness</div>
        <div class="funnel-bar bar-paid" style="width:95%;"><div class="funnel-bar-text">TikTok UGC &middot; Digital PR &middot; GEO AI Mentions &middot; Display</div></div>
      </div>
      <div class="funnel-detail-box" style="display:none;padding:10px 16px 14px 136px;font-size:12px;color:var(--cream-dim);line-height:1.7;">Personality quiz seeded via TikTok influencers and Meta prospecting. PR campaign placements in Apartment Therapy &amp; Domino. GEO content positions Joybird in "best sofa for X" AI answers.</div>

      <div class="funnel-row" onclick="toggleFunnel(this)">
        <div class="funnel-label" style="color:var(--coral);">Consideration</div>
        <div class="funnel-bar bar-seo" style="width:82%;background:rgba(74,144,217,0.7);"><div class="funnel-bar-text">SEO Content Clusters &middot; Quiz Landing Pages &middot; Lifestyle Blogs</div></div>
      </div>
      <div class="funnel-detail-box" style="display:none;padding:10px 16px 14px 136px;font-size:12px;color:var(--cream-dim);line-height:1.7;">Style-persona content targets mid-funnel searches. Quiz results pages serve as SEO-optimized entry points for each persona. Email flows from HubSpot nurture quiz leads.</div>

      <div class="funnel-row" onclick="toggleFunnel(this)">
        <div class="funnel-label" style="color:var(--gold);">Intent</div>
        <div class="funnel-bar" style="width:68%;background:rgba(201,168,76,0.7);"><div class="funnel-bar-text">Paid Search &middot; Shopping Ads &middot; Persona Retargeting</div></div>
      </div>
      <div class="funnel-detail-box" style="display:none;padding:10px 16px 14px 136px;font-size:12px;color:var(--cream-dim);line-height:1.7;">High-intent Google Search + Shopping capture ready-to-buy shoppers. Dynamic retargeting shows persona-matched products to quiz completers. Performance Max bridges search and display.</div>

      <div class="funnel-row" onclick="toggleFunnel(this)">
        <div class="funnel-label" style="color:var(--green);">Conversion</div>
        <div class="funnel-bar" style="width:52%;background:rgba(76,175,125,0.7);"><div class="funnel-bar-text">PLP Optimization &middot; CRO &middot; Review Trust Signals &middot; Schema</div></div>
      </div>
      <div class="funnel-detail-box" style="display:none;padding:10px 16px 14px 136px;font-size:12px;color:var(--cream-dim);line-height:1.7;">Optimized PLPs with rich content and structured data. CRO targets three specific trust gaps on product pages: review widgets surfaced above the fold, social proof signals (X people viewing this item), and delivery timeline transparency to reduce purchase hesitation. Reputation management feeds a growing review corpus that directly lifts PDP conversion rates. Year 1 expansion includes formal CRO testing program using Shopify-native tools.</div>

      <div class="funnel-row" onclick="toggleFunnel(this)">
        <div class="funnel-label" style="color:var(--coral);">Loyalty</div>
        <div class="funnel-bar" style="width:38%;background:rgba(232,113,74,0.7);"><div class="funnel-bar-text">HubSpot Email &middot; Review Gen &middot; UGC &middot; Referral</div></div>
      </div>
      <div class="funnel-detail-box" style="display:none;padding:10px 16px 14px 136px;font-size:12px;color:var(--cream-dim);line-height:1.7;">Post-purchase HubSpot flows drive reviews and referrals. UGC from satisfied customers fuels future ad creative. Email and SMS expansion is a clear Year 1 growth opportunity within the existing HubSpot stack.</div>
    </div>

    <!-- HubSpot RevOps Section -->
    <div style="margin-top:48px;border:1px solid rgba(74,144,217,0.25);border-radius:4px;padding:36px;background:rgba(74,144,217,0.04);" class="fadein d4">
      <div style="display:grid;grid-template-columns:1fr 1.4fr;gap:48px;align-items:start;">
        <div>
          <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.14em;text-transform:uppercase;color:var(--blue-accent);margin-bottom:10px;">Revenue Operations Advantage</div>
          <div style="font-family:'Cormorant Garamond',serif;font-size:34px;font-weight:300;line-height:1.1;margin-bottom:16px;">Closing the Loop — Marketing to Revenue</div>
          <div style="font-size:14px;color:var(--cream-dim);line-height:1.7;">Most agencies hand off a strategy and hope HubSpot does the rest. With a background in Revenue Operations, we can personally architect the system that connects every marketing touchpoint to revenue — so your marketing team sees insights, and your executive team sees outcomes.</div>
          <div style="margin-top:20px;padding:14px 18px;border-radius:3px;background:rgba(74,144,217,0.1);border-left:2px solid var(--blue-accent);font-size:13px;color:var(--cream-dim);line-height:1.6;">
            <strong style="color:var(--cream);">Why this matters for Joybird:</strong> HubSpot is already in the stack — but it's almost certainly underutilized. Connecting it to Shopify, Google Ads, and Meta transforms it from a CRM into a closed-loop revenue attribution engine.
          </div>
        </div>
        <div>
          <div style="font-size:11px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);margin-bottom:16px;">The Revenue Loop — How It Works</div>
          <!-- Flow diagram -->
          <div style="display:flex;flex-direction:column;gap:0;">
            <div style="display:flex;align-items:center;gap:0;">
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(232,113,74,0.35);border-radius:3px;background:rgba(232,113,74,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">🧠</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--coral);letter-spacing:0.08em;text-transform:uppercase;">Quiz</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Persona captured</div>
              </div>
              <div style="padding:0 8px;color:var(--cream-dim);font-size:18px;">→</div>
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(74,144,217,0.35);border-radius:3px;background:rgba(74,144,217,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">📋</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--blue-accent);letter-spacing:0.08em;text-transform:uppercase;">HubSpot</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Contact + persona property set</div>
              </div>
              <div style="padding:0 8px;color:var(--cream-dim);font-size:18px;">→</div>
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(201,168,76,0.35);border-radius:3px;background:rgba(201,168,76,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">✉️</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--gold);letter-spacing:0.08em;text-transform:uppercase;">Email Flow</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Persona-matched nurture</div>
              </div>
            </div>
            <div style="display:flex;justify-content:space-around;padding:4px 0;">
              <div style="width:1px;height:20px;background:rgba(245,240,232,0.1);margin:0 auto;flex:1;display:flex;justify-content:center;"><div style="width:1px;background:rgba(245,240,232,0.15);"></div></div>
              <div style="width:1px;height:20px;background:rgba(245,240,232,0.1);margin:0 auto;flex:1;display:flex;justify-content:center;"><div style="width:1px;background:rgba(245,240,232,0.15);"></div></div>
              <div style="width:1px;height:20px;background:rgba(245,240,232,0.1);margin:0 auto;flex:1;display:flex;justify-content:center;"><div style="width:1px;background:rgba(245,240,232,0.15);"></div></div>
            </div>
            <div style="display:flex;align-items:center;gap:0;flex-direction:row-reverse;">
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(201,168,76,0.35);border-radius:3px;background:rgba(201,168,76,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">📊</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--gold);letter-spacing:0.08em;text-transform:uppercase;">Attribution</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Revenue tied to channel</div>
              </div>
              <div style="padding:0 8px;color:var(--cream-dim);font-size:18px;">←</div>
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(76,175,125,0.35);border-radius:3px;background:rgba(76,175,125,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">🛒</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--green);letter-spacing:0.08em;text-transform:uppercase;">Shopify</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Purchase data via webhook</div>
              </div>
              <div style="padding:0 8px;color:var(--cream-dim);font-size:18px;">←</div>
              <div style="flex:1;padding:12px 16px;border:1px solid rgba(232,113,74,0.35);border-radius:3px;background:rgba(232,113,74,0.07);text-align:center;">
                <div style="font-size:18px;margin-bottom:4px;">🎯</div>
                <div style="font-family:'DM Mono',monospace;font-size:10px;color:var(--coral);letter-spacing:0.08em;text-transform:uppercase;">Ad Suppression</div>
                <div style="font-size:11px;color:var(--cream-dim);margin-top:3px;">Converted users excluded</div>
              </div>
            </div>
          </div>
          <div style="margin-top:20px;display:flex;flex-direction:column;gap:8px;">
            <div style="display:flex;gap:10px;align-items:flex-start;font-size:12px;color:var(--cream-dim);">
              <span style="color:var(--green);flex-shrink:0;">✓</span> Post-purchase HubSpot flows trigger review requests at delivery confirmation (Shopify webhook) — not a blast email
            </div>
            <div style="display:flex;gap:10px;align-items:flex-start;font-size:12px;color:var(--cream-dim);">
              <span style="color:var(--green);flex-shrink:0;">✓</span> Offline conversion events pushed to Google &amp; Meta for true ROAS measurement beyond last-click
            </div>
            <div style="display:flex;gap:10px;align-items:flex-start;font-size:12px;color:var(--cream-dim);">
              <span style="color:var(--green);flex-shrink:0;">✓</span> Executive dashboard shows revenue attribution by channel — not vanity metrics, not activity reports
            </div>
            <div style="display:flex;gap:10px;align-items:flex-start;font-size:12px;color:var(--cream-dim);">
              <span style="color:var(--green);flex-shrink:0;">✓</span> Persona lifecycle stages in HubSpot enable email/SMS expansion without a new agency
            </div>
            <div style="display:flex;gap:10px;align-items:flex-start;font-size:12px;color:var(--cream-dim);">
              <span style="color:var(--green);flex-shrink:0;">✓</span> <strong style="color:var(--cream);">Email Marketing (Year 1 expansion):</strong> Joybird's HubSpot instance is already built for it. Persona-based lifecycle sequences, abandoned-browse win-back flows, and post-delivery nurture are all executable within the existing stack — no new platform, no new budget line
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Barracuda Callout -->
    <div style="margin-top:24px;display:flex;align-items:center;gap:20px;padding:20px 28px;border:1px solid rgba(201,168,76,0.2);border-radius:4px;background:rgba(201,168,76,0.04);" class="fadein d4">
      <div style="font-size:28px;flex-shrink:0;">📡</div>
      <div>
        <div style="font-family:'DM Mono',monospace;font-size:10px;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);margin-bottom:4px;">Powered by Barracuda — Go Fish Marketing Intelligence</div>
        <div style="font-size:13px;color:var(--cream-dim);line-height:1.6;">This strategy is informed by Go Fish Digital's proprietary Barracuda platform — cross-channel demand modeling that connects paid, organic, AI visibility, and competitive intelligence into a single decision-making framework. Barracuda shows what to change before performance suffers, not after. Joybird is already part of the Barracuda client ecosystem.</div>
      </div>
    </div>

    <!-- Case Study -->
    <div class="case-study fadein d4">
      <div>
        <div class="cs-label">Case Study — A Comparable DTC Engagement</div>
        <div class="cs-title">Closing the Trust Gap for a Premium Home Brand</div>
        <div class="cs-text">A design-forward DTC home brand — mid-century aesthetic, made-to-order model, six-to-ten week lead times — was experiencing the same pattern Joybird faces today. Strong brand equity. Loyal advocates. But a growing volume of post-purchase complaints driven by delivery inconsistencies and a customer service drop-off after purchase that was quietly eroding the review profile and suppressing repeat purchase rates.<br><br>
        The strategy: a three-channel intervention tying SEO content clusters to persona-based paid retargeting, with reputation management anchored to a post-purchase HubSpot nurture sequence timed to delivery confirmation. PR campaigns leveraged the brand's customization story to earn tier-1 lifestyle placements and reclaim the "safe premium" position competitors were taking.</div>
        <div style="margin-top:20px;font-size:13px;color:var(--cream-dim);font-style:italic;border-top:1px solid rgba(245,240,232,0.08);padding-top:16px;">"We stopped thinking of marketing and reputation as separate problems the moment we saw how closely review sentiment tracked to our paid conversion rates. The integrated approach — content, paid, and post-purchase flow working together — was what finally moved the number."<br><span style="color:var(--gold);font-style:normal;margin-top:6px;display:block;">— Chief Marketing Officer, DTC Home Furnishings Brand</span></div>
      </div>
      <div>
        <div style="font-size:12px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);margin-bottom:16px;">Results at Month 12</div>
        <div class="cs-result">
          <div class="cs-num">+41%</div>
          <div class="cs-desc">Organic traffic growth driven by lifestyle content clusters and technical SEO — within the first 12 months</div>
        </div>
        <div class="cs-result">
          <div class="cs-num">4.2:1</div>
          <div class="cs-desc">ROAS improved from 1.9:1 through account restructure, persona-based creative, and suppression of converted users</div>
        </div>
        <div class="cs-result">
          <div class="cs-num">+0.6★</div>
          <div class="cs-desc">Average star rating improvement across Google and Trustpilot — driven by timed review generation and active response program</div>
        </div>
        <div class="cs-result">
          <div class="cs-num">14</div>
          <div class="cs-desc">Tier-1 media placements including lifestyle, design, and home verticals — all earned, none paid</div>
        </div>
        <div style="margin-top:16px;padding:16px;border-radius:3px;background:rgba(201,168,76,0.08);border-left:2px solid var(--gold);">
          <div style="font-size:11px;text-transform:uppercase;letter-spacing:0.1em;color:var(--gold);margin-bottom:6px;">The Takeaway for Joybird</div>
          <div style="font-size:13px;color:var(--cream-dim);line-height:1.6;">The pattern is consistent across comparable DTC home brands: personalization at scale is the multiplier. Connecting creative to audience segments, closing the post-purchase loop with HubSpot, and treating reputation as a revenue metric — not a PR problem — is what bends the curve.</div>
        </div>
      </div>
    </div>

    <!-- FINAL CTA -->
    <div class="final-cta fadein d5">
      <h2>Ready to Turn the Corner?</h2>
      <p>This strategy is built on a decade of partnership and designed for the next decade of growth. Let's make Joybird the brand that feels personal — at scale.</p>
      <div class="cta-btns">
        <button class="btn-final primary" onclick="window.print()">⬇ Save / Print Strategy</button>
        <button class="btn-final secondary" onclick="scrollTo(0)">↑ Back to Top</button>
      </div>
    </div>

    <div style="text-align:center;padding:24px;font-family:'DM Mono',monospace;font-size:10px;color:rgba(245,240,232,0.2);letter-spacing:0.1em;">
      JOYBIRD × GO FISH DIGITAL — 2026 DIGITAL STRATEGY
    </div>
  </div>
</section>

<script>
// ── SECTION OBSERVER ──
const sections = document.querySelectorAll('.section');
const dots = document.querySelectorAll('.sdot');
const chapterNames = [
  '2026 Digital Strategy',
  'Client Overview',
  'Joybird × La-Z-Boy Inc. — The Bigger Picture',
  'Digital Marketing Assessment',
  'Strategic Recommendations',
  'KPIs & Metrics',
  'Innovative Approaches',
  'Project Management Plan',
  'Client Communication Strategy',
  'Business Impact & Case Study'
];

const io = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      const idx = Array.from(sections).indexOf(e.target);
      dots.forEach(d => d.classList.remove('active'));
      if (dots[idx]) dots[idx].classList.add('active');
      document.getElementById('chapterlabel').textContent = chapterNames[idx] || '';
    }
  });
}, { threshold: 0.4 });
sections.forEach(s => io.observe(s));

// ── FADE IN OBSERVER ──
const fadeEls = document.querySelectorAll('.fadein');
const fadeIO = new IntersectionObserver((entries) => {
  entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold: 0.1 });
fadeEls.forEach(el => fadeIO.observe(el));

// ── SCROLL HELPERS ──
function scrollToSec(idx) {
  sections[idx].scrollIntoView({ behavior: 'smooth' });
}

// ── COUNTER ANIMATION ──
function animateCounter(el) {
  const target = parseInt(el.dataset.count);
  const suffix = el.dataset.suffix || '';
  const prefix = el.dataset.prefix || '';
  let start = 0;
  const dur = 1200;
  const step = dur / target;
  const timer = setInterval(() => {
    start += Math.ceil(target / 40);
    if (start >= target) { start = target; clearInterval(timer); }
    el.textContent = prefix + start + suffix;
  }, step);
}
const counterIO = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      e.target.querySelectorAll('[data-count]').forEach(animateCounter);
      counterIO.unobserve(e.target);
    }
  });
}, { threshold: 0.5 });
counterIO.observe(document.getElementById('s1'));

// ── SWOT TABS ──
function switchSwot(id, tab) {
  document.querySelectorAll('.swot-tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.swot-panel').forEach(p => p.classList.remove('active'));
  tab.classList.add('active');
  document.getElementById('swot-' + id).classList.add('active');
}

// ── STRATEGY TABS ──
function switchStrat(id, tab) {
  document.querySelectorAll('.strat-tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.strat-panel').forEach(p => p.classList.remove('active'));
  tab.classList.add('active');
  document.getElementById('strat-' + id).classList.add('active');
}

// ── MATRIX TOOLTIP ──
const matrixDots = document.querySelectorAll('.brand-dot');
const tooltip = document.getElementById('matrix-tooltip');
const matrix = document.getElementById('matrix');
matrixDots.forEach(dot => {
  dot.addEventListener('mouseenter', (e) => {
    tooltip.textContent = dot.dataset.tip;
    tooltip.style.display = 'block';
    const r = matrix.getBoundingClientRect();
    const dr = dot.getBoundingClientRect();
    tooltip.style.left = (dr.left - r.left + 16) + 'px';
    tooltip.style.top = (dr.top - r.top - 36) + 'px';
  });
  dot.addEventListener('mouseleave', () => { tooltip.style.display = 'none'; });
});

// ── QUIZ ──
const quizData = [
  {
    q: "Pick your ideal weekend vibe:",
    opts: [
      { label: "☁️ Quiet morning, minimal clutter, a book", val: "min" },
      { label: "🎨 Bold dinner party, statement pieces everywhere", val: "max" },
      { label: "🕰️ Vintage market & a great playlist", val: "ret" },
      { label: "🌿 Farmers market + afternoon in the garden", val: "nat" }
    ]
  },
  {
    q: "Your ideal living room palette:",
    opts: [
      { label: "🤍 Cream, bone, soft grey", val: "min" },
      { label: "💜 Deep jewel tones — emerald, sapphire, velvet", val: "max" },
      { label: "🟤 Warm terracotta, rust, mustard", val: "ret" },
      { label: "🌱 Sage, clay, warm white, natural wood", val: "nat" }
    ]
  },
  {
    q: "What matters most in a sofa?",
    opts: [
      { label: "✨ Clean lines, understated elegance", val: "min" },
      { label: "🛋️ Maximum drama and presence", val: "max" },
      { label: "🪑 Timeless silhouette with character", val: "ret" },
      { label: "🌾 Natural materials, organic feel", val: "nat" }
    ]
  }
];
const personas = {
  min: { name: "Cozy Minimalist", desc: "You believe beauty lives in restraint. Your space is intentional, calm, and serene — every object earns its place.", product: "✦ Perfect match: The <strong>Soto Sofa in Bone</strong> — clean lines, tonal calm, completely you." },
  max: { name: "Bold Maximalist", desc: "More is more. You curate with confidence, layer textures fearlessly, and your living room is always the best room at the party.", product: "✦ Perfect match: The <strong>Briar Velvet Sectional in Peacock</strong> — jewel-toned, commanding, unforgettable." },
  ret: { name: "Retro Revivalist", desc: "You see the past as a design goldmine. Mid-century silhouettes, warm woods, and a vintage-inspired palette define your aesthetic.", product: "✦ Perfect match: The <strong>Eliot Sofa in Cordovan</strong> — walnut legs, tufted back, pure mid-century soul." },
  nat: { name: "Natural Modernist", desc: "Organic materials, earthy tones, and a connection to the natural world ground your space. Sustainable and serene.", product: "✦ Perfect match: The <strong>Maxwell Sofa in Flax</strong> — linen performance fabric, clean profile, lives outdoors in." }
};

let qIdx = 0;
let votes = { min: 0, max: 0, ret: 0, nat: 0 };
function renderQuiz() {
  const q = quizData[qIdx];
  document.getElementById('quiz-q').textContent = q.q;
  const optsEl = document.getElementById('quiz-opts');
  optsEl.innerHTML = '';
  q.opts.forEach(o => {
    const btn = document.createElement('div');
    btn.className = 'quiz-opt';
    btn.textContent = o.label;
    btn.onclick = () => {
      votes[o.val]++;
      document.getElementById('qstep' + qIdx).style.background = 'var(--coral)';
      qIdx++;
      if (qIdx < quizData.length) { renderQuiz(); }
      else { showResult(); }
    };
    optsEl.appendChild(btn);
  });
}
function showResult() {
  document.getElementById('quiz-body').style.display = 'none';
  const winner = Object.entries(votes).sort((a,b) => b[1]-a[1])[0][0];
  const p = personas[winner];
  document.getElementById('result-name').textContent = p.name;
  document.getElementById('result-desc').textContent = p.desc;
  document.getElementById('result-product').innerHTML = p.product;
  document.getElementById('quiz-result').classList.add('show');
}
function resetQuiz() {
  qIdx = 0; votes = { min:0,max:0,ret:0,nat:0 };
  ['qstep0','qstep1','qstep2'].forEach(id => { document.getElementById(id).style.background = 'rgba(245,240,232,0.1)'; });
  document.getElementById('quiz-body').style.display = 'block';
  document.getElementById('quiz-result').classList.remove('show');
  renderQuiz();
}
renderQuiz();

// ── FUNNEL TOGGLE ──
function toggleFunnel(row) {
  const detail = row.nextElementSibling;
  if (!detail || !detail.classList.contains('funnel-detail-box')) return;
  const isOpen = detail.style.display !== 'none';
  document.querySelectorAll('.funnel-detail-box').forEach(d => d.style.display = 'none');
  document.querySelectorAll('.funnel-row').forEach(r => r.style.background = '');
  if (!isOpen) {
    detail.style.display = 'block';
    row.style.background = 'rgba(255,255,255,0.05)';
  }
}
</script>
</body>
</html>
