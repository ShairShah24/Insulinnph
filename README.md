<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Insulin NPH - Comprehensive Guide</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; background: #f0f4f8; color: #333; }
    header { background: linear-gradient(to right, #1a73e8, #34a853); color: white; padding: 2rem; text-align: center; }
    h1 { margin: 0; }
    .container { padding: 2rem; max-width: 1200px; margin: auto; }
    .card { background: white; padding: 1.5rem; margin-bottom: 2rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
    h2 { color: #1a73e8; }
    h3 { color: #34a853; margin-top: 1.5rem; }
    ul, ol { margin-left: 1.5rem; }
    .nav-btn { margin: 0.3rem; padding: 0.5rem 1rem; border: 2px solid #1a73e8; background: white; color: #1a73e8; border-radius: 30px; cursor: pointer; }
    .nav-btn:hover { background: #1a73e8; color: white; }
    .section-nav { text-align: center; margin-bottom: 2rem; }
    img { max-width: 100%; height: auto; border-radius: 8px; }
    .info-grid { display: flex; gap: 1rem; flex-wrap: wrap; }
    .info-box { flex: 1 1 250px; background: #f8f9fa; padding: 1rem; border-left: 4px solid #1a73e8; border-radius: 8px; }
    .warning { background: #fff3cd; padding: 1rem; border-left: 4px solid #ffc107; margin-top: 1rem; border-radius: 8px; }
  </style>
  <script>
    function scrollToSection(id) {
      document.getElementById(id)?.scrollIntoView({ behavior: "smooth" });
    }
  </script>
</head>
<body>
  <header>
    <h1>Insulin NPH (Neutral Protamine Hagedorn)</h1>
    <p>A professional pharmacology reference</p>
  </header>

  <div class="container">
    <div class="section-nav">
      <button class="nav-btn" onclick="scrollToSection('generic')">Generic Info</button>
      <button class="nav-btn" onclick="scrollToSection('mechanism')">Mechanism</button>
      <button class="nav-btn" onclick="scrollToSection('pharmacokinetics')">Pharmacokinetics</button>
      <button class="nav-btn" onclick="scrollToSection('indications')">Indications</button>
      <button class="nav-btn" onclick="scrollToSection('side-effects')">Side Effects</button>
      <button class="nav-btn" onclick="scrollToSection('storage')">Storage</button>
      <button class="nav-btn" onclick="scrollToSection('pakistan')">Pakistan Data</button>
      <button class="nav-btn" onclick="scrollToSection('time-curve')">Time-Action Curve</button>
    </div>

    <div class="card" id="generic">
      <h2>Generic Information</h2>
      <div class="info-grid">
        <div class="info-box"><strong>Generic Name:</strong> Insulin NPH (Isophane insulin)</div>
        <div class="info-box"><strong>Class:</strong> Intermediate-acting insulin</div>
        <div class="info-box"><strong>Duration:</strong> 14–24 hours</div>
        <div class="info-box"><strong>Brands:</strong> Humulin N, Novolin N, Insulatard</div>
      </div>

      <h3>Brand Images</h3>
      <div style="display: flex; gap: 2rem; flex-wrap: wrap;">
        <div><img src="images/OIP.webp" alt="Humulin R"/><p>Humulin R</p></div>
        <div><img src="images/OIP (1).webp" alt="Novolin N"/><p>Novolin N</p></div>
      </div>
    </div>

    <div class="card" id="mechanism">
      <h2>Mechanism of Action</h2>
      <p>Insulin NPH facilitates glucose uptake by stimulating GLUT4 translocation. It inhibits gluconeogenesis and promotes glycogen storage.</p>
    </div>

    <div class="card" id="pharmacokinetics">
      <h2>Pharmacokinetics</h2>
      <ul>
        <li><strong>Onset:</strong> 1–3 hours</li>
        <li><strong>Peak:</strong> 4–8 hours</li>
        <li><strong>Duration:</strong> 14–24 hours</li>
        <li><strong>Excretion:</strong> Renal</li>
      </ul>
    </div>

    <div class="card" id="indications">
      <h2>Indications and Dosing</h2>
      <ul>
        <li>Type 1 diabetes (basal use)</li>
        <li>Type 2 diabetes (with/without oral agents)</li>
        <li>Gestational diabetes</li>
      </ul>
      <p><strong>Adults:</strong> 0.4–1.0 units/kg/day, usually split into two doses.</p>
    </div>

    <div class="card" id="side-effects">
      <h2>Side Effects & Contraindications</h2>
      <h3>Common Effects</h3>
      <ul>
        <li>Hypoglycemia</li>
        <li>Weight gain</li>
        <li>Lipodystrophy</li>
      </ul>
      <h3>Rare/Serious</h3>
      <ul>
        <li>Allergic reactions</li>
        <li>Insulin edema</li>
      </ul>
      <h3>Contraindications</h3>
      <ul>
        <li>Hypersensitivity to protamine/insulin</li>
        <li>Current hypoglycemic episode</li>
      </ul>
    </div>

    <div class="card" id="storage">
      <h2>Storage Guidelines</h2>
      <div class="info-grid">
        <div class="info-box"><strong>Unopened:</strong> 2–8°C (do not freeze)</div>
        <div class="info-box"><strong>In use:</strong> Store at room temperature (≤30°C) for up to 28 days</div>
      </div>
    </div>

    <div class="card" id="pakistan">
      <h2>Pakistan Formulations & Market</h2>
      <ul>
        <li><strong>Availability:</strong> Humulin N, Novolin N widely available</li>
        <li><strong>Affordability:</strong> Human insulin ~1.4 days' wages/month</li>
        <li><strong>Challenge:</strong> Rural access, biosimilar approval ongoing</li>
      </ul>
    </div>

    <div class="card" id="time-curve">
      <h2>Time-Action Curve</h2>
      <p>This graph shows the action profile of insulin NPH versus other insulins:</p>
      <img src="images/time_action_curve.jpg" alt="Time-Action Curve"/>
    </div>
  </div>

  <footer style="text-align:center; padding:1rem; font-size:0.9rem; background:#1a1a1a; color:#ccc;">
    Designed for educational use. Consult a physician for treatment decisions.
  </footer>
</body>
</html>
