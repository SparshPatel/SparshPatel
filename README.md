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
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟨 Portfolio & Convex Optimization</summary>
  <blockquote>
    <b>Definition:</b> A mathematical subfield of optimization that studies the problem of minimizing convex functions over convex sets. In finance, it guarantees finding the single globally optimal asset allocation weights (e.g., maximizing Sharpe ratio) under tracking-error, leverage, or regulatory constraints.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟩 Time Series Analysis</summary>
  <blockquote>
    <b>Definition:</b> A statistical methodology used to analyze a sequence of data points collected over time intervals. It isolates internal structures such as trends, seasonal variations, and cointegration properties to construct predictive models for highly non-stationary financial data streams.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟦 Reinforcement Learning</summary>
  <blockquote>
    <b>Definition:</b> An area of machine learning concerned with how intelligent agents take sequential actions within an environment to maximize a cumulative reward function. It resolves multi-period decision problems through exploratory trial-and-error without needing a static analytical environment.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟪 Nonlinear Physics & Stochastic Resonance</summary>
  <blockquote>
    <b>Definition:</b> The study of complex systems where outputs are non-proportional to inputs. It includes phenomena where a system utilizes ambient background noise to amplify weak structural signals, making hidden phase transitions or regime shifts visible.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟫 Bayesian Optimization</summary>
  <blockquote>
    <b>Definition:</b> A sequential design strategy for global optimization of expensive black-box functions. It uses a probabilistic surrogate model (like Gaussian Processes) to guide search parameters efficiently by evaluating choices based on exploration and exploitation metrics.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>🟧 Python & Vectorization</summary>
  <blockquote>
    <b>Definition:</b> A high-level programming paradigm that replaces explicit loop operations with heavily optimized, compiled array-level instructions. It eliminates interpreter overhead to run lightning-fast data transformations on multi-dimensional matrices.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>⬛ Differentiable Optimization</summary>
  <blockquote>
    <b>Definition:</b> An engineering architecture that treats mathematical optimization problems as standard, backpropagation-friendly neural network layers. It permits the calculation of analytical gradients directly through implicit optimization surfaces for end-to-end learning systems.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

### Interactive Project Ecosystem

<details>
  <summary>📁 Project: Volatility Targeting, Variance Drain, and the Financialization Effect</summary>
  <blockquote>
    <b>Skills Used:</b> Stochastic Calculus, Econometrics, Heston-Merton Framework, Python, CRSP Data Analytics<br><br>
    <b>Core Execution:</b> Derived closed-form Sharpe improvement from Heston–Merton framework with formal propositions linking volatility targeting to Merton-optimal allocation and variance drain reduction. Validated on 100-year CRSP data across 21 assets and 14 international markets; proposed VDOV rule achieving OOS Sharpe of 1.01 vs. 0.94 Moreira and Muir benchmark, 0.79 buy-and-hold, with structural break analysis at $\tau^* \approx 1985$.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Delta-Guided Soft Actor-Critic for Derivative Hedging</summary>
  <blockquote>
    <b>Skills Used:</b> RL, Derivatives, Stochastic Processes, PyTorch, Gym/Stable-Baselines<br><br>
    <b>Core Execution:</b> Proposed novel reward-shaping scheme embedding Black–Scholes delta as time-decaying inductive bias with original asymptotic optimality proof and $O(\sqrt{N \log N})$ finite-time regret bound. Reduced hedging error by 19–38% across GBM, Merton jump-diffusion, and rough Bergomi ($H=0.07$) environments with $2\times$ convergence speedup over vanilla SAC; validated on real SPY/QQQ/IWM options.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Bayesian Optimisation of Cointegration-Based Stat Arb</summary>
  <blockquote>
    <b>Skills Used:</b> Bayesian Opt., Kalman, Time Series, Johansen VECM, Gaussian Processes<br><br>
    <b>Core Execution:</b> Built multi-universe stat-arb pipeline using Johansen VECM, adaptive Kalman hedge ratios, and GP-BO (Matérn 5/2, Expected Improvement) to jointly tune 5 parameters end-to-end. Achieved OOS Sharpe signals averaging 5.78 across 5 ETF universes with walk-forward re-optimisation; ablation study identified Kalman filter as single most impactful component.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Adaptive Coupled Stochastic Resonance for Vol Regime Detection</summary>
  <blockquote>
    <b>Skills Used:</b> Nonlinear Physics, Econometrics, Langevin Dynamics, Transfer Entropy, Walk-Forward Testing<br><br>
    <b>Core Execution:</b> Designed coupled Langevin bistable detector arrays with adaptive Kramers-rate barriers and transfer entropy-based coupling for early VIX regime transition detection. Outperformed 10 SOTA methods (CUSUM, BOCPD, Markov-Switching, PELT, etc.) with 200 IAAFT phase-randomized surrogate validation on strict walk-forward test set (2019–2025).
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Factor Exposure and Correlation Decomposition</summary>
  <blockquote>
    <b>Skills Used:</b> Portfolio Diversification, Factor Analysis, Risk Management, Python<br><br>
    <b>Core Execution:</b> Proposes an integrated diagnostic framework combining multiple methodologies to check if a portfolio with multiple asset classes is diversified, and suggests a way to truly diversify portfolios. Modeled correlation spikes over 20 years of data across 25 asset vectors, yielding a tactical strategy that reduced maximum drawdown profiles by close to half.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Robust Portfolio Optimization via Smart Predict-then-Optimize</summary>
  <blockquote>
    <b>Skills Used:</b> Differentiable Opt., Deep Learning, KKT Conditions, cvxpy, Robust Allocation<br><br>
    <b>Core Execution:</b> Implemented end-to-end differentiable portfolio construction embedding a mean-variance optimization layer directly within a deep neural network pipeline. Computes exact analytical gradients through the implicit optimization surface using KKT conditions, structurally matching the prediction error loss function with out-of-sample portfolio efficiency.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: DepreciNet — Multi-Modal Deep Learning for Real Estate Pricing</summary>
  <blockquote>
    <b>Skills Used:</b> PyTorch, Cross-Attention Architectures, Neural Radiance Fields (NeRF), Spatial Encoding<br><br>
    <b>Core Execution:</b> Designed a 5-branch cross-attention PyTorch architecture with learnable exponential depreciation, NeRF-style spatial encoding, and interpretable price decomposition ($V_{\text{structural}} + V_{\text{location}} + V_{\text{condition}} + \Delta_{\text{market}}$).
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Kappa Quant</summary>
  <blockquote>
    <b>Skills Used:</b> Convex Optimization, Options Pricing, Risk Management, Plotly, cvxpy<br><br>
    <b>Core Execution:</b> Two open source quant tools: CVaR portfolio optimizer using Rockafellar-Uryasev LP (cvxpy, 8-stock universe, benchmarked on Sharpe/VaR/CVaR) and an implied volatility surface builder using Black-Scholes inversion (Brent’s method) on live AAPL options with interactive 3D Plotly surfaces.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Cross-Asset Time Series Momentum Strategy</summary>
  <blockquote>
    <b>Skills Used:</b> Factor Research, Portfolio Construction, Time Series Momentum, Permutation Tests<br><br>
    <b>Core Execution:</b> Extended Moskowitz, Ooi & Pedersen (2012) across 17 instruments and 4 asset classes (equities, fixed income, commodities, currencies) with multi-horizon lookback (1, 3, 6, 12 months). Implemented volatility-targeted position sizing, permutation-based statistical tests, and regime-conditional factor exposure decomposition with deliberate anti-overfitting design.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

