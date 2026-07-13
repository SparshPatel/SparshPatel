# Sparsh Patel | Computational Finance & Systems Engineering

*Empirical Asset Pricing • Portfolio Construction Under Model Uncertainty • High-Throughput Systems*

Academic researcher and systems engineer working at the intersection of quantitative asset management and computational finance. My work focuses on building robust mathematical frameworks—spanning stochastic calculus, convex optimization, and reinforcement learning—and backing them with high-performance production code.

### Engineering Impact & Core Metrics

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=SparshPatel&show_icons=true&theme=tokyonight&count_private=true" alt="Sparsh's GitHub Stats" height="180px" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SparshPatel&layout=compact&theme=tokyonight&langs_count=6" alt="Top Languages" height="180px" />
</p>

# 🕹️ STOP SKIMMING. CLICK THE BOXES BELOW.

### Interactive Engineering Stack

<details>
  <summary>🟥 Stochastic Calculus</summary>
  <blockquote>
    <b>Definition:</b> A branch of mathematics that operates on stochastic processes (like Brownian motion) to model systems with random, time-dependent behavior. It allows for the integration and differentiation of chaotic financial asset paths where traditional calculus fails.
  </blockquote>
</details>

<details>
  <summary>🟨 Portfolio & Convex Optimization</summary>
  <blockquote>
    <b>Definition:</b> A mathematical subfield of optimization that studies the problem of minimizing convex functions over convex sets. In finance, it guarantees finding the single globally optimal asset allocation weights (e.g., maximizing Sharpe ratio) under tracking-error, leverage, or regulatory constraints.
  </blockquote>
</details>

<details>
  <summary>🟩 Time Series Analysis</summary>
  <blockquote>
    <b>Definition:</b> A statistical methodology used to analyze a sequence of data points collected over time intervals. It isolates internal structures such as trends, seasonal variations, and cointegration properties to construct predictive models for highly non-stationary financial data streams.
  </blockquote>
</details>

<details>
  <summary>🟦 Reinforcement Learning</summary>
  <blockquote>
    <b>Definition:</b> An area of machine learning concerned with how intelligent agents take sequential actions within an environment to maximize a cumulative reward function. It resolves multi-period decision problems through exploratory trial-and-error without needing a static analytical environment.
  </blockquote>
</details>

<details>
  <summary>🟪 Nonlinear Physics & Stochastic Resonance</summary>
  <blockquote>
    <b>Definition:</b> The study of complex systems where outputs are non-proportional to inputs. It includes phenomena where a system utilizes ambient background noise to amplify weak structural signals, making hidden phase transitions or regime shifts visible.
  </blockquote>
</details>

<details>
  <summary>🟫 Bayesian Optimization</summary>
  <blockquote>
    <b>Definition:</b> A sequential design strategy for global optimization of expensive black-box functions. It uses a probabilistic surrogate model (like Gaussian Processes) to guide search parameters efficiently by evaluating choices based on exploration and exploitation metrics.
  </blockquote>
</details>

<details>
  <summary>🟧 Python & Vectorization</summary>
  <blockquote>
    <b>Definition:</b> A high-level programming paradigm that replaces explicit loop operations with heavily optimized, compiled array-level instructions. It eliminates interpreter overhead to run lightning-fast data transformations on multi-dimensional matrices.
  </blockquote>
</details>

<details>
  <summary>⬛ Differentiable Optimization</summary>
  <blockquote>
    <b>Definition:</b> An engineering architecture that treats mathematical optimization problems as standard, backpropagation-friendly neural network layers. It permits the calculation of analytical gradients directly through implicit optimization surfaces for end-to-end learning systems.
  </blockquote>
</details>

---

### Deep-Dive Research & Interactive Projects

<details>
  <summary>📁 Working Paper: Volatility Targeting, Variance Drain, and the Financialization Effect</summary>
  <blockquote>
    <b>Skills Used:</b> Stochastic Calculus, Econometrics, Heston-Merton Framework, Python, CRSP Data Analytics<br><br>
    <b>What I Did:</b> Derived a formal closed-form Sharpe ratio improvement from a integrated Heston-Merton setup, directly linking volatility targeting implementations to Merton-optimal rules. Validated the math on a 100-year CRSP dataset tracking 21 assets across 14 international markets. Authored the VDOV rule, pushing out-of-sample Sharpe to 1.01 against the Moreira-Muir benchmark.
  </blockquote>
</details>

