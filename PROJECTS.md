# Portfolio Projects Documentation

## KOM-G | Kristiansand Kommune – Finansiell Virksomhetsstyring & KOSTRA Cockpit
- **Description**: Comprehensive municipal financial controlling and KOSTRA reporting platform for Kristiansand kommune built in Power BI Developer Mode (PBIP) with TMDL (Tabular Model Definition Language) and PBIR (Power BI Report format). Models actual ERP and budget data (`fact_data`) in a star schema linked to KOSTRA account plans (6-digit art) and function classifications (4-digit) across the municipality's two core operational sectors: Oppvekst og Utdanning (`KomSkole`) and Helse og Omsorg (`Bomiljø 2540`). Features 78 centralized DAX measures, 25 specialized report pages, Tufte S-Curves with 3-month moving averages, interactive What-If scenario simulation for cost cuts and budget reallocation, Random Forest ML time-series forecasting, and driver analysis for agency staffing, base wages, and overtime.
- **Technologies**: Power BI PBIP (.pbip / .tmdl / .pbir), Star Schema Data Modeling (`fact_data`), 78 DAX Measures (`_Måltall`), 25 Specialized Report Pages, KOSTRA SSOT Account Plan, What-If Parameter Simulation, Random Forest ML Time-Series Forecasting, Edward Tufte Data-Ink UI (Paper & Dark Mode).
- **Business Impact**: Delivers monthly variance control, early warnings (-2.23 MNOK YTD variance identified across sectors), granular driver decomposition (agency staffing, base wages, acute substitution), and what-if prescriptive action modeling for municipal finance directors and sector controllers.
- **GitHub Repository**: [KOM-G Repo](https://github.com/Frank-Ellingsen/KOM-G)
- **Live Demo**: [KOM-G KOSTRA Cockpit Live](https://frank-ellingsen.github.io/KOM-G/)
- **Power BI Project**: [KOM-G PBIP Project](https://github.com/Frank-Ellingsen/KOM-G/tree/main/pbi-rep-project.pbip)

## Kristiansand EPM & Responsible AI Framework
- **Description**: Production-ready AI Project Controller Hub & EPM Platform engineered for proactive financial management, budget controlling, and regulatory compliance in Kristiansand kommune. Covers 6 municipal areas, 81 responsibility units, and a total budget of 7.24 billion NOK (11.48B overall budget framework). Unifies automated ERP variance detection (Visma ERP vs. Framsikt EPM), rolling Monte Carlo P10/P50/P90 & EVM time-series forecasting (EAC/ETC), compliance checks for Kommuneloven §§ 14-5 & 14-6, HTA § 4, and AML § 10-12, and one-click exports to PowerPoint (Bystyret), Word (political cases), FAST Excel, and Power BI (.pbip). Architected with hybrid LLM inference (Google Gemini 3.8 Flash primary + local Ollama for air-gapped operations), local PII masking (Stage-Gate Port 4), Stage-Gate Port 9 HITL sign-off (0 autonomous actions), and cryptographic SHA-256 sealed audit trails adhering to Edward Tufte Data-Ink principles.
- **Technologies & Legislation**: 12 Specialized Controller Personas, 19 Native Antigravity Skills, Hybrid Inference (Google Gemini 3.8 Flash & Ollama), Stage-Gate Port 9 HITL Governance, Golden Record Data Lake (SQLite Star Schema & DuckDB OLAP), Framsikt EPM & KOSTRA Master Package (Wages 1010–1090 & VAR Cost Coverage), Monte Carlo P10/P50/P90, Kommuneloven §§ 14-5 & 14-6, EU AI Act (Art. 14, 26, 27 FRIA), GDPR Art. 22 & 35 DPIA, HTA § 4 & AML § 10-12, SHA-256 Audit Trail (`Audit_AI_Actions`), 6-part MLOps Package, 9-part Municipal AI Handbook, Edward Tufte Data-Ink UI.
- **Business Impact**: Equips municipal financial controllers, chief financial officers, and political committees with T-60 day early warnings before trimester close, prescriptive action menus (A, B, C) with confidence scoring, automated draft council resolutions for budget balance jf. § 14-5, and full cryptographic auditability for Kommunerevisjonen and Kontrollutvalget.
- **GitHub Repository**: [AI_KOM Repo](https://github.com/Frank-Ellingsen/AI_KOM)  
- **Live Demo**: [Kristiansand EPM & Responsible AI Framework Live](https://frank-ellingsen.github.io/AI_KOM/)

## Brønnøysund AI Lookup & Financial S-Curve Prognosis
- **Description**: Real-time Norwegian corporate intelligence platform powered by the official Brønnøysundregisteret Open REST API (Enhetsregisteret) and Google Gemini AI. Enables instant company lookup by organization number (org.nr) or company name across all Norwegian enterprises (e.g. AMOK EQUIPMENT AS, UMOE MANDAL AS, EQUINOR ASA, KONGSBERG GRUPPEN ASA). Features automated strategic financial diagnosis, AI action recommendations (EAC cost overrun mitigation, DSO reduction, FX/material hedging), and 12-month cumulative free cash flow S-Curve trajectory modeling adhering to Edward Tufte Data-Ink principles.
- **Technologies**: Brønnøysund Enhetsregisteret API, Google Gemini AI 2.5 Flash, Financial S-Curve Prognosis, EAC Risk Mitigation, Working Capital & DSO, Chart.js 4.4 Engine, Edward Tufte Data-Ink Standard.
- **Business Impact**: Provides project controllers, financial analysts, and corporate leadership with instant Norwegian enterprise registration lookup, automated AI strategic recommendations, and predictive 12-month cash flow trajectory modeling.
- **GitHub Repository**: [Look_Up_Bronnoysund Repo](https://github.com/Frank-Ellingsen/Look_Up_Bronnoysund)  
- **Live Demo**: [Brønnøysund AI Lookup & Financial S-Curve Prognosis](https://frank-ellingsen.github.io/br-nn-ysund-oppslag/)

## AMOK EQUIPMENT AS — Integrated 3-Statement Model & Executive Dashboard
- **Description**: End-to-end corporate financial intelligence suite, SQLite DataOps engine, integrated 8-year 3-statement financial model (2023–2030), and Power BI developer project for AMOK EQUIPMENT AS (Org.nr 911823705). Features automated API extraction from Brønnøysundregistrene (BrReg), FAST/ICAEW compliant Excel corkscrew modeling with 4 dynamic scenario cases (Base, Bull, Bear, Severe Stress), transactional SQLite WAL-mode database with cryptographic SHA-256 audit logging, and Power BI PBIP developer mode with TMDL semantic models and PBIR report layouts.
- **Technologies**: Integrated 3-Statement Model, FAST & ICAEW Standard, SQLite WAL-Mode DataOps, Brønnøysundregistrene BrReg API, Power BI PBIP Developer Mode (TMDL/PBIR), SR 11-7 & EU AI Act Governance, Edward Tufte Data-Ink UI.
- **Business Impact**: Delivers C-suite executive financial intelligence, 8-year liquidity and solvency forecasting, stress testing under extreme macroeconomic shifts, and version-controlled PBIP semantic reporting.
- **GitHub Repository**: [Three_State_Model Repository](https://github.com/Frank-Ellingsen/Three_State_Model)  
- **Live Demo**: [AMOK EQUIPMENT 3-Statement Model & Executive Dashboard Demo](https://frank-ellingsen.github.io/Three_State_Model/)  
- **Excel Model**: [Excel 3-Statement Model](https://github.com/Frank-Ellingsen/Three_State_Model/blob/main/models/Amok_Equipment_Integrated_3_Statement_Model.xlsx)  
- **Power BI Report**: [Power BI PBIP Project](https://github.com/Frank-Ellingsen/Three_State_Model/tree/main/powerbi)

## Power Market Back Office & Data Platform (Skagerak Kraft)
- **Description**: Full-scale Power Market Back Office and Project Controller platform engineered for portfolio anomaly detection, hydropower generation monitoring (52 plants across NO1, NO2, and NO5 price zones), and physical power imbalance settlement. Features dynamic EVM-style imbalance risk simulation (BAC/AC/ETC/EAC), interactive S-Curves with direct labeling, an Isolation Forest machine learning anomaly detection engine for SCADA telemetry faults, and an in-browser DuckDB/SQLite analytical SQL studio.
- **Technologies**: Project Controlling & EVM, Isolation Forest (Machine Learning), DuckDB (OLAP) & SQLite (OLTP), Edward Tufte Data-Ink UI, Interactive SVG S-Curves, Nord Pool / Statnett Settlement.
- **Business Impact**: Provides power plant operators, energy traders, and project controllers with automated telemetry fault detection, imbalance risk mitigation, capture price analysis, and real-time EAC forecasting.
- **GitHub Repository**: [Power Market Back Office Repo](https://github.com/Frank-Ellingsen/Power-Market-Back-Office)  
- **Live Demo**: [Power Market Back Office Demo](https://frank-ellingsen.github.io/Power-Market-Back-Office/)

## Project Finance AI — Controller Cockpit & Workflow Monitor
- **Description**: Python-based finance analytics and forecasting platform combining deterministic financial calculations, a local SQLite repository, scikit-learn machine learning forecasting, and CrewAI-style workflow orchestration with optional MLflow experiment tracking. Designed for project-controlling and financial-analysis scenarios to explain budget variances, forecast project cost behavior with a 90% confidence envelope, track policy-driven escalation thresholds (POL-FIN-2026-01), and produce a consistent analysis narrative from structured domain data.
- **Technologies**: Project Controlling & EVM, Deterministic Variance & EAC, SQLite Database Engine, Scikit-Learn ML Forecasting, CrewAI Multi-Agent Workflow, MLflow Tracking, Edward Tufte Data-Ink UI.
- **Business Impact**: Equips project controllers, financial analysts, and project managers with automated budget-to-actual variance explanations, ML-driven cost projections, escalation alerts, and auditable transaction evidence.
- **GitHub Repository**: [Project Finance AI Repo](https://github.com/Frank-Ellingsen/ml_pred_to_ai_prescript)  
- **Live Demo**: [Project Finance AI Controller Cockpit](https://frank-ellingsen.github.io/ml_pred_to_ai_prescript/)

## Norwegian Electricity Price Analysis (2021–2026)
- **Description**: Longitudinal econometric analysis of spot electricity prices across Norway's five bidding zones (NO1–NO5). Investigates seasonal fluctuations, grid transmission constraints, hydrological reservoir variance, and structural price disparities between southern and northern regions.
- **Technologies**: Python, Pandas, Power BI Modeling, Time Series Econometrics, NO1–NO5 Spot Pricing.
- **Business Impact**: Provides energy market analysts and power portfolio controllers with deep visibility into price volatility, transmission bottlenecks, and regional risk exposure.
- **GitHub Repository**: [Norwegian Electricity Price Analysis Repo](https://github.com/Frank-Ellingsen/norwegian-electricity-analysis)  
- **Live Demo**: [Norwegian Electricity Price Analysis Report](https://frank-ellingsen.github.io/norwegian-electricity-analysis/)

## AI AGENTIC PMO — Skjold-Class MTB Governance Portal
- **Description**: Autonomous PMO and Project Controlling platform engineered for naval defense lifetime extension programs (Skjold-Class Stealth Fast Patrol Boats at Umoe Mandal). Integrates full-lifecycle executive governance, interactive triple S-Curve EVM forecasting (BAC 766M NOK, CPI/SPI indices), 19 Work Package milestone Gantt scheduling, drydock execution tracking, IFRS 15 / IAS 37 accounting compliance, and Variation Order Request (VOR) governance.
- **Technologies**: Autonomous PMO Architecture, Earned Value Management (EVM), IFRS 15 / IAS 37, DuckDB / Analytical SQL, Interactive SVG Charts, Edward Tufte Data-Ink UI.
- **Business Impact**: Provides project directors, CAMs, and shipyard controllers with single-pane-of-glass variance control, EAC/ETC forecasting, and milestone risk tracking.
- **GitHub Repository**: [AI AGENTIC PMO Repo](https://github.com/Frank-Ellingsen/AI-AGENTIC-PMO)  
- **Live Demo**: [AI AGENTIC PMO Portal Demo](https://frank-ellingsen.github.io/AI-AGENTIC-PMO/)

## PMO EVM Analytics in Microsoft Fabric
- **Description**: Enterprise PMO and Earned Value Management platform built on Microsoft Fabric Lakehouse (Direct Lake) for naval defense construction (Skjold-Class Stealth Fast Patrol Boats). Features triple S-Curves, CPI/SPI indices, WBS Gantt scheduling, EMV risk matrix, and VOR governance adhering to Edward Tufte Data-Ink principles.
- **Technologies**: Microsoft Fabric, Direct Lake, DAX, Earned Value Management (EVM), Edward Tufte Data-Ink UI.
- **Business Impact**: Delivers real-time cost and schedule visibility, EAC/ETC forecasting, and proactive risk governance for major engineering programs.
- **GitHub Repository**: [PMO EVM Analytics in Microsoft Fabric Repo](https://github.com/Frank-Ellingsen/PMO-EVM-Analytics-in-Microsoft-Fabric)  
- **Live Demo**: [PMO EVM Analytics Demo](https://frank-ellingsen.github.io/PMO-EVM-Analytics-in-Microsoft-Fabric/)

## Housing Price Predictor
- **Description**: A machine learning model that predicts housing prices based on various features such as location, size, and amenities.
- **Technologies**: Python, scikit-learn, pandas.
- **Business Impact**: Helps real estate agents and buyers make informed decisions based on predicted market values.
- **GitHub Repository**: [Housing Price Predictor Repo](https://github.com/Frank-Ellingsen/housing-price-predictor)  
- **Live Demo**: [Housing Price Predictor Demo](https://housing-price-predictor.com)

## Weather Automation
- **Description**: An automation system that fetches weather data from APIs and provides forecasts.
- **Technologies**: Python, Flask, OpenWeatherMap API.
- **Business Impact**: Useful for businesses needing reliable weather inputs for operations.
- **GitHub Repository**: [Weather Automation Repo](https://github.com/Frank-Ellingsen/weather-automation)  
- **Live Demo**: [Weather Automation Demo](https://weather-automation.com)

## Car Rental Analytics
- **Description**: An analytics tool that analyzes rental data to optimize pricing strategies.
- **Technologies**: R, ggplot2, Shiny.
- **Business Impact**: Aids car rental companies to increase revenue through data-driven insights.
- **GitHub Repository**: [Car Rental Analytics Repo](https://github.com/Frank-Ellingsen/car-rental-analytics)  
- **Live Demo**: [Car Rental Analytics Demo](https://car-rental-analytics.com)

## Global Countries Report
- **Description**: A comprehensive report providing insights about various countries including economic and demographic statistics.
- **Technologies**: Python, Jupyter, Pandas.
- **Business Impact**: Useful for analysts and researchers in understanding global trends.
- **GitHub Repository**: [Global Countries Report Repo](https://github.com/Frank-Ellingsen/global-countries-report)  
- **Live Demo**: [Global Countries Report Demo](https://global-countries-report.com)

## MS Fabric Data Warehouse
- **Description**: A data warehousing solution built using MS Fabric, enabling efficient data storage and retrieval.
- **Technologies**: MS Fabric, SQL, ETL processes.
- **Business Impact**: Enhances data accessibility for businesses requiring large datasets.
- **GitHub Repository**: [MS Fabric Data Warehouse Repo](https://github.com/Frank-Ellingsen/ms-fabric-data-warehouse)  
- **Live Demo**: [MS Fabric Data Warehouse Demo](https://ms-fabric-data-warehouse.com)

## Power BI Dashboards
- **Description**: Interactive dashboards built with Power BI for visualizing business data.
- **Technologies**: Power BI, DAX, Data modeling.
- **Business Impact**: Facilitates data visualization and helps in strategic decision-making.
- **GitHub Repository**: [Power BI Dashboards Repo](https://github.com/Frank-Ellingsen/power-bi-dashboards)  
- **Live Demo**: [Power BI Dashboards Demo](https://power-bi-dashboards.com)

## Excel Data Models
- **Description**: A series of complex data models developed in Excel that analyze various datasets.
- **Technologies**: Excel, VBA, Power Query.
- **Business Impact**: Provides businesses with robust data analysis tools right in Excel.
- **GitHub Repository**: [Excel Data Models Repo](https://github.com/Frank-Ellingsen/excel-data-models)  
- **Live Demo**: [Excel Data Models Demo](https://excel-data-models.com)