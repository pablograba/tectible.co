# Pablo G. Baretto

Solutions architect and data engineer with 20+ years of experience. I design and build AI stacks: production systems, evaluation, search, agentic harnesses, and the data platforms under them. I design around each company’s cloud, vendors, privacy rules, cost structure, and the team that will run the system. That includes private and air-gapped deployments when shared model APIs are not acceptable.

I previously worked as a presales and delivery architect for production cloud and data platforms. The work starts from operating constraints.

------------------------------------------------------------------------

## Experience

### AI architecture and implementation

**2021 - Present**

Long engagements with mid-market companies, product companies, and venture-backed startups. I assess the environment, design an AI stack that fits it, and implement the system far enough that the client can operate it.

- **US mental-health provider (regulated reporting).** Built a generative workflow for clinical reports with evaluation against real cases and human review for exceptions, using existing data and process rather than a new model stack. About **98%** of reports passed the agreed checks; roughly two reports per day still go to review.
- **Legal SaaS, Spain.** Answers grounded in national law, with no cleaned corpus and no custom LLM. Ingestion pipelines plus RAG with citations. Agreed accuracy on sampled answers ~**99%**; human review dropped to about **1%** of responses; time to an answer fell ~**90%**.
- **Matchbook AI, USA.** Matching engine for messy, continuously arriving master data used by ~50 S&P 500 clients. Initial load ~**500 million** records and ~**1 million** updates per day (about 15% above the original target). Processing time down **35%**; SLA breaches stopped.
- **Sonarplatform, EU.** Search and analytics over on-chain data: ~**1 billion** transactions across 10+ Ethereum networks, ingest ~**3,000 tx/s**, API p95 under **800 ms**.
- **US consumer-data product.** Hybrid lexical and vector search under ingest and latency limits (ingest up to **200 MB/s**, search under **500 ms**), rather than a single-vendor search stack.
- **Holobrain** is a private deployment pattern used when customer data and models must stay on the customer’s infrastructure. It’s one implementation path, not the architecture for every client. [holobrain.ai](https://holobrain.ai)

### Data Analytics Solutions Architect, Logicalis (Spain)

**2015 - 2021**

Progressed from Cloud Solutions Architect to Data Analytics Solutions Architect at a global IT services firm. Designed production data and analytics platforms from each client’s cloud footprint, tooling, and operating model, including presales architecture and delivery. Not a standard reference build.

- Architected and led Orange’s unified log and metrics platform on an Elasticsearch-inspired stack already compatible with their operations model. Reduced MTTD ~**55%**, MTTR **45%**, unplanned downtime **30-40%**, and manual log analysis **\>60%**.
- Delivered production systems and PoCs for Vodafone, Telefónica, FNMT, Grupo Piñero, La Caixa, Ocaso, AENA, and Catalana Occidente, scoped to each organization’s capacity and vendor landscape.

### Senior Data Analytics Consultant

**2006 - 2015**

Analytics for IT monitoring and support across Latin America. Assembled open-source and existing vendor tools to fit mid-sized firms’ budgets and operations teams.

- **FacilDesk (founder).** Open-source IT monitoring (Elasticsearch) and ticketing (OTRS) with analytics for mid-sized firms. Mitsubishi Motor Company: **+67%** customer satisfaction. Bancaribe: **43%** faster incident response. Also Agroamerica and Cerámicas Caribe.
- **Sun Microsystems contractor (Venezuela).** Data-centric monitoring assembled onto telco and oil & gas estates (CANTV, Movilnet, Telefónica, PDVSA, ENI).

### Java Trainer and Consultant, Sun Microsystems (Venezuela)

**2001 - 2006**

Java training and consulting across northern Latin America.

------------------------------------------------------------------------

## Selected work

**Holobrain.** Private, air-gapped AI deployments for organizations whose privacy requirements rule out shared LLM APIs. Open-weights models and automated workflows run on the customer’s infrastructure. This is one implementation path when policy requires it, not the default for every client. [holobrain.ai](https://holobrain.ai)

------------------------------------------------------------------------

## Certifications

**Google Cloud Professional Data Engineer**, 2020

**Elasticsearch Certified Engineer**, 2020

------------------------------------------------------------------------

## Education

**Universidad de Los Andes (Venezuela)**, Systems Engineer, 2001

**Universidad Complutense de Madrid (Spain)**, Master’s in Marketing Management
