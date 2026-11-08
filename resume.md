---
layout: page
title: "Resume"
permalink: /resume/
---

<!-- =====================================================
     RESUME PAGE (A4, printable, up to 2 sheets)
     HOW TO EDIT:
       - Only change the text. Keep the class names as they are.
       - Lines marked EDIT are the ones to replace with real data.
     HOW TO MAKE A PDF:
       - Click the Print button, choose Save as PDF, paper A4,
         margins None, and tick Background graphics.
     ===================================================== -->

<div class="resume-wrap">

  <!-- Print button. Hidden automatically when printing (class no-print) -->
  <div class="resume-toolbar no-print">
    <button class="btn primary" onclick="window.print()">⬇ Print / Save as PDF (A4)</button>
    <!-- <span class="muted">Print settings: A4, margins None, Background graphics ON.</span> -->
  </div>


  <!-- =====================================================
       PAGE 1  (always on)
       Layout: LEFT = dark blue sidebar, RIGHT = main content
       ===================================================== -->
  <article class="cv">

    <!-- ========== LEFT COLUMN: DARK BLUE SIDEBAR ========== -->
    <aside class="cv-side">

      <!-- Profile photo: file must be at assets/images/Dp.png -->
      <img class="cv-photo" src="{{ '/assets/images/Dp.png' | relative_url }}" alt="Profile photo">

      <!-- EDIT: full name and job title -->
      <h1>Hettige Don Gayan Viduranga</h1>
      <div class="cv-role">Business Analyst &amp; Power BI Developer</div>

      <!-- Personal information. EDIT each line. Delete a line to remove it. -->
      <h3>Personal Info</h3>
      <ul class="plain">
        <li>📍 Homagama, Sri Lanka</li>
        <li>📞 +94 7714706367</li>
        <li>✉️ hdgviduranga@gmail.com</li>
        <li>🔗 linkedin.com/in/gayan-viduranga</li>
        <li>🐙 github.com/GayanViduranga</li>
        <li>🎂 DOB: 1993</li>
      </ul>

      <!-- Languages. EDIT language and level -->
      <h3>Languages</h3>
      <ul class="plain">
        <li>English – Professional</li>
        <li>Sinhala – Native</li>
        
      </ul>

      <!-- Tools: each span is one rounded tag. Copy a span to add more -->
      <h3>Tools</h3>
      <div class="chips">
        <span>Power BI</span><span>Excel</span><span>SQL</span><span>Microsoft Fabric</span>
        <span>BigQuery</span><span>Python</span><span>Git</span>
      </div>

      <!-- Techniques and skills: same pattern as Tools -->
      <h3>Techniques &amp; Skills</h3>
      <div class="chips">
        <span>DAX</span><span>Data Modeling</span><span>ETL</span><span>Data Analysis</span>
        <span>RLS</span><span>Automation</span><span>Prompt Engineering</span><span>MCP</span>
      </div>

    </aside>

    <!-- ========== RIGHT COLUMN: MAIN CONTENT ========== -->
    <main class="cv-main">

      <!-- About me summary. EDIT: 3 to 4 lines is ideal -->
      <section class="cv-block">
        <h2>About Me</h2>
        <p>Business Analyst and Power BI Developer with a corporate finance foundation. I design DAX-optimized data models and automated reporting that give finance and operations teams trusted numbers without manual work. (Dummy text)</p>
      </section>

      <!-- Experience. To add a job, copy one whole job block.
           Put the newest job first. -->
      <section class="cv-block">
        <h2>Experience</h2>

        <!-- JOB 1 (newest) -->
        <div class="job">
          <div class="job-head">
            <strong>Senior Business Analyst</strong>
            <span class="date">2023 – Present</span>
          </div>
          <div class="company">Company Name (Pvt) Ltd, Colombo</div>
          <ul>
            <li>Built enterprise Power BI dashboards used by 20+ managers.</li>
            <li>Reduced monthly reporting time by 70% through automated pipelines.</li>
            <li>Designed star-schema models and Row-Level Security.</li>
          </ul>
        </div>

        <!-- JOB 2 -->
        <div class="job">
          <div class="job-head">
            <strong>Business Analyst</strong>
            <span class="date">2021 – 2023</span>
          </div>
          <div class="company">Company Name (Pvt) Ltd, Colombo</div>
          <ul>
            <li>Produced management accounts and ratio analysis for senior leadership.</li>
            <li>Automated Excel and SQL reports with scheduled email delivery.</li>
          </ul>
        </div>

        <!-- JOB 3 -->
        <div class="job">
          <div class="job-head">
            <strong>Finance Executive</strong>
            <span class="date">2018 – 2021</span>
          </div>
          <div class="company">Company Name (Pvt) Ltd, Colombo</div>
          <ul>
            <li>Prepared cost-of-sales analysis and monthly financial statements.</li>
            <li>Supported budgeting and variance reporting.</li>
          </ul>
        </div>
      </section>

      <!-- Education. EDIT degrees, years, universities -->
      <section class="cv-block">
        <h2>Education</h2>
        <div class="job">
          <div class="job-head"><strong>MSc in Business Analytics</strong><span class="date">20XX</span></div>
          <div class="company">Robert Gordon University</div>
        </div>
        <div class="job">
          <div class="job-head"><strong>BSc in Business Administration (Special)</strong><span class="date">20XX</span></div>
          <div class="company">University of Sri Jayewardenepura</div>
        </div>
      </section>

      <!-- References. Two side by side. EDIT names and contacts -->
      <section class="cv-block">
        <h2>References</h2>
        <div class="refs">
          <div>
            <strong>Reference Name 1</strong><br>
            Head of Finance, Company A<br>
            ref1@example.com · +94 77 000 0000
          </div>
          <div>
            <strong>Reference Name 2</strong><br>
            IT Manager, Company B<br>
            ref2@example.com · +94 71 000 0000
          </div>
        </div>
      </section>

    </main>
  </article>


  <!-- =====================================================
       PAGE 2  (currently switched OFF)
       TO TURN ON: delete the opening comment marker on the
       line right after this note, and the closing comment marker
       on the last line of this block.
       Page 2 is a separate A4 sheet, so you decide exactly what
       goes on it. Nothing splits automatically.
       Do not put other comments inside this block while it is off,
       because comments cannot be nested.
       ===================================================== -->

  <!--
  <article class="cv">

    <aside class="cv-side">
      <h3>Certifications</h3>
      <ul class="plain">
        <li>Microsoft PL-300 (Power BI)</li>
        <li>Microsoft DP-600 (Fabric)</li>
        <li>CA Sri Lanka – Strategic Level</li>
      </ul>

      <h3>Awards</h3>
      <ul class="plain">
        <li>Employee of the Year, 20XX</li>
        <li>Best Automation Project, 20XX</li>
      </ul>

      <h3>Interests</h3>
      <div class="chips">
        <span>Energy projects</span><span>DIY</span><span>Writing</span>
      </div>
    </aside>

    <main class="cv-main">

      <section class="cv-block">
        <h2>Key Projects</h2>

        <div class="job">
          <div class="job-head">
            <strong>Finance Reporting Automation</strong>
            <span class="date">2024</span>
          </div>
          <div class="company">Power BI · Python · SQL</div>
          <ul>
            <li>Automated monthly management reports with email delivery.</li>
            <li>Cut preparation time from 3 days to 3 hours.</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-head">
            <strong>Fabric Lakehouse Migration</strong>
            <span class="date">2025</span>
          </div>
          <div class="company">Microsoft Fabric · Direct Lake</div>
          <ul>
            <li>Moved legacy Excel models into a governed semantic model.</li>
            <li>Introduced Row-Level Security for 5 departments.</li>
          </ul>
        </div>
      </section>

      <section class="cv-block">
        <h2>Publications &amp; Writing</h2>
        <p>Medium articles on Power BI, DAX and AI automation: medium.com/@hdgviduranga</p>
      </section>

    </main>
  </article>
  -->

</div>