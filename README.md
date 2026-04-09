# Hi, I'm Prajwal 😛
I'm an aspiring Data Analyst and future Data Engineer passionate about building end-to-end data pipelines and uncovering insights through data. Currently building a portfolio of projects that combine Python, SQL, and statistical testing to answer  analytical questions about areas I'm passionate about!

---

### 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

---

### 📂 Featured Projects

#### 🛰️ [Starlink Aviation — Account Attainment & Revenue Intelligence](https://github.com/prajwalhendre/starlink-attainment)
> A six-script Python pipeline and Tableau dashboard modeling Starlink Aviation's fleet attainment gap and revenue opportunity across 10 airline partners

- Downloaded and parsed the full FAA Aircraft Registry (4,266 aircraft) to get real tail number counts per airline
- Built a fuzzy string matching join using `str.contains()` to handle FAA legal entity name suffixes that break exact joins
- Modeled $699.75M theoretical maximum ARR and a $52.9M monthly revenue gap at current 9.3% global attainment
- Flagged American Airlines and Delta as Critical accounts ($12.2M and $10.5M monthly gaps with all STCs pending)
- Built a five-view Tableau dashboard with risk tiering, attainment %, fleet overview, and global footprint
- **Tools:** Python, Pandas, NumPy, Requests, Tableau Public, FAA Aircraft Registry

**[View the Live Dashboard](https://public.tableau.com/views/Book1_17533820297810/AccountAttainmentDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

#### 🎮 [League of Legends Champion Design Analysis](https://github.com/prajwalhendre/lol-champion-analysis)
> Analyzing how Riot Games' champion design philosophy has evolved since 2009 using live API data, normalized SQL, and statistical testing
- Pulled live data from the Meraki Analytics API using Python `requests` — no static CSV, fully dynamic pipeline
- Built a **normalized SQLite database** with junction tables for champion roles and positions
- Statistically confirmed melee champions receive significantly higher armor (+32.8%), HP (+6.4%), and move speed compensation (all p < 0.0001)
- Found modern champions have significantly lower base HP than launch era champions (Tukey HSD p=0.0025)
- Discovered Riot is shifting away from Tanks (18% → 5.5%) toward Assassins (13% → 23%) in proportional release share
- **Tools:** Python, Pandas, SQLite, Matplotlib, Seaborn, SciPy, Statsmodels, Requests

#### 🔴 [Pokémon Generational Analysis](https://github.com/prajwalhendre/pokemon-generation-analysis)
> An end-to-end data pipeline analyzing how Pokémon design has evolved across 9 generations
- Built a full pipeline: raw CSV → Python cleaning → SQLite database → SQL analysis → visualization
- Performed statistical testing (Pearson Correlation, ANOVA, Chi-squared) to uncover design trends
- Found statistically significant power creep in regular Pokémon (p = 0.0016) while Legendaries show no generational pattern
- **Tools:** Python, Pandas, SQLite, Matplotlib, Seaborn, SciPy

---

### 📊 What I'm Building Toward
| Area | Current Level | Next Step |
|---|---|---|
| Python | Pandas, SciPy, API calls | Machine Learning |
| SQL | Joins, window functions, subqueries | Query optimization |
| Statistics | T-tests, ANOVA, Tukey HSD | Regression modeling |
| Data Engineering | SQLite pipelines | Cloud (coming soon) |

---

### 🌱 Currently Working On
- Building a data analytics portfolio with real statistical findings
- Deepening SQL skills for technical interviews
- Exploring machine learning foundations (coming soon!)

---

### 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prajwal-hendre-/)