<details>
  <summary>📁 Project: Assistive System for Medication Info Retrieval & Braille Conversion</summary>
  <blockquote>
    <b>Skills Used:</b> ML, Image Processing, Web Scraping, Python<br><br>
    <b>Core Execution:</b> Developed a multi-model pipeline for medicine leaflet classification and medication information retrieval. Application Number: 202641007661.
    <br><br>
    <button onclick="this.closest('details').removeAttribute('open')">Close Box ✖</button>
  </blockquote>
</details>

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
* **Mathematical Optimization:** Engineered Mean-Variance Optimization (MVO) portfolio configuration pipelines, scaling downside market resilience up to an elite program-high 45.3% protective ratio under simulated market crises.
* **Tail-Risk Initiatives:** Executed empirical quantitative risk research focusing on systematic drawdown bounds and clustering patterns for proprietary "Black Swan Flu Shot" market strategies. Led a team project.
* **Team Governance:** Promoted to Co-Leader of the AI & Injection Team. Managed a technical pod of 10 research interns, orchestrated core engineering infrastructure, and oversaw quantitative engineering recruitment.

#### Dream Avant Garde
*Founding Partner* | Dec 2025 - May 2026
* The first ever decentralized venture index fund championing emerging businesses by providing tokenization, resources, and support. Built decentralized tokenization models, quantitative assessment frameworks, and programmatic DeFi governance rules.

#### Advanced Intelligence Ventures (AIV)
*Founding Partner* | May 2025 - May 2026
* Focused on quantitative strategy sourcing, algorithmic infrastructure exploration, and collaborative early-stage asset architectures.

#### EY GDS & All India Council for Technical Education (AICTE)
*Full Stack Developer Intern* | Feb 2025 - Apr 2025
* Constructed cloud-integrated full-stack web architectures utilizing the MERN framework for a recipe book application during a specialized joint technology initiative.

#### MyDailyWork
*Developer Intern* | Jul 2024 - Aug 2024
* Shipped components and refactored live functionality inside core production application frameworks.

### 🔲 Certifications & Credentials

<details>
  <summary>⬜ CLICK TO EXPAND CERTIFICATION PORTFOLIO</summary>
  <br>
  <table>
    <thead>
      <tr>
        <th>Harvard University</th>
        <th>NVIDIA Deep Learning Institute</th>
        <th>Google Cloud Platform</th>
        <th>Amazon Web Services</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Advanced Computing Methods</td>
        <td>Parallel Computing</td>
        <td>Distributed Cloud Architectures</td>
        <td>Cloud Infrastructure Design</td>
      </tr>
      <tr>
        <td>Statistical Frameworks</td>
        <td>High-Performance GPU Acceleration</td>
        <td>Core Data Pipelines</td>
        <td>Scalable Systems Engineering</td>
      </tr>
      <tr>
        <td>Analytical Logic Systems</td>
        <td>Deep Neural Networks</td>
        <td>Engineering Operations</td>
        <td>Security Ecosystems</td>
      </tr>
    </tbody>
  </table>
  <br>
  <button onclick="this.closest('details').removeAttribute('open')">Close Credentials ✖</button>
</details>

### Ecosystem & Community
* **ACM Student Chapter:** Active core developer.
* **Hardware & Ecosystem Programs:** Selected participant in specialized engineering and developer initiatives under **NVIDIA**, **AMD**, and **GitHub**.
