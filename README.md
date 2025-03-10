### **Martin Spier**

**VP, Foundation Engineering at PicPay. Ex-Netflix.**  
Email: [hello@martinspier.io](mailto:hello@martinspier.io)  
LinkedIn: [linkedin.com/in/martinspier](http://linkedin.com/in/martinspier) | GitHub: [github.com/spiermar](http://github.com/spiermar)   
Phone: \+1 (425) 351-8800

---

### **Professional Summary**

**Senior Engineering Leader** with over 15 years of experience driving large-scale platform engineering, cloud infrastructure, and developer productivity initiatives. Proven track record of leading 200+ engineer organizations, delivering high-impact technical strategies, and fostering cross-functional collaboration to align engineering efforts with business goals. Deep expertise in **performance and reliability engineering**, large-scale **distributed systems**, and **observability**. Helped **Netflix** grow from 15 to 200+ million subscribers through scalable architectures and performance optimizations. Authored popular open-source tools and advised multiple VC funds and startups. Passionate about building high-performing teams and driving business growth through innovation.

---

### **Experience**

#### **PicPay**

**VP, Foundation Engineering**  
**Sep 2023 – Present**

*PicPay, the largest digital wallet in Latin America, extends a wide array of financial services, including peer-to-peer payments, BNPL, credit cards, personal loans, benefits, insurance, investments, and cryptocurrency to a vast user base of over 70 million individuals and serves the needs of 5 million merchants.*

- Lead a 200+ cross-functional organization responsible for core engineering functions, including the oversight of cloud infrastructure, development of internal platforms, providing robust observability solutions, driving enhancements in developer productivity, and guiding the evolution of PicPay’s mobile apps.  
- **Platform Engineering:** Implemented a foundational layer that abstracted application and infrastructure complexity, promoting consistency, reusability, and reduced developer cognitive load. Reduced Change Lead Time by over 20% and increased Deployment Frequency.  
- **Cost Efficiency & Vendor Management:** Prioritized open-source and internally developed solutions over third-party vendors, replacing two of the top three technology vendors. Improved flexibility and reduced technology costs by 22%+ through vendor contract renegotiations.  
- **Tool Consolidation:** Consolidated the Internal Developer Portal (IDP) and developer tooling, including CI/CD, observability, and source code management solutions, into a single cohesive development experience. Improved developer experience, taking the developer CSAT from 22% to 87%.  
- **Technical Debt Reduction:** Decommissioned legacy systems, including PicPay’s 12-year-old central relational database and Latin America’s largest EKS (Kubernetes) cluster, improving scalability and maintainability. Broke down the single cloud account into smaller, standardized environments managed via Infrastructure as Code (IaC), boosting security and control.  
- **FinOps Practice:** Implemented FinOps across all 16 Business Units, focusing on cost visibility, unit economics, and cloud usage optimization. Generated over $30M in annualized savings and drove efficient growth.  
- **Mobile Development Framework:** Introduced a hybrid development and Server-Driven UI (SDUI) framework, improving development cycles, boosting productivity, and reducing time-to-market by 94%.  
- **Organizational Restructuring:** Reduced complexity by decentralizing shared teams in favor of loosely coupled teams aligned with specific business needs. Increased talent density by restructuring the hiring process to focus on active hunting and structured interviews.  
- **Product & Technology Consolidation:** Consolidated product and technology into a single organization, boosting collaboration and productivity.  
- **Data-Driven Culture:** Promoted a data-driven culture by democratizing access to data, anchoring decisions in data, and defining clear metrics and KPIs for the organization.  
- **End User Focus:** Improved PicPay’s end-user experience and retention by focusing on non-functional quality metrics (crashes, ANRs, UI hangs, slow starts) through active refactoring, optimization, and automated error triage. Reduced ANRs, PicPay’s biggest offensor, by 88%, and crashes by 80%.

**VP, Foundation Engineering and Data Platforms**  
**Nov 2021 – Sep 2023**

- In addition to the Foundation Engineering organization, lead the Data Platforms team, managing 100+ developers, data scientists and engineers, responsible for the Big Data and ML platforms, and core data pipelines.  
- **Data Ingestion Model:** Improved data ingestion by transitioning from full database loads to Change Data Capture (CDC) and event streaming, significantly reducing ingestion time and infrastructure costs.  
- **Data Governance:** Established data governance frameworks and a schema registry, ensuring compliance and data quality across the organization.  
- **Workflow Management:** Decommissioned the legacy workflow management platform in favor of a fully managed Apache Airflow (MWAA) solution, reducing pipeline execution failures.  
- **BI Tool Consolidation:** Consolidated multiple BI and data visualization tools (Looker, Power BI) into a single solution (Tableau), reducing overall tooling costs.  
- **Pipeline Monitoring:** Improved pipeline monitoring and operational models, significantly reducing time to detection and recovery.  
- **Machine Learning Platform:** Spearheaded the development of the machine learning platform, enabling faster model deployment and improving user retention by 15%.

#### **Snowflake**

**Performance Architect**  
**May 2021 – Nov 2021**

- Enhanced Snowflake’s cloud data platform through architectural improvements, performance analysis of core components, and service level optimizations.  
- Developed prototypes for system observability and performance analysis tools, improving issue detection and alerting, enabling self-healing capabilities, and ensuring a more stable and efficient end user experience.  
- Collaborated with engineering teams to refine service deployment models, reducing change failure rate and increasing the overall system availability and stability.

#### **Netflix**

**Performance Architect**  
**Dec 2012 – May 2021**

- **Performance Optimization:** Designed scalable architectures and implemented optimizations for Netflix’s global streaming platform, serving over 200 million subscribers. Conducted performance analysis and tuning across all system layers, improving reliability and performance of real-time, batch, big data and ML workloads.  
- **Technical Thought Leadership:** Provided performance, reliability, scalability and efficiency expertise to guide major changes and projects, and represented Netflix at conferences as a subject matter expert.  
- **Performance Tools Development:**  
  - [**FlameScope**](https://github.com/Netflix/flamescope)**:** Open-source tool for visualizing flame graphs across time ranges, widely adopted in the industry.  
  - [**FlameCommander**](https://www.youtube.com/watch?v=L58GrWcrD00)**:** Cloud profiling tool for capturing and analyzing CPU, memory, and heapdump profiles on any cloud instance or container.  
  - **Visualizations:** Developed open-source plugins for [flame graphs](https://github.com/spiermar/d3-flame-graph) and [heatmaps](https://github.com/spiermar/d3-heatmap2) to enhance performance data analysis. These plugins are widely used in the industry and part of major projects such as Apache Flink, Google’s pprof profiler and Oracle’s Java Flight Recorder.  
  - **FlameCloud:** Continuous profiling solution collecting thousands of software profiles and millions of stacks daily.  
  - **End-to-End Tracing:** Framework linking user device tracing with backend service tracing (Zipkin-based) for improved observability.  
  - [**Icarus**](https://www.youtube.com/watch?v=4RG2DUK03_0)**:** Real user performance monitoring solution processing 180B+ events daily, with GUI for analysis, alerting, and anomaly detection.  
  - [**Vector**](https://netflixtechblog.com/introducing-vector-netflixs-on-host-performance-monitoring-tool-c0d3058c3f6f)**:** Open-source, on-host, high-resolution performance monitoring framework.  
  - **Mogul** and **Slalom:** System demand and bottleneck analysis tools for visualizing data flows and dependencies in large-scale systems.  
  - Developed the in-house performance testing framework with automated analysis capabilities, improving system reliability.  
- Created the **Netflix User Performance Score**, a Lighthouse-inspired compound metric, representing a user’s experience, and the basis for modeling the impact of performance bottlenecks in user retention.  
- **Cloud Architecture Leadership:** Defined and implemented cloud architecture standards and best practices during Netflix’s migration to the cloud, ensuring scalability, reliability, and efficiency across the platform.  
- **Mentorship & Culture Building:** Mentored engineers and onboarded new hires on performance tools and practices, raising Netflix’s bar for engineering excellence.

#### **Expedia**

**Performance Engineer**  
**Jan 2011 – Dec 2012**

#### **Dell**

**Performance Engineer**  
**Jan 2007 – Jan 2011**

---

### **Skills**

**Technical Skills:**

- Distributed Systems | Performance Engineering | Data Visualization | Observability  
- Cloud Infrastructure (AWS, Kubernetes, EKS) | Platform Engineering | Data Platforms

**Leadership Skills:**

- Organizational Leadership | Strategic Planning & Execution | Cross-Functional Collaboration  
- Data-Driven Decision Making | People Management | Team Development | Executive Communication

---

### **Education**

**PUCRS, Brazil**

- **Project Management** (2009 – 2010\)  
- **B.Sc. Computer Science** (2002 – 2008\)