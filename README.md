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
      </ul>

  <a class="download" href="[Research_Statement_Quantum_Controls.pdf](https://drive.google.com/drive/folders/1HWzTBOAm0izYfR77ygBVA21r0c2ypE6F?usp=sharing)" download>Download PDF</a>
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


  </div>
</body>
</html>
