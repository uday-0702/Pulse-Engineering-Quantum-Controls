<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Research Statement — Quantum Controls — Uday Mathur</title>
  <meta name="description" content="Research statement on pulse-level control and leakage suppression for superconducting transmon qubits (FAST DRAG, HD DRAG, DRAG variants)." />
  <style>
    :root{
      --bg:#f7f5f0;
      --card:#ffffff;
      --accent:#b8860b;
      --text:#1b1b1b;
      --muted:#555;
      font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    }
    body{background:linear-gradient(180deg,var(--bg),#fbfbfb);color:var(--text);margin:0;padding:24px;}
    .container{max-width:900px;margin:24px auto;padding:28px;background:var(--card);box-shadow:0 6px 20px rgba(0,0,0,0.06);border-radius:10px;}
    h1{margin:0 0 6px;font-size:26px;}
    .meta{color:var(--muted);margin-bottom:18px;font-size:14px;}
    section{margin-top:18px;}
    h2{color:var(--accent);font-size:18px;margin-bottom:8px;}
    p{line-height:1.55;margin:8px 0;color:#222;}
    ul{margin:8px 0 8px 20px;color:#222;}
    pre{background:#f3f3f3;padding:12px;border-radius:6px;overflow:auto;}
    .badge{display:inline-block;padding:6px 10px;background:rgba(184,134,11,0.12);color:var(--accent);border-radius:999px;font-weight:600;margin-right:8px;font-size:13px;}
    .download{display:inline-block;margin-top:10px;padding:10px 14px;background:var(--accent);color:white;border-radius:8px;text-decoration:none;font-weight:600;}
    .footer{margin-top:22px;color:var(--muted);font-size:13px;border-top:1px solid #eee;padding-top:12px;}
    .collab-list{list-style:none;padding:0;margin:0}
    .collab-list li{margin:6px 0}
  </style>
</head>
<body>
  <div class="container" role="main">
    <header>
      <h1>Research Statement — Quantum Controls</h1>
      <div class="meta">Uday Mathur — Department of Physics, IIT (BHU), Varanasi</div>
      <div>
        <span class="badge">Quantum Control</span>
        <span class="badge">Superconducting Qubits</span>
        <span class="badge">Pulse Engineering</span>
      </div>
    </header>

  <section id="overview">
      <h2>Overview</h2>
      <p>
        This research statement summarizes work on pulse-level control for superconducting transmon qubits, focusing on techniques to suppress leakage from the computational subspace and improve single-qubit gate fidelity. The study compares classical and modern pulse-shaping approaches and highlights practical recommendations for experimental calibration and hardware-level implementation.
      </p>
    </section>

  <section id="what-we-did">
      <h2>What we did</h2>
      <ul>
        <li>Performed a comparative analysis of pulse schemes used for single-qubit control in transmon devices.</li>
        <li>Evaluated Gaussian pulses and DRAG-based corrections, including higher-order DRAG variants.</li>
        <li>Developed and tested two advanced spectral-control variants: FAST DRAG (Fourier Ansatz Spectrum Tuning) and HD DRAG (Higher-Derivative DRAG).</li>
        <li>Quantified performance using average gate fidelity and leakage metrics, and studied phase-error behavior and correction strategies.</li>
        <li>Explored a pulse-design concept for operating on intermediate multi-qubit states by sequential suppression of primary and secondary anharmonic spectral components.</li>
      </ul>
    </section>

  <section id="results">
      <h2>Key results</h2>
      <ul>
        <li><strong>High-fidelity operation:</strong> DRAG-L and 5th-order DRAG variants reached ~99% single-qubit gate fidelity at ≈ 7 ns in our study (with calibration).</li>
        <li><strong>Spectral suppression:</strong> FAST DRAG offered the strongest and widest suppression of spectral energy at the qubit anharmonicity, providing the most flexibility for hardware calibration.</li>
        <li><strong>Leakage control:</strong> HD DRAG enabled multi-transition leakage suppression with fewer calibration parameters, though with less direct bandwidth control than FAST DRAG.</li>
        <li><strong>Phase mitigation:</strong> Virtual-Z gates (software corrections) and time-dependent detuning were effective at reducing residual phase accumulation introduced by pulses.</li>
        <li><strong>Design outlook:</strong> A sequential spectral-suppression approach (primary then secondary anharmonicity) shows promise for selective control of intermediate multi-qubit states.</li>
      </ul>
    </section>

  <section id="collaborations">
      <h2>Collaborations</h2>
      <p>This work was conducted during a summer internship at the Bhabha Atomic Research Centre (BARC) and closely supervised by:</p>
      <ul class="collab-list">
        <li><strong>Dr. Prashant Shukla</strong> — Scientific Officer, Nuclear Physics Division (NPD), BARC Mumbai</li>
        <li><strong>Sanndeep Joshi</strong> — Nuclear Physics Division (NPD), BARC Mumbai</li>
      </ul>
      <p>The research builds on and extends ideas from recent literature (notably Hyyppä et al., PRX Quantum 2024 and Motzoi et al. 2009).</p>
    </section>

  <section id="files">
      <h2>Files included</h2>
      <ul>
        <li><code>Research_Statement_Quantum_Controls.pdf</code> — Full research statement PDF (methods, discussion, figures).</li>
        <li>LaTeX source — available on request for reproducibility and journal submissions.</li>
      </ul>

  <a class="download" href="Research_Statement_Quantum_Controls.pdf" download>Download PDF</a>
      <p style="margin-top:8px;color:var(--muted);font-size:13px">If hosting on GitHub, place the PDF at the repository root or inside a `docs/` folder and update the link above accordingly.</p>
    </section>

  <section id="how-to-get-it">
      <h2>How to obtain the files</h2>
      <p>Two common ways to share or download:</p>
      <ol>
        <li><strong>Direct download</strong>: Click the <em>Download PDF</em> button above if the file is hosted in the same repository or website folder.</li>
        <li><strong>Clone the repository (example)</strong>:
          <pre>git clone &lt;repository-link&gt;
cd &lt;repository-folder&gt;
# PDF will be at the repo root or docs/ folder</pre>
        </li>
      </ol>
      <p>If you want, I can prepare a small ZIP that includes the PDF and the LaTeX source and provide instructions for hosting it on GitHub Pages or an institutional webpage.</p>
    </section>

  <section id="citation-license">
      <h2>Citation & license</h2>
      <p>
        If you refer to this work, please cite as:
      </p>
      <pre>Uday Mathur, Research Statement — Quantum Controls: Analysis of Leakage Suppression in Transmon Qubits, IIT (BHU), 2025.</pre>
      <p class="footer">License: For academic and research use. Redistribution or modification should credit the author and affiliated institution.</p>
    </section>

  </div>
</body>
</html>