<details>
  <summary>📁 Working Paper: Delta-Guided Soft Actor-Critic for Derivative Hedging</summary>
  <blockquote>
    <b>Skills Used:</b> Reinforcement Learning, Derivatives, Stochastic Processes, PyTorch, Gym/Stable-Baselines<br><br>
    <b>What I Did:</b> Designed an original reward-shaping framework injecting Black-Scholes delta parameters as a time-decaying inductive bias into an SAC model, completing a full mathematical proof of asymptotic optimality. Tested across GBM, Merton jump-diffusion, and rough Bergomi environments to drop hedging error by 19% to 38% while accelerating convergence speed by 2x.
  </blockquote>
</details>

<details>
  <summary>📁 Working Paper: Bayesian Optimisation of Cointegration-Based Stat Arb</summary>
  <blockquote>
    <b>Skills Used:</b> Bayesian Optimization, Kalman Filters, Time Series, Johansen VECM, Gaussian Processes<br><br>
    <b>What I Did:</b> Built a multi-universe statistical arbitrage processing system utilizing Johansen VECM and adaptive Kalman hedge ratios. Configured a GP-BO pipeline (Matérn 5/2 kernel) to automatically tune 5 core strategy hyperparameters simultaneously, netting out-of-sample Sharpe metrics averaging 5.78 across 5 ETF test groups.
  </blockquote>
</details>

<details>
  <summary>📁 Working Paper: Adaptive Coupled Stochastic Resonance for Vol Regime Detection</summary>
  <blockquote>
    <b>Skills Used:</b> Nonlinear Physics, Econometrics, Langevin Dynamics, Transfer Entropy, Walk-Forward Testing<br><br>
    <b>What I Did:</b> Designed coupled Langevin bistable detector arrays utilizing adaptive Kramers-rate barriers combined with transfer entropy coupling logic to catch microsecond shifts in VIX volatility regimes. Proved structural validity against 10 baseline methods across 200 phase-randomized surrogate tracking matrices.
  </blockquote>
</details>

<details>
  <summary>📁 Publication: Factor Exposure and Correlation Decomposition</summary>
  <blockquote>
    <b>Skills Used:</b> Portfolio Diversification, Factor Analysis, Risk Management, SSRN Frameworks<br><br>
    <b>What I Did:</b> Created an integrated multi-method diagnostic framework to uncover hidden risk concentration patterns inside multi-asset portfolios. Modeled correlation spikes over 20 years of data across 25 asset vectors, yielding a tactical strategy that reduced maximum drawdown profiles by close to half.
  </blockquote>
</details>

<details>
  <summary>📁 Project: Robust Portfolio Optimization via Smart Predict-then-Optimize</summary>
  <blockquote>
    <b>Skills Used:</b> Differentiable Optimization, Deep Learning, KKT Conditions, cvxpy, Robust Allocation<br><br>
    <b>What I Did:</b> Implemented a true end-to-end differentiable portfolio construction architecture by inserting a custom convex optimization layer directly inside a neural network using KKT implicit differentiation. Outperformed classic two-stage baselines across Sharpe, Sortino, and CVaR boundaries during high-stress market states.
  </blockquote>
</details>

<details>
  <summary>📁 Project: DepreciNet — Multi-Modal Deep Learning for Real Estate Pricing</summary>
  <blockquote>
    <b>Skills Used:</b> PyTorch, Cross-Attention Architectures, Neural Radiance Fields (NeRF), Spatial Encoding<br><br>
    <b>What I Did:</b> Engineered a 5-branch cross-attention deep learning model mapping physical asset conditions, location, structural features, and macro trends. Implemented custom learnable exponential depreciation functions combined with NeRF-style spatial encodings for interpretable real estate valuation.
  </blockquote>
</details>

<details>
  <summary>📁 Project: Kappa Quant</summary>
  <blockquote>
    <b>Skills Used:</b> Convex Optimization, Options Pricing, Black-Scholes, Plotly, Interactive Tools<br><br>
    <b>What I Did:</b> Released two standalone computational math tools: a high-velocity CVaR portfolio optimizer running a Rockafellar-Uryasev LP engine via cvxpy, and an implied volatility surface constructor utilizing Brent's inversion method on live multi-strike option data streams.
  </blockquote>
</details>

<details>
  <summary>📁 Project: Cross-Asset Time Series Momentum Strategy</summary>
  <blockquote>
    <b>Skills Used:</b> Factor Research, Portfolio Construction, Time Series Momentum, Permutation Tests<br><br>
    <b>What I Did:</b> Extended multi-horizon lookback momentum structures across 17 global asset types. Implemented strict volatility-targeted asset sizing, anti-overfitting rules, and permutation-based statistical checks to confirm model robustness.
  </blockquote>
</details>

