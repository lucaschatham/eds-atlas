# Independent Ehlers-Danlos Research Collaborative

A patient-informed, expert-supervised collaboration developing an AI-assisted Ehlers-Danlos syndrome (EDS) phenotype dataset and an explainable evidence navigator.

**Status:** Forming team and preparing an application to Anthropic's AI for Science rare disease program.

**Project title:** Mapping EDS Heterogeneity: A Research-Ready Dataset and Explainable Evidence Navigator

**Track:** Basic science research

> This repository describes a proposed research project. It is not a clinical service and does not provide medical advice, diagnosis, or treatment.

## Why this matters

EDS is a heterogeneous group of inherited connective-tissue disorders with variable, multisystem effects. Patients may experience joint instability, chronic pain, fatigue, autonomic and gastrointestinal symptoms, bruising, bleeding, poor wound healing, and long diagnostic delays. Risk also varies substantially by subtype and individual phenotype. The absence of reliable risk stratification can leave some patients without appropriate perioperative precautions while creating uncertainty around beneficial procedures for others.

Published prevalence estimates vary because EDS, hypermobile EDS (hEDS), and hypermobility spectrum disorders (HSD) are defined and counted differently:

- A conventional minimum estimate of at least 1 in 5,000 for all EDS types implies roughly **1.6 million people worldwide** using a global population of 8.2 billion.
- A health-record estimate of approximately 1 in 3,100 for diagnosed hEDS would imply roughly **2.6 million people worldwide** if generalized globally.
- A broader estimate near 1 in 500 for the combined EDS and HSD spectrum would imply roughly **16.4 million people worldwide**.

These figures are alternative estimates, not additive. The 16.4 million estimate includes HSD and must not be described as EDS alone.

## Scientific question

Can harmonized clinical, patient-reported, and literature-derived phenotype data reveal reproducible symptom clusters and mechanistic relationships across EDS, and can those relationships support an explainable, evidence-grounded research navigator?

## Six-month deliverables

### 1. Research-ready EDS dataset

- Harmonize approved EDS datasets into one documented schema.
- Map phenotype terms to shared ontologies, including HPO and Mondo.
- Preserve source provenance, uncertainty, consent status, and review status.
- Add consented, deidentified patient-reported data only when ethics and governance requirements permit.
- Support analysis of phenotype clusters, mechanisms, bleeding patterns, and surgical readiness.
- Release governance-permitted data, schemas, mappings, evaluations, and hypotheses through the Monarch ecosystem.

### 2. Personalized EDS Navigator research prototype

- Accept structured symptoms, history, diagnostic stage, and prior interventions.
- Return explainable phenotype-to-disease pathways and a differential for clinician review.
- Surface evidence-linked management questions and individualized bleeding, wound-healing, and perioperative considerations.
- Show rationale, source evidence, uncertainty, and expert-review status for every material output.
- Support research and shared decision-making without diagnosing or prescribing.

## Method

Claude will assist with literature and case-report review, structured extraction, phenotype normalization, ontology mapping, deduplication, contradiction detection, evidence synthesis, hypothesis generation, and model evaluation. Claude Code will support ingestion pipelines, data-quality tooling, analysis workflows, evaluation harnesses, and the web prototype.

Domain experts will define the research questions, review all research-facing claims, validate a stratified sample of extracted data, assess mechanistic hypotheses, and review the bleeding and surgical-readiness module. Claude outputs will remain proposals until a qualified human reviewer approves them.

## Proposed success criteria

Within six months, the project aims to:

- Harmonize at least three independent EDS data sources and 2,000 governance-approved patient records.
- Process at least ten times the evidence volume of a documented manual baseline.
- Achieve at least 90% expert-validated phenotype extraction and ontology-mapping accuracy.
- Maintain source provenance, uncertainty, and review status for every research-facing output.
- Identify at least five expert-endorsed phenotype clusters or mechanistic hypotheses, with at least two advanced into follow-on studies.
- Complete a blinded evaluation of at least 100 cases with at least 90% capture of documented diagnostic, bleeding, wound-healing, and perioperative risk factors.
- Conduct testing with at least 50 people with EDS and 20 clinicians or researchers.
- Obtain at least 80% agreement that the Navigator surfaces a relevant, expert-validated risk, management question, or next step not readily visible in the source record.

Targets remain contingent on confirmed data access, ethics review, consent, and scientific-lead approval.

## Timeline

