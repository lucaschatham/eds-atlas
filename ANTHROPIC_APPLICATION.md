# Anthropic AI for Science Application Draft

## Applicant information

### Name of primary contact

Lucas Chatham

### Name of organization or research institution

Independent Ehlers-Danlos Research Collaborative

### Position or title at organization

Project Lead

### Website of organization or research group, Google Scholar, or GitHub

[Independent Ehlers-Danlos Research Collaborative](https://github.com/lucaschatham/independent-eds-research-collaborative)

### Where did you hear about this program?

[Anthropic's rare disease research grants announcement](https://www.anthropic.com/news/rare-disease-research-grants)

## Project information

### Project title

Mapping EDS Heterogeneity: A Research-Ready Dataset and Explainable Evidence Navigator

### What rare disease or disease class does this project focus on?

Ehlers-Danlos syndromes (EDS), with an initial pilot focused on hypermobile Ehlers-Danlos syndrome (hEDS) and related hypermobility spectrum disorders.

### Which Organization ID should receive the credits?

**TBD: insert the Anthropic Organization ID before submission.**

## Research team

### Team description

The Independent Ehlers-Danlos Research Collaborative brings together EDS research, clinical genetics, hematology, translational science, patient perspective, data engineering, and AI product development. Lucas Chatham, project and application lead, will direct the Claude workflow, data integration, software development, evaluation, and coordination; he contributes machine-learning, autonomous-systems, health-data, biomechanics, and lived EDS experience. Christina Marie Laukaitis, Clinical Associate Professor, Research at Carle Illinois College of Medicine, contributes medical-genetics expertise in hEDS, omics, and tissue mechanisms. Jennifer G. Andrews, PhD, MBA, Associate Professor and Research Director in Genetics and Developmental Pediatrics at the University of Arizona, contributes translational expertise in genetic and pediatric conditions, patient-reported data, EDS symptoms, and bleeding. Rohith Jesudas, MD, Assistant Member in Hematology at St. Jude Children's Research Hospital, contributes expertise in hemostasis, thrombosis, and chronic hematologic disease, including the bleeding and surgical-readiness pilot. Russell Norris, PhD, Professor of Regenerative Medicine and Cell Biology at the Medical University of South Carolina, is pending confirmation and would advise on connective-tissue and hEDS mechanisms. Scientific experts will define questions, validate mappings and claims, and review outputs; Lucas will implement and operate the AI workflow.

Team members retain their institutional affiliations. Their institutions are not represented as project sponsors unless separately confirmed.

### Key team members who will use Claude

The five team members named above will use or review Claude outputs according to their assigned roles. Russell Norris's participation remains pending confirmation.

### Academic and professional profiles

- [Lucas Chatham](https://www.linkedin.com/in/lucaschatham)
- [Christina Marie Laukaitis](https://medicine.illinois.edu/about/directory/faculty/profile/laukaiti)
- [Jennifer G. Andrews](https://profiles.arizona.edu/person/jga)
- [Rohith Jesudas](https://www.stjude.org/people/j/rohith-jesudas.html)
- [Russell Norris](https://profiles.musc.edu/Russell.Norris/), pending confirmation

## Research proposal

### Project description

Scientific question: Can harmonized clinical, patient-reported, and literature-derived phenotype data reveal reproducible symptom clusters and mechanistic relationships across Ehlers-Danlos syndromes, and can those relationships support an explainable, evidence-grounded research navigator?

We will begin with a bounded pilot focused on hypermobile EDS, including bleeding and surgical readiness as an initial use case. Subject to data access, consent, and required institutional review board or ethics approval, we will integrate existing EDS datasets and self-management studies with new consented, deidentified patient-reported symptoms, diagnoses, interventions, and outcomes. If new data collection cannot be approved during the project period, the pilot will use existing deidentified and public data and produce a governed intake schema for future collection.

Additional resources will include peer-reviewed literature, case reports, Human Phenotype Ontology (HPO), Mondo, the Monarch Knowledge Graph, DisMech, OMIM, and Orphanet. Claude-assisted pipelines will extract and normalize phenotypes, map terms to shared ontologies, deduplicate records, reconcile conflicting evidence, preserve provenance, and propose phenotype clusters and mechanistic hypotheses. Domain experts will review all research-facing claims and a stratified sample of extracted data.

The project has two integrated deliverables. First, a research-ready EDS dataset with a documented schema, data dictionary, provenance, quality checks, and sharing rules. Public outputs will include all governance-permitted deidentified or aggregate data, ontology mappings, and expert-reviewed hypotheses contributed through the Monarch ecosystem. Second, a Personalized EDS Navigator research prototype that accepts structured symptoms, history, diagnostic stage, and prior interventions, then returns explainable phenotype-to-disease pathways, a differential for clinician review, and evidence-linked management hypotheses with rationale, uncertainty, and safety guidance. It will not diagnose or prescribe.

Timeline: Month 1, finalize scope, governance, schema, and evaluation plan. Months 2 and 3, ingest, harmonize, and quality-check data. Months 3 and 4, analyze phenotype clusters, test hypotheses, and evaluate Claude. Months 4 and 5, build the Navigator. Month 6, complete expert and patient testing, error analysis, documentation, and public release.

### How will Claude be used?

Claude will ingest approved literature, case reports, registry schemas, ontology mappings, and deidentified patient records to extract and normalize phenotypes, map terms to HPO and Mondo, reconcile duplicates and conflicts, build provenance-linked summaries, propose phenotype-cluster and mechanism hypotheses, and generate explainable Navigator responses; every extracted fact and hypothesis will retain its source, confidence, and expert-review status. Claude Code will implement the ingestion, validation, analysis, evaluation, and web-application pipelines, while domain experts review a stratified sample and every research-facing claim, replacing repeated manual reading and coding across heterogeneous sources with an auditable human-in-the-loop workflow that can process and test substantially more evidence within six months.

## Impact assessment

### Potential scientific impact

Using a global population of 8.2 billion, the conventional minimum prevalence of all EDS types, at least 1 in 5,000, implies roughly 1.6 million affected people worldwide; newer health-record evidence cited by GeneReviews places diagnosed hypermobile EDS near 1 in 3,100, equivalent to 2.6 million people if generalized globally, while the broader hEDS and hypermobility spectrum disorder population may approach 1 in 500, or 16.4 million people, revealing a vast population whose pain, instability, fatigue, gastrointestinal and autonomic symptoms, bruising, bleeding, and poor healing may remain unrecognized or treated in isolation. This project aims to build a public, privacy-preserving system that converts this fragmented evidence into computable, patient-specific phenotypes, discovers mechanistically distinct subgroups, identifies people whose records suggest EDS, and gives researchers and clinicians evidence-linked pathways for diagnosis, symptom management, and individualized bleeding and perioperative risk, with the potential to shorten years of diagnostic delay, prevent avoidable surgical harm, enable appropriate procedures where poor risk stratification currently creates uncertainty, and move millions of people from trial-and-error care toward earlier, safer, measurable relief.

Evidence basis: [UN global population](https://www.un.org/en/desa/WUP-2025), [NIH prevalence](https://medlineplus.gov/genetics/condition/ehlers-danlos-syndrome/), [GeneReviews hEDS](https://www.ncbi.nlm.nih.gov/books/NBK1279/), and [Wales population study](https://pubmed.ncbi.nlm.nih.gov/31685485/).

### How will success using Claude be measured?

Within six months, Claude must harmonize at least three independent EDS data sources and 2,000 governance-approved patient records into one provenance-complete schema; process at least ten times the evidence volume of the manual baseline at 90% or greater expert-validated extraction and ontology-mapping accuracy; identify at least five expert-endorsed phenotype clusters or mechanistic hypotheses, with at least two advanced into follow-on studies; and pass a blinded evaluation of at least 100 cases with 90% or greater capture of documented diagnostic, bleeding, wound-healing, and perioperative risk factors and no unflagged unsupported high-risk guidance. Success also requires testing with at least 50 people with EDS and 20 clinicians or researchers, with at least 80% reporting that the Navigator surfaces an expert-validated risk, management question, or next step not readily visible in the source record, while publicly releasing the governance-permitted dataset, evaluation set, failure analysis, and system components needed to demonstrate a credible path from the six-month pilot to population-scale use.

## Resource requirements

### Requested credits and expected impact

We request the maximum award of **$50,000 in credits**, allocated as follows:

- **$35,000 in Claude Science and API credits:** literature and case-report analysis, ontology mapping, structured extraction, data harmonization, hypothesis generation, repeated evaluation, and expert-reviewed Navigator inference.
- **$15,000 in Claude Code credits:** ingestion pipelines, data-quality tooling, evaluation harnesses, analysis workflows, and web-prototype development.

The full award will support repeated expert-reviewed runs across heterogeneous sources, systematic error analysis, and model comparisons. This makes it possible to produce validated, reusable outputs rather than a single untested proof of concept.

## Biosecurity assessment

### Does the research involve pathogen research, virology, drug resistance, toxicology, or synthetic biology?

None of the above.

### Biosecurity safeguards

Not applicable. The project does not involve pathogens, virology, drug-resistance studies, toxicology, or synthetic biology.

## Additional information

### Is there anything else the review committee should know?

This is a patient-informed, expert-supervised basic-science project designed for public benefit. We will contribute governance-compatible outputs to the Monarch ecosystem, report negative and failure results, restrict Claude inputs to consented, deidentified, approved data, and keep the Navigator explicitly non-diagnostic and non-prescriptive.

The collaboration must confirm a scientific lead, data-access pathway, ethics pathway, final team participation, and the Anthropic Organization ID before submission.

### Terms of Service

I agree.
