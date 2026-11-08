---
layout: page
title: "Portfolio"
permalink: /projects/
---

<div class="container">

<section>
  <h2 class="section">Portfolio</h2>
  <p class="muted">Production-grade analytics dashboards, interactive visual components, and data solutions.</p>
</section>

<section>
  <h2 class="section">Enterprise Operational Analytics</h2>
  <div class="card">
    <div class="tags"><span>Power BI</span><span>DAX</span><span>Star Schema</span></div>
    <p class="muted">An interactive Power BI report embedded below. Use the full-screen option for a closer look.</p>
    <div class="embed-container">
      <iframe title="Operational Reporting Dashboard"
              src="https://app.powerbi.com/view?r=YOUR_SAMPLE_REPORT_EMBED_URL"
              allowFullScreen="true"></iframe>
    </div>
  </div>
</section>

<section>
  <h2 class="section">Interactive Tools</h2>
  <div class="grid">
    <div class="card">
      <h3>💰 LKR Financial Formatter</h3>
      <p class="muted">Convert raw amounts into clean millions notation.</p>
      <input type="number" id="rawInput" class="input" placeholder="e.g. 15000000">
      <div id="outputResult" class="result"></div>
    </div>
  </div>
</section>

</div>

<script>
  document.getElementById('rawInput').addEventListener('input', function (e) {
    var val = parseFloat(e.target.value);
    var out = document.getElementById('outputResult');
    out.innerText = isNaN(val) ? "" : "LKR " + (val / 1000000).toFixed(2) + " M";
  });
</script>