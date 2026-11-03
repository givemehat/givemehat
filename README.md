<h1 align="center">Rajnish Singh</h1>
<p align="center">
  <b>AI/ML Research Intern, Technology Innovation Hub (TIH), IIT Guwahati</b><br/>
  <b>IBM Quantum Advocate</b> • B.Tech Computer Science & Engineering, Gautam Buddha University
</p>

<p align="center">
  <a href="https://linkedin.com/in/rajnish-singh-a9a61022a"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/givemehat"><img src="https://img.shields.io/badge/GitHub-givemehat-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://pypi.org/project/QTerm/"><img src="https://img.shields.io/badge/PyPI-QTerm-3775A9?style=flat&logo=pypi&logoColor=white" alt="PyPI" /></a>
  <a href="https://medium.com/@rajnishsingh"><img src="https://img.shields.io/badge/Medium-@rajnishsingh-12100E?style=flat&logo=medium&logoColor=white" alt="Medium" /></a>
  <a href="mailto:rajnisihsingh@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## 🔬 Research Focus & Overview

My research focuses on **computational robustness, reliability, and uncertainty-aware modeling** across non-stationary dynamical systems, noisy physical substrates, and quantitative risk environments:

* **Open Quantum Systems & Quantum Machine Learning**: Numerical simulation of non-Markovian dissipation, Lindblad master equations for extreme financial tail-risk, and empirical noise degradation in parameterized quantum circuits (QSVC vs VQC) under hardware-calibrated NISQ noise models.
* **Quantitative Risk & Financial Time-Series**: Institutional realized volatility forecasting (HAR, Sector-HAR, LightGBM, Diebold-Mariano hypothesis testing) and high-throughput sub-millisecond derivatives liquidity screening.
* **Deep Learning & Edge Prognostics**: Dilated causal temporal convolutional networks (TCN) and recurrent architectures for complex degradation modeling (battery SOH/RUL) with low-latency INT8/FP16 edge deployment via ONNX Runtime.
* **Post-Quantum Cryptography & Security Verification**: Algorithmic discovery of cryptographic assets, Mosca's theorem quantum risk assessment, and CycloneDX Cryptographic Bill of Materials (CBOM) generation.

---