<details>
  <summary>📁 Biomedical & Vision Frameworks</summary>
  <blockquote>
    <ul>
      <li><b>Retinal Vessel Segmentation:</b> Designed a hybrid U-Net framework with latent-space clustering, securing 94.55% accuracy scores on international datasets (DRIVE, STARE).</li>
      <li><b>Ovarian Cancer Detection:</b> Developed an attention-guided Multiple Instance Learning network identifying tissue structures on high-res histopathology patches.</li>
      <li><b>Residual Inconsistency Network:</b> Constructed a dual-stream CNN + Transformer system parsing raw RGB and SRM noise arrays to locate boundaries in manipulated deepfake files.</li>
      <li><b>Functional Connectomes Graph Learning:</b> Modeled 4D fMRI brain scans as high-dimensional geometric graphs utilizing NeuroGraph vectors to run large-scale cohort clustering.</li>
    </ul>
  </blockquote>
</details>

---

### Industry Experience

#### D+A Strategies
*Alpha Researcher • Quantitative Trainee* | Jul 2026 - Present
* Specializing in portfolio construction, alpha generation strategies, and advanced quantitative asset management architectures under uncertain market regimes.

#### Volvo Group
*Business Analyst & Full Stack Developer (Gen AI Intern)* | Jan 2026 - Jul 2026
* **Enterprise Cloud Architecture:** Designed and deployed an enterprise-scale, role-based access management system over Azure cloud layers, centralizing proprietary agentic AI tools with real-time low-latency inference.
* **C-Suite Infrastructure Advisory:** Co-authored an enterprise-wide ETL deployment blueprint and technical whitepaper directly supporting corporate AI adoption strategies, presented directly to C-suite leaders.
* **Agentic Systems:** Built production AI agents optimized for processing internal financial intelligence streams, vehicle diagnostics pipelines, retail analytics, and equipment machine cycles. Acted as Scrum Master.

#### Shepherd Ventures
*Senior Financial Quantitative Analyst Intern* | Jul 2025 - June 2026
* **Mathematical Optimization:** Engineered Mean-Variance Optimization (MVO) portfolio configuration pipelines, scaling downside market resilience up to an elite program-high 45.3% protective ratio.
* **Tail-Risk Initiatives:** Executed empirical quantitative risk research focusing on systematic drawdown bounds and clustering patterns for proprietary "Black Swan Flu Shot" market strategies.
* **Team Governance:** Promoted to Co-Leader of the AI & Injection Team. Managed a technical pod of 10 research interns, orchestrated core engineering infrastructure, and oversaw quantitative engineering recruitment.

#### Dream Avant Garde
*Founding Partner* | Dec 2025 - May 2026
* Developed decentralised tokenization models, quantitative assessment frameworks, and programmatic DeFi governance rules for a web3 venture index fund layout.

#### Advanced Intelligence Ventures (AIV)
*Founding Partner* | May 2025 - May 2026
* Focused on quantitative strategy sourcing, algorithmic infrastructure exploration, and collaborative early-stage asset architectures.

#### EY GDS & All India Council for Technical Education (AICTE)
*Full Stack Developer Intern* | Feb 2025 - Apr 2025
* Constructed cloud-integrated full-stack web architectures utilizing the MERN framework during a specialized joint technology initiative.

#### MyDailyWork
*Developer Intern* | Jul 2024 - Aug 2024
* Shipped components and refactored live functionality inside core production application frameworks.

---

### 🔲 Certifications & Credentials

<details>
  <summary>🗂️ Click to Expand Certification Portfolio</summary>
  <br>
  <table>
    <thead>
      <tr>
        <th>Issuing Institution</th>
        <th>Domain & Focus Area</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><b>Harvard University</b></td>
        <td>Advanced Computing Methods, Statistical Frameworks, and Analytical Logic Systems</td>
      </tr>
      <tr>
        <td><b>NVIDIA Deep Learning Institute (DLI)</b></td>
        <td>Parallel Computing, High-Performance GPU Acceleration, and Deep Neural Networks</td>
      </tr>
      <tr>
        <td><b>Google Cloud Platform</b></td>
        <td>Distributed Cloud Architectures, Core Data Pipelines, and Engineering Operations</td>
      </tr>
      <tr>
        <td><b>Amazon Web Services (AWS)</b></td>
        <td>Cloud Infrastructure Design, Scalable Systems Engineering, and Security Ecosystems</td>
      </tr>
    </tbody>
  </table>
</details>

---

### Ecosystem & Community
* **ACM Student Chapter:** Active core developer.
* **Hardware & Ecosystem Programs:** Selected participant in specialized engineering and developer initiatives under **NVIDIA**, **AMD**, and **GitHub**.
