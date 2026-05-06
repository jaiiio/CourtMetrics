
 # CourtMetrics

**End-to-end Data Engineering project** for the Argentine Professional Basketball League (LNB).

While NBA and European leagues have rich public advanced statistics, the LNB lacks accessible advanced metrics (TS%, eFG%, USG%, etc.).

### 🎯 Objective
Build a modern **Lakehouse** platform to generate advanced basketball analytics for San Lorenzo de Almagro (and eventually the entire league).

---

### 🛠 Tech Stack

- **Ingestion**: Python + Playwright (Web Scraping)
- **Storage**: Parquet + Delta Lake
- **Processing**: Spark SQL + Databricks
- **Architecture**: Medallion Architecture (Bronze → Silver → Gold) + Star Schema
- **Orchestration**: Databricks Workflows (in progress)

---

### 📊 MVP - Stage 1 (Completed)

- Scraped official data from [laliganacional.com.ar](https://laliganacional.com.ar)
- Implemented full **Medallion Architecture**:
  - **Bronze**: Raw data
  - **Silver**: Cleaned, transformed and quality-checked data
  - **Gold**: Advanced metrics ready for analysis
- Built Star Schema for analytical queries
- Performed EDA on every layer to ensure data quality
- Created initial dashboards for quick insights

**Screenshots:**

 ![image_1777994827794.png](./image_1777994827794.png "image_1777994827794.png")  

 ![image_1777995829084.png](./image_1777995829084.png "image_1777995829084.png")  

  ![image_1778014964960.png](./image_1778014964960.png "image_1778014964960.png")  


  ### 🚀 How to Run the Project (Local / Databricks)

**Próximamente** — Working on it.

### Future Roadmap

- Stage 2: Expand to all teams in the league
- Stage 3: Comparative analysis with NBA/Europe
- Stage 4: Play-by-play data
- Stage 5: Interactive dashboards (Power BI / Streamlit / Grafana)

---

**Autor**: Fabio Fernández  
**Estado**: MVP Finished (Abril 2026)