## 🏛️ Selected Research & Engineering Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/qdms-quantum-market-simulator">⚛️ QDMS: Quantum Market Risk Simulator</a></h3>
      <p><i>Open Quantum Systems • Extreme Tail-Risk Modeling</i></p>
      <ul>
        <li><b>Formulation:</b> Solves the <b>Lindblad Master Equation</b> via QuTiP to model liquidity collapse and asset dissipation as environmental decoherence.</li>
        <li><b>Performance:</b> Value-at-Risk (VaR 99%) convergence accelerated by <b>3.4×</b> compared to standard pseudo-random Monte Carlo simulations.</li>
        <li><b>Stack:</b> Modular Python physics engine, asynchronous FastAPI backend, and React dashboard for live state-fidelity streaming.</li>
      </ul>
      <p>
        <a href="https://github.com/givemehat/qdms-quantum-market-simulator"><img src="https://img.shields.io/badge/QuTiP-4.7+-blue?style=flat" alt="QuTiP" /></a>
        <a href="https://github.com/givemehat/qdms-quantum-market-simulator"><img src="https://img.shields.io/badge/FastAPI-Production-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" /></a>
        <a href="https://github.com/givemehat/qdms-quantum-market-simulator"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/nifty-volatility-options-engine">⚡ NIFTY Volatility & Options Engine</a></h3>
      <p><i>Quantitative Finance • Realized Volatility Forecasting</i></p>
      <ul>
        <li><b>Econometric Forecasting:</b> HAR, Cluster-HAR, Sector-HAR, and LightGBM over 3+ years of high-frequency 5-minute tick data.</li>
        <li><b>Statistical Validation:</b> Strict out-of-sample ranking evaluated using <b>Diebold-Mariano</b> pairwise statistical tests.</li>
        <li><b>Derivatives Engine:</b> Options short-strangle screener evaluating 50+ strike combinations in &lt;15 ms using DuckDB OLAP.</li>
      </ul>
      <p>
        <a href="https://givemehat.github.io/nifty-volatility-options-engine/"><img src="https://img.shields.io/badge/Live_Dashboard-GitHub_Pages-00e5ff?style=flat&logo=github" alt="Live Demo" /></a>
        <a href="https://github.com/givemehat/nifty-volatility-options-engine"><img src="https://img.shields.io/badge/DuckDB-OLAP-FFF000?style=flat&logo=duckdb&logoColor=black" alt="DuckDB" /></a>
        <a href="https://github.com/givemehat/nifty-volatility-options-engine"><img src="https://img.shields.io/badge/Tests-Passing-brightgreen?style=flat" alt="Tests" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/folk-art-restoration">🎨 Heritage Folk Art Restoration</a></h3>
      <p><i>Computer Vision • Dual-Stage Spectral Deep Learning (npj Heritage Science)</i></p>
      <ul>
        <li><b>Architecture:</b> Combines Fast Fourier Convolution (FFC) inpainting with Enhanced Deep Residual Super-Resolution (EDSR).</li>
        <li><b>Empirical Benchmark:</b> Achieved <b>31.6 dB PSNR</b> and <b>0.923 SSIM</b> on non-stationary cultural artwork degradation patterns.</li>
        <li><b>Corpus:</b> Benchmark corpus of 2,500+ high-resolution samples across 4 distinct physical degradation archetypes.</li>
      </ul>
      <p>
        <a href="https://github.com/givemehat/folk-art-restoration"><img src="https://img.shields.io/badge/Status-Under_Review-orange?style=flat" alt="Under Review" /></a>
        <a href="https://github.com/givemehat/folk-art-restoration"><img src="https://img.shields.io/badge/PyTorch-2.0+-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch" /></a>
        <a href="https://github.com/givemehat/folk-art-restoration"><img src="https://img.shields.io/badge/Reproducibility-Verified-success?style=flat" alt="Reproducibility" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/ONLINETIHIITG">🔋 Battery Fleet Prognostics (SOH / RUL)</a></h3>
      <p><i>Edge AI • Technology Innovation Hub (TIH), IIT Guwahati</i></p>
      <ul>
        <li><b>Deep Learning Zoo:</b> Dilated Causal TCN, 2-layer LSTM, and GRU trained on NASA PCoE battery aging datasets.</li>
        <li><b>Edge Optimization:</b> Achieved <b>0.38 ms inference latency</b> and a <b>214 kB footprint</b> via ONNX FP16 quantization.</li>
        <li><b>Zero-Leakage Protocol:</b> Strict 16 Train / 9 Validation / 9 Holdout cell partition yielding State of Health <b>R² = +0.924</b>.</li>
      </ul>
      <p>
        <a href="https://github.com/givemehat/ONLINETIHIITG"><img src="https://img.shields.io/badge/Affiliation-TIH_IIT_Guwahati-blue?style=flat" alt="IIT Guwahati" /></a>
        <a href="https://github.com/givemehat/ONLINETIHIITG"><img src="https://img.shields.io/badge/ONNX_Runtime-Edge-005CED?style=flat&logo=onnx&logoColor=white" alt="ONNX" /></a>
        <a href="https://github.com/givemehat/ONLINETIHIITG"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/INDRAMESH">🛡️ INDRAMESH: Cryptographic Discovery & Risk</a></h3>
      <p><i>Post-Quantum Cryptography • Smart India Hackathon Rank 1 / 80</i></p>
      <ul>
        <li><b>Discovery Engine:</b> Static and dynamic binary scanner identifying legacy cryptographic algorithms and key strengths.</li>
        <li><b>Mosca's Theorem:</b> Computes time-to-quantum risk thresholds ($D + S > T$) against migration urgency.</li>
        <li><b>Compliance:</b> Generates automated CycloneDX-compliant Cryptographic Bill of Materials (CBOM).</li>
      </ul>
      <p>
        <a href="https://github.com/givemehat/INDRAMESH"><img src="https://img.shields.io/badge/SIH-Rank_1-gold?style=flat" alt="SIH Rank 1" /></a>
        <a href="https://github.com/givemehat/INDRAMESH"><img src="https://img.shields.io/badge/PQC-NIST_FIPS_203/204-blue?style=flat" alt="PQC" /></a>
        <a href="https://github.com/givemehat/INDRAMESH"><img src="https://img.shields.io/badge/PyTest-Passing-brightgreen?style=flat" alt="PyTest" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/givemehat/Noise_Resilience_Quantum_Classifiers">⚛️ Quantum Classifier Noise Resilience</a></h3>
      <p><i>Quantum Machine Learning • NISQ Noise Benchmarking</i></p>
      <ul>
        <li><b>Empirical Study:</b> Compares Quantum Support Vector Classifiers (QSVC) vs Variational Quantum Classifiers (VQC).</li>
        <li><b>Noise Channels:</b> Evaluates performance under depolarizing noise, thermal relaxation, and readout errors.</li>
        <li><b>Primitives:</b> Executed using Qiskit 1.x Estimator/Sampler architectures with calibrated backend noise models.</li>
      </ul>
      <p>
        <a href="https://github.com/givemehat/Noise_Resilience_Quantum_Classifiers"><img src="https://img.shields.io/badge/Qiskit-1.x-6929C4?style=flat&logo=ibm&logoColor=white" alt="Qiskit" /></a>
        <a href="https://github.com/givemehat/Noise_Resilience_Quantum_Classifiers"><img src="https://img.shields.io/badge/Research-QAMP_2026-purple?style=flat" alt="QAMP" /></a>
      </p>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Stack & Tooling

* **Scientific Computing & ML:** Python, C++, PyTorch, Scikit-learn, LightGBM, NumPy, Pandas, SciPy, QuTiP, OpenCV.
* **Quantum Development:** Qiskit (1.x/2.x Primitives), Aer Noise Simulators, Parameterized Feature Maps (ZZFeatureMap, PauliFeatureMap), QTerm.
* **Quantitative Finance & Data:** DuckDB, FastAPI, Financial Time-Series Modeling (HAR, GARCH), Monte Carlo, Options Pricing (Black-Scholes).
* **Engineering & Deployment:** Docker, Git/GitHub, ONNX Runtime, Linux/Bash, Streamlit, PyTest.

---

## 📝 Recent Research Articles & Publications

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

---

## 📺 Technical Walkthroughs & Lectures

<!-- YOUTUBE-LIST:START -->
<!-- YOUTUBE-LIST:END -->

---

<p align="center">
  <sub>Open to research collaborations, visiting researcher roles, and quantitative engineering opportunities.</sub>
</p>
