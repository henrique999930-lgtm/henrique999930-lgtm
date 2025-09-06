<?xml version="1.0" encoding="UTF-8"?>
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="360" viewBox="0 0 1200 360" role="img" aria-labelledby="title desc">
  <title id="title">Carlos Henrique — Engenheiro de Dados</title>
  <desc id="desc">Banner profissional com nome, título e principais skills.</desc>

  <defs>
    <linearGradient id="bg" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0" stop-color="#0f1724"/>
      <stop offset="1" stop-color="#071023"/>
    </linearGradient>

    <linearGradient id="accent" x1="0" x2="1">
      <stop offset="0" stop-color="#60a5fa"/>
      <stop offset="0.5" stop-color="#34d399"/>
      <stop offset="1" stop-color="#a78bfa"/>
    </linearGradient>

    <style type="text/css"><![CDATA[
      .name { font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif; font-weight:700; font-size:42px; fill: url(#accent); -webkit-font-smoothing:antialiased; }
      .title { font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif; font-weight:600; font-size:18px; fill:#cbd5e1; }
      .small { font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif; font-weight:500; font-size:14px; fill:#94a3b8; }
      .pill-text { font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif; font-weight:600; font-size:13px; fill:#0b1220; }
      .pill-dark-text { font-family: Inter, "Segoe UI", Roboto, Arial, sans-serif; font-weight:600; font-size:13px; fill:#ffffff; }
    ]]></style>
  </defs>

  <!-- Background -->
  <rect x="0" y="0" width="1200" height="360" fill="url(#bg)"/>

  <!-- Decorative soft shapes -->
  <g opacity="0.10">
    <circle cx="120" cy="60" r="80" fill="#0ea5b7"/>
    <circle cx="980" cy="210" r="120" fill="#6ee7b7"/>
  </g>

  <!-- Left column: name & info -->
  <g transform="translate(70,72)">
    <text x="0" y="40" class="name">Carlos Henrique</text>
    <text x="0" y="78" class="title">Engenheiro de Dados</text>
    <text x="0" y="110" class="small" xml:space="preserve">Arquitetando e otimizando ecossistemas de dados ponta a ponta na nuvem (AWS / GCP).</text>
    <text x="0" y="140" class="small">Brasília · Remoto · henrique999930-lgtm</text>

    <!-- Tech pills row 1 -->
    <g transform="translate(0,170)">
      <rect x="0" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="18" y="24" class="pill-text">AWS</text>

      <rect x="136" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="154" y="24" class="pill-text">GCP</text>

      <rect x="272" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="290" y="24" class="pill-text">Docker</text>

      <rect x="408" y="0" width="160" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="426" y="24" class="pill-text">Python · PySpark</text>
    </g>

    <!-- Tech pills row 2 -->
    <g transform="translate(0,214)">
      <rect x="0" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="18" y="24" class="pill-text">SQL</text>

      <rect x="136" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="154" y="24" class="pill-text">Power BI</text>

      <rect x="272" y="0" width="120" height="36" rx="18" fill="#0f1724" stroke="#111827"/>
      <text x="290" y="24" class="pill-text">Streamlit</text>

      <rect x="408" y="0" width="120" height="36" rx="18" fill="#111827" stroke="#111827"/>
      <text x="426" y="24" class="pill-dark-text">Git</text>
    </g>
  </g>

  <!-- Right column: card with highlights -->
  <g transform="translate(760,40)">
    <rect x="0" y="0" width="360" height="280" rx="14" fill="#ffffff" fill-opacity="0.03" stroke="#1f2937"/>
    <text x="22" y="34" class="title">Arsenal Técnico</text>

    <g transform="translate(22,60)">
      <rect x="0" y="0" width="88" height="30" rx="8" fill="#60a5fa"/>
      <text x="44" y="20" class="pill-text" text-anchor="middle">AWS</text>

      <rect x="98" y="0" width="88" height="30" rx="8" fill="#34d399"/>
      <text x="142" y="20" class="pill-text" text-anchor="middle">GCP</text>

      <rect x="196" y="0" width="88" height="30" rx="8" fill="#f97316"/>
      <text x="240" y="20" class="pill-text" text-anchor="middle">Docker</text>

      <rect x="0" y="46" width="88" height="30" rx="8" fill="#f3f4f6"/>
      <text x="44" y="66" class="pill-text" text-anchor="middle">Python</text>

      <rect x="98" y="46" width="88" height="30" rx="8" fill="#7c3aed"/>
      <text x="142" y="66" class="pill-text" text-anchor="middle">PySpark</text>

      <rect x="196" y="46" width="88" height="30" rx="8" fill="#06b6d4"/>
      <text x="240" y="66" class="pill-text" text-anchor="middle">SQL</text>

      <rect x="0" y="92" width="88" height="30" rx="8" fill="#06b6d4"/>
      <text x="44" y="112" class="pill-text" text-anchor="middle">Power BI</text>

      <rect x="98" y="92" width="88" height="30" rx="8" fill="#ef4444"/>
      <text x="142" y="112" class="pill-text" text-anchor="middle">Streamlit</text>

      <rect x="196" y="92" width="88" height="30" rx="8" fill="#111827"/>
      <text x="240" y="112" class="pill-dark-text" text-anchor="middle">Git</text>
    </g>

    <text x="22" y="240" class="small">Principais projetos: Sales Insight · Pipeline ETL · Decksboard</text>
  </g>

  <!-- accent underline -->
  <rect x="70" y="126" width="520" height="3" rx="2" fill="url(#accent)" opacity="0.95"/>
</svg>