| Period | Work |
| --- | --- |
| Month 1 | Confirm scientific lead, pilot population, governance, data access, schema, and evaluation plan |
| Months 2 and 3 | Ingest, harmonize, deduplicate, map, and quality-check approved data |
| Months 3 and 4 | Analyze phenotype clusters, test hypotheses, and evaluate Claude-assisted extraction |
| Months 4 and 5 | Build and integrate the EDS Navigator research prototype |
| Month 6 | Complete blinded evaluation, expert and patient testing, failure analysis, documentation, and public release |

## Team

| Member | Affiliation | Focus | Contact |
| --- | --- | --- | --- |
| Chris Mungall, PhD | Lawrence Berkeley National Laboratory | Senior computational scientist and Monarch principal investigator focused on ontologies, knowledge graphs, phenomics, and biological data integration. | |
| Christina Marie Laukaitis, MD, PhD | Carle Illinois College of Medicine and Carle Health | Physician-geneticist leading hEDS genetics, omics, and tissue-mechanism research. | |
| Jennifer G. Andrews, PhD, MBA *(confirmed)* | University of Arizona College of Medicine, Tucson | Translational researcher in genetic and pediatric-onset conditions, autonomic function, and lifelong care. | |
| Lucas Chatham, BBA, CPT, CAFS *(confirmed)* | Daybreaker Health | Scientific Lead. Expertise in LLM systems infrastructure, products, data systems, applied biomechanics, and lived hEDS. | [chathamworks@gmail.com](mailto:chathamworks@gmail.com) |
| Megan L. Pearson, BS | University of Colorado Anschutz Medical Campus, Department of Dermatology and Gates Institute | PhD student investigating hEDS subtypes and their genetic and epigenetic drivers through electronic health record analysis and patient-derived skin models. | [megan.pearson@cuanschutz.edu](mailto:megan.pearson@cuanschutz.edu) |
| Melissa A. Haendel, PhD *(confirmed)* | UNC School of Medicine, TISLab | Director and professor advancing rare-disease diagnostics and care through semantic engineering and data integration. | |
| Nicolas A. Matentzoglu, PhD | Semanticly and the Monarch Initiative | Semantic engineer specializing in biomedical ontologies, mappings, standards, and knowledge graphs. | [nicolas.matentzoglu@gmail.com](mailto:nicolas.matentzoglu@gmail.com) |
| Phillip Andrew Richmond, PhD | UNC School of Medicine, TISLab | Associate professor and bioinformatics lead focused on rare-disease phenotyping, EHR integration, and genomic diagnosis. | |
| Rohith Jesudas, MD | St. Jude Children's Research Hospital | Pediatric hematologist specializing in hemostasis and thrombosis, with an interest in rare bleeding disorders. | |
| Russell A. Norris, PhD | Medical University of South Carolina | Professor studying cardiovascular biology, connective-tissue genetics, and mechanisms of tissue development and repair. | |

Members are listed alphabetically. Participation is confirmed only where marked *(confirmed)*; all other participation is pending confirmation.

Team members retain their institutional affiliations. Those institutions are not represented as project sponsors unless separately confirmed.

## Governance and safety

- Use only public, consented, deidentified, or otherwise governance-approved data.
- Obtain required institutional review board or ethics approval before new human-subjects data collection.
- Keep restricted patient-level data out of this public repository.
- Publish only data and derived outputs permitted by consent, agreements, and applicable law.
- Require evidence, uncertainty, provenance, and expert review for research-facing claims.
- Treat the Navigator as a research prototype, not a medical device or substitute for clinical judgment.

## Evidence basis

- [Anthropic rare disease research grants](https://www.anthropic.com/news/rare-disease-research-grants)
- [NIH MedlinePlus: Ehlers-Danlos syndrome](https://medlineplus.gov/genetics/condition/ehlers-danlos-syndrome/)
- [GeneReviews: Hypermobile Ehlers-Danlos Syndrome](https://www.ncbi.nlm.nih.gov/books/NBK1279/)
- [Diagnosed prevalence of EDS and HSD in Wales](https://pubmed.ncbi.nlm.nih.gov/31685485/)
- [The diagnostic journey in adults with hEDS and HSD](https://pubmed.ncbi.nlm.nih.gov/34739411/)
- [EDS gastrointestinal surgery and complications](https://pubmed.ncbi.nlm.nih.gov/23095510/)
- [Monarch Initiative](https://monarchinitiative.org/)

## Repository documents

- [Full project plan](PROJECT_PLAN.md)
- [Anthropic application draft](ANTHROPIC_APPLICATION.md)

## Open decisions

- Confirm final team roles.
- Confirm the pilot population and whether hEDS alone or hEDS plus HSD is in scope.
- Confirm available datasets, consent terms, ethics pathway, and sharing permissions.
- Confirm quantitative targets after data-access review.
- Confirm participation for every member not yet marked confirmed.
- Select a content and data license after governance review.
