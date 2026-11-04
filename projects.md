---
layout: page
title: "Projects & Demos"
permalink: /projects/
---

This portfolio showcases production-grade analytics dashboards, interactive visual components, and data solutions.

## Enterprise Operational Analytics (Power BI)

Below is a responsive container embedding an interactive Power BI report.

<div class="embed-container">
  <iframe title="Operational Reporting Dashboard" src="https://app.powerbi.com/view?r=YOUR_SAMPLE_REPORT_EMBED_URL" allowFullScreen="true"></iframe>
</div>

---

## Interactive Client-Side Simulation

 lightweight client-side calculation utility:

<div id="calc-widget" style="padding: 20px; background: #ffffff; border: 1px solid #eaeaea; border-radius: 8px; margin: 20px 0;">
  <h4>Quick LKR Financial Formatter</h4>
  <p>Convert raw financial inputs into clean millions notation:</p>
  <input type="number" id="rawInput" placeholder="Enter amount in LKR (e.g. 15000000)" style="padding: 8px; width: 100%; max-width: 300px; margin-bottom: 10px;" />
  <div id="outputResult" style="font-weight: 600; color: #0366d6;"></div>
</div>

<script>
  document.getElementById('rawInput').addEventListener('input', function(e) {
    const val = parseFloat(e.target.value);
    if (!isNaN(val)) {
      const inMillions = (val / 1000000).toFixed(2);
      document.getElementById('outputResult').innerText = "Formatted: LKR " + inMillions + " M";
    } else {
      document.getElementById('outputResult').innerText = "";
    }
  });
</script>