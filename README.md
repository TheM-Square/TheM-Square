<div align="center">

<img src="./assets/profile-banner.svg" alt="Manas Mahajan — Chemical Engineering × Computation" width="100%" />

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-TheM--Square-0D1117?style=for-the-badge&logo=github&logoColor=F0F6FC)](https://github.com/TheM-Square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manas_Mahajan-0D1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF)](https://linkedin.com/in/manas-mahajan-41ab8b327)
[![Email](https://img.shields.io/badge/Email-Contact-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:mmahajan046.btech2024@che.nitrr.ac.in)

</div>

<br/>

## `> whoami`

I’m a **Chemical Engineering undergraduate at NIT Raipur** building computational tools for engineering problems.

My work sits at the intersection of **process engineering, numerical methods, scientific Python, and machine learning** — from thermodynamic equilibrium and distillation to heat-transfer simulation and data-driven anomaly detection.

```text
        PHYSICS
           │
           ▼
   mathematical model
           │
           ▼
   numerical methods
           │
           ├──────────────┐
           ▼              ▼
       simulation         data
           │              │
           └──────┬───────┘
                  ▼
            ML / analysis
                  │
                  ▼
          engineering insight
```

> **Current direction:** computational chemical engineering, process modeling & simulation, and ML methods that remain grounded in physical understanding.

---

## `> selected-work`

### 01 · Vapor–Liquid Equilibrium

**[VLE--Modeling](https://github.com/TheM-Square/VLE--Modeling)** · `Python` `NumPy` `SciPy` `Matplotlib`

A from-scratch binary VLE model covering **Antoine vapor-pressure calculations, Raoult’s Law, Margules activity coefficients, and numerical bubble-point solving**.

| Model | System | Output |
|---|---|---|
| Ideal | Benzene–Toluene | T–xy / x–y |
| Non-ideal | Ethanol–Water | T–xy / x–y |
| Activity model | Margules | γ₁, γ₂ |
| Solver | Brent root-finding | Bubble-point T |

<img src="https://raw.githubusercontent.com/TheM-Square/VLE--Modeling/main/vle_plots.png" alt="VLE phase diagrams" width="780" />

---

### 02 · Transient Heat-Conduction Solver

**[heat-conduction](https://github.com/TheM-Square/heat-conduction)** · `Python` `NumPy` `SciPy` `Matplotlib`

A numerical heat-transfer model using the **explicit finite-difference method** for transient conduction, with both constant-wall-temperature and convective boundary conditions.

```text
heat equation → spatial discretisation → time marching
      │                                  │
      └───────────────┬──────────────────┘
                      ▼
             stability / CFL check
                      │
                      ▼
            numerical vs analytical
```

The repository also examines the **Fourier-number stability limit** and compares the numerical solution with the Fourier-series analytical solution.

<img src="https://raw.githubusercontent.com/TheM-Square/heat-conduction/main/heat_conduction_plots.png" alt="Heat conduction simulation results" width="780" />

---

### 03 · CSTR Equilibrium Solver

**[cstr-solver](https://github.com/TheM-Square/cstr-solver)** · `Python` `NumPy` `Matplotlib`

A steady-state CSTR mole-balance problem formulated as a root-finding task and solved **from scratch** with three classical methods:

`Bisection` → `Newton–Raphson` → `Secant`

The project compares convergence behaviour and makes the numerical trade-offs visible rather than hiding them behind a library call.

<img src="https://raw.githubusercontent.com/TheM-Square/cstr-solver/main/CSTR%20PLOT.png" alt="CSTR convergence comparison" width="780" />

---

### 04 · Supply-Chain Anomaly Detection

**Smart India Hackathon 2026 · Team ZeroDay** · `XGBoost` `SHAP` `SQLite`

A hybrid anomaly/fraud detection pipeline built around **machine learning + hard-logic rules**.

```text
shipment / invoice / route data
              │
              ▼
       feature engineering
              │
       ┌──────┴──────┐
       ▼             ▼
   ML scoring     rule engine
       │             │
       └──────┬──────┘
              ▼
        risk score 0–100
              │
              ▼
      SHAP / why flagged
              │
              ▼
          SQLite logs
```

Engineered signals around **delivery delay, route deviation, invoice mismatch, and customer/carrier behaviour**, then merged model and rule outputs into an interpretable risk score.

---

## `> toolbox`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,mysql,git,jupyter" alt="Languages and tools" />

<br/><br/>

<img src="https://img.shields.io/badge/NumPy-0D1117?style=flat-square&logo=numpy&logoColor=4DABCF" />
<img src="https://img.shields.io/badge/Pandas-0D1117?style=flat-square&logo=pandas&logoColor=150458" />
<img src="https://img.shields.io/badge/SciPy-0D1117?style=flat-square&logo=scipy&logoColor=8CAAE6" />
<img src="https://img.shields.io/badge/Scikit--learn-0D1117?style=flat-square&logo=scikitlearn&logoColor=F7931E" />
<img src="https://img.shields.io/badge/XGBoost-0D1117?style=flat-square&logo=xgboost&logoColor=3FB950" />
<img src="https://img.shields.io/badge/SHAP-0D1117?style=flat-square&logoColor=58A6FF" />
<img src="https://img.shields.io/badge/CatBoost-0D1117?style=flat-square&logoColor=58A6FF" />

<br/>

<img src="https://img.shields.io/badge/Aspen_Plus-0D1117?style=flat-square&logoColor=58A6FF" />
<img src="https://img.shields.io/badge/DWSIM-0D1117?style=flat-square&logoColor=58A6FF" />
<img src="https://img.shields.io/badge/MATLAB-0D1117?style=flat-square&logoColor=58A6FF" />
<img src="https://img.shields.io/badge/Excel-0D1117?style=flat-square&logo=microsoftexcel&logoColor=217346" />

</div>

<br/>

| Layer | Focus |
|---|---|
| **Programming** | Python · C++ · SQL |
| **Scientific computing** | NumPy · SciPy · Pandas · Matplotlib |
| **ML** | Scikit-learn · XGBoost · CatBoost · SHAP |
| **Engineering** | VLE · Heat Transfer · Reaction Engineering · Process Simulation |
| **Methods** | Root-finding · ODE solving · Regression · Parameter estimation · Error / convergence analysis |

---

## `> experience`

### Nuvoco Vistas Corp Ltd. · Industrial Intern

`June 2026 · 3 weeks`

Exposure to **ABB DCS-based centralized process control**, plant-wide monitoring across raw mill / kiln / cement mill circuits, and process-level heat & mass balances through the **preheater → precalciner → rotary kiln → grate cooler** chain.

Also worked around **raw-mix design, LSF / SM / AM targets, XRF-based QA, IS-code compliance, Aspen Plus, and Excel process-data analysis**.

---

## `> things-i-care-about`

```text
┌─────────────────────────────────────────────────────────┐
│  PROCESS MODELING                                       │
│  thermodynamics · phase equilibrium · reactor models   │
├─────────────────────────────────────────────────────────┤
│  NUMERICAL COMPUTATION                                  │
│  root finding · ODEs · FDM · convergence · validation  │
├─────────────────────────────────────────────────────────┤
│  MACHINE LEARNING                                       │
│  prediction · anomaly detection · explainability      │
├─────────────────────────────────────────────────────────┤
│  SCIENTIFIC ML                                          │
│  surrogate models · physics-informed methods          │
└─────────────────────────────────────────────────────────┘
```

---

## `> github telemetry`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=TheM-Square&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=3FB950&text_color=C9D1D9&rank_icon=github&include_all_commits=true" />
&nbsp;&nbsp;
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheM-Square&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=6" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=TheM-Square&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=F78166&currStreakLabel=58A6FF&font=JetBrains%20Mono" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=TheM-Square&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=6" alt="GitHub trophies" />

</div>

---

## `> now`

```text
[████████████████████░░░░░░░░░░]  computational ChemE
[██████████████████░░░░░░░░░░░░]  process simulation
[████████████████░░░░░░░░░░░░░░]  machine learning
[██████████████░░░░░░░░░░░░░░░░]  scientific ML
```

Currently exploring **surrogate modeling, physics-informed ML, model reduction, and optimization for chemical-process systems**.

---

## `> connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0D1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF)](https://linkedin.com/in/manas-mahajan-41ab8b327)
[![Email](https://img.shields.io/badge/Email-Say_Hi-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:mmahajan046.btech2024@che.nitrr.ac.in)

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=TheM-Square&color=58A6FF&style=flat-square&label=profile+views" />

<br/><br/>

<sub><i>build the model · test the assumptions · understand the result</i></sub>

</div>
