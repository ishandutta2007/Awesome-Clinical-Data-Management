# Awesome-Clinical-Data-Management

# Top Clinical Data Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Electronic Data Capture, CDISC Compliance, Data Cleaning & Regulatory Submission*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Clinical Data Management**. These tools help sponsors, CROs, and research institutions capture, clean, transform, and submit clinical trial data in compliance with GCP, 21 CFR Part 11, and CDISC standards.

**Examples** include Medidata, Veeva Vault CDMS, Oracle Clinical One, Clario, IBM Clinical Development, OpenClinica, Ennov Clinical, Macro EDC, ClinCapture, and Castor (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom study workflows, and transparent clinical data — ideal for academic research centers and non-profit organizations that need full control over sensitive patient data without per-subject SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Medidata](https://www.medidata.com/)**
  The dominant clinical data management platform. Provides Rave EDC, Rave RTSM, and the Medidata Clinical Cloud for end-to-end trial data capture, management, and reporting.

- **[Veeva Vault CDMS](https://www.veeva.com/)**
  Cloud-native clinical data management system within Veeva's Clinical Suite. Provides EDC, data cleaning, coding, and submission-ready datasets with deep integration to Veeva Vault eTMF.

- **[Oracle Clinical One](https://www.oracle.com/)**
  Cloud clinical data management platform. Provides EDC, data management, and trial management with Oracle's enterprise infrastructure and support.

- **[Clario](https://clario.com/)**
  Clinical endpoint technology provider. Provides eCOA, cardiac safety, imaging, and respiratory endpoints with data management capabilities.

- **[IBM Clinical Development](https://www.ibm.com/)**
  Clinical data management platform from IBM. Provides EDC, data management, and CDISC capabilities for large pharmaceutical and CRO deployments.

- **[OpenClinica](https://www.openclinica.com/)**
  Commercial open-source clinical trial software. Provides a **free Community Edition** for self-hosted deployment and a cloud-hosted enterprise version with ePRO, randomization, and reporting modules . The cloud version is validated and compliant with 21 CFR Part 11, GCP, and HIPAA .

- **[Ennov Clinical](https://www.ennov.com/)**
  EDC and clinical data management platform within Ennov's regulatory and quality suite. Provides document management, workflow, and compliance tracking.

- **[Macro EDC](https://www.elsevier.com/)**
  Elsevier's EDC platform. Provides electronic data capture, data management, and CDISC export capabilities.

- **[ClinCapture](https://www.clincapture.com/)**
  Clinically validated open-source EDC software. Commercial support and hosting available with ePRO, CTMS integration, and offline capabilities.

- **[Castor](https://www.castoredc.com/)**
  Clinical research platform with EDC, eConsent, ePRO, and decentralized trial tools. Popular with academic and investigator-initiated research.

## Open-Source GitHub Projects

### Full EDC/CDM Platforms

- **[LibreClinica](https://github.com/reliatec-gmbh/LibreClinica)**
  **The community-driven successor to OpenClinica and the most active open-source EDC/CDM platform.** Forked in 2019 from OpenClinica 3.14 and actively maintained by ReliaTec GmbH and community contributors including University Hospital RWTH Aachen and DKFZ Partner Site Dresden . **Current version**: v1.4.0 (Tomcat 9, OpenJDK 11, PostgreSQL 13/14) . **Key features**: Web-based CDM and EDC system typically used for clinical trials, registers, and other studies . **GCP-compliant** with full audit trails, electronic signatures, discrepancy management, and CDISC ODM-XML import/export . **Extensibility**: SOAP web services for programmatic data access; support for HTML, CSS, and JavaScript injection into CRF Excel sheets; JavaScript (jQuery) available for custom form logic . **Proven in production**: Used for over 10 years at institutions including University Hospital Aachen . Users report it is "one of the most powerful clinical EDC systems, definitely a cost-effective option, extremely user-friendly, flexible and stable" . **Open source (LGPL)** . **Migration path**: Direct database migration from OpenClinica 3.14+ documented .

- **[OpenClinica Community Edition](https://github.com/OpenClinica/OpenClinica)**
  **The original open-source EDC/CDM platform that launched the category.** The world's first commercial open-source clinical trial software . **401 GitHub stars** . **Community Edition is free** and available for self-hosted deployment . **Key features**: Powerful EDC for clinical studies of any size, scope, language, or budget . **Freedom from vendor lock-in**, freedom to tailor the solution to specific needs, and control over eClinical technology rather than being controlled by it . **License**: LGPL (Lesser General Public License) . **Note**: OpenClinica 4.0 is no longer GPL-licensed; Community Edition continues under LGPL for OpenClinica 3.x lineage . The cloud-hosted version adds drag-and-drop study designer, modern UI, and mobile-friendly forms .

- **[REDCap](https://projectredcap.org/)**
  **The most widely deployed research data capture platform in academia.** Developed at Vanderbilt University in 2004 and maintained by the REDCap Consortium with **4,000+ institutional partners across 130+ countries** . **1.3+ million users** worldwide . **Free for non-profit and governmental institutions** through consortium membership . **Key features**: Secure, web-based data collection and management with customizable data entry forms, role-based access privileges, randomization management (concealed but traceable), double-data entry, formal data querying with transparent decision records, sophisticated tracking system creating complete audit trails, and online survey capability . **Statistician-friendly**: Data can be downloaded directly to SAS, STATA, SPSS, and R . **Regulatory compliance**: Designed for clinical research with complete audit trails preventing accidental or intentional data changes . **Note**: While free, REDCap is **not open-source or freeware** — individual download is not permitted; institutions must join the consortium and attain an end-user license agreement . Requires PHP web server and MySQL database with institutional technical support .

- **[Phoenix CTMS](https://github.com/phoenixctms/ctsms)**
  **The "ultimate CTMS/PRS/CDMS" open-source platform.** **56 stars, actively maintained** (updated weekly) . Java-based comprehensive clinical trial management system providing Clinical Trial Management System (CTMS), Patient Recruitment System (PRS), and Clinical Data Management System (CDMS) capabilities. **Open source**.

- **[LCARS-C](https://github.com/hcstubbe/lcarsc)**
  **Lightweight Clinical Data Acquisition and Recording System for resource-limited settings.** Published in *Scientific Reports* (Nature, 2024) . **MIT License** . **Key features**: Metadata-driven interface and database structure with uncomplicated setup; editor and library modules; lightweight architecture specifically designed for resource-constrained environments . **Validated in four clinical studies** at Ludwig Maximilian University of Munich with thorough code review, automated unit testing (testthat), and Selenium frontend tests . **R-based implementation**. **Open source (MIT)** .

### CDISC Data Transformation & Submission

- **[sdtm.oak](https://github.com/pharmaverse/sdtm.oak)**
  **EDC-agnostic SDTM data transformation engine from the pharmaverse community.** **26 GitHub stars, updated weekly** . **Key innovation**: Automates transformation of raw clinical data in **ODM format to SDTM** based on standard mapping algorithms . **EDC and Data Standard agnostic** — works with any EDC system and any CDISC SDTM IG version . **Modular programming framework** with reusable "algorithms" as functions . **V0.2.0 capabilities**: Creates DM domain and various SDTM domains encompassing Findings, Events, Findings About, and Intervention classes . **Available on CRAN** . **Roadmap**: Metadata-driven code generation, SV/SE domains, EPOCH variable, and standard units/results derivation . **R package** .

- **[cdiscbuilder](https://pypi.org/project/cdiscbuilder/)**
  **Python package to convert ODM XML to SDTM/ADaM datasets.** **Configuration-driven approach** using YAML files or Python dictionaries without hardcoding complex logic . **Key features**: ODM XML parsing into dataframes; configurable mappings (source columns, hardcoded values, custom logic); schema validation; metadata-driven Findings domain processor (VS, LB, FA, etc.); Excel/Parquet output for regulatory-compliant datasets . **CLI and Python API**: `cdisc-sdtm --xml study_data.xml --output ./sdtm_data` . **Advanced mapping**: prefixing, substring extraction, fallback, default values, and case-sensitive mapping . **Open source (PyPI)** .

- **[OpenEDC](https://github.com/)]**
  **Open-source CDISC ODM-based EDC editor and data collection tool.** Developed at Heidelberg University's Medical Informatics Institute (MDM-Portal) . **Key principle**: All data processed and stored **only on your local device** — no cloud dependency . Can connect to an OpenEDC server for multi-user, multi-site projects . **Features**: Design medical research projects based on CDISC ODM-XML standard; drag-and-drop form building with events, forms, groups, questions, and codelists; export to ODM XML, CSV, or direct upload to MDM-Portal . **Important caveat**: Inputs are not cached between sessions — regular data exports are strongly recommended . **Open source**.

### Additional Strong Open-Source Options

- **Full EDC/CDM**: **LibreClinica** (most active, OpenClinica successor, LGPL), **OpenClinica Community** (original open-source, LGPL), **Phoenix CTMS** (CTMS+PRS+CDMS, Java) .
- **Academic Research**: **REDCap** (4,000+ institutions, free for non-profits, not open-source) .
- **Resource-Limited**: **LCARS-C** (MIT, R-based, validated in studies) .
- **CDISC Transformation**: **sdtm.oak** (R, EDC-agnostic, ODM→SDTM), **cdiscbuilder** (Python, YAML-configured) .
- **ODM Editing**: **OpenEDC** (local-first, MDM-Portal integration) .

**Frameworks for building custom systems**: Combine **LibreClinica** for the core EDC/CDM platform with GCP compliance and CDISC ODM support, **sdtm.oak** or **cdiscbuilder** for SDTM/ADaM transformation, **LCARS-C** for lightweight deployments in resource-limited settings, and **OpenEDC** for local-first ODM form design. Add **PostgreSQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Clinical data management platforms handle sensitive patient and trial data; ensure compliance with 21 CFR Part 11, ICH-GCP, HIPAA, GDPR, and applicable regional regulations.
- **Open-source reality**: The open-source ecosystem for clinical data management is **mature and production-proven**. **LibreClinica** is the most active successor to OpenClinica with 10+ years of production use at university hospitals . **OpenClinica Community Edition** provides the original open-source EDC/CDM platform with LGPL licensing . **REDCap** is the most widely deployed research data capture platform with 4,000+ institutional partners, though it is not technically open-source . **LCARS-C** offers a lightweight MIT-licensed alternative validated in clinical studies . **sdtm.oak** and **cdiscbuilder** provide open-source CDISC transformation pipelines . For enterprise-scale deployments with global support, commercial platforms (Medidata, Veeva, Oracle) remain the primary choice, but open-source alternatives are **genuinely viable for academic institutions and research centers** with technical capacity.
