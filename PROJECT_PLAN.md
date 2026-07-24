# Project Plan

## Project

**Mapping EDS Heterogeneity: A Research-Ready Dataset and Explainable Evidence Navigator**

**Applicant group:** Independent Ehlers-Danlos Research Collaborative

**Proposed program:** Anthropic AI for Science, rare disease basic science track

**Duration:** Six months

## Executive summary

Ehlers-Danlos syndromes (EDS) are heterogeneous connective-tissue disorders whose manifestations cross musculoskeletal, cardiovascular, gastrointestinal, autonomic, hematologic, neurologic, and other systems. Fragmented terminology, small datasets, inconsistent phenotype capture, delayed diagnosis, and variable management make it difficult to identify mechanistically meaningful subgroups or translate evidence into patient-specific questions.

This project proposes one integrated research system with two outputs: a research-ready EDS dataset and an explainable Personalized EDS Navigator prototype. The dataset will harmonize approved clinical, patient-reported, registry, and literature-derived evidence into a common phenotype schema. The Navigator will use that evidence to surface phenotype-to-disease pathways, research hypotheses, diagnostic differentials for clinician review, and evidence-linked management and perioperative questions. Every material output will include provenance, uncertainty, and expert-review status.

The initial pilot will focus on hypermobile EDS (hEDS), with bleeding and surgical readiness as a high-value use case. The project will not diagnose, prescribe, or represent the prototype as a clinical device.

## Problem and scale

A conventional minimum prevalence of at least 1 in 5,000 for all EDS types implies roughly 1.6 million affected people worldwide. A health-record estimate near 1 in 3,100 for diagnosed hEDS would imply roughly 2.6 million people if generalized globally. A broader estimate near 1 in 500 for the combined EDS and hypermobility spectrum disorder population would imply roughly 16.4 million people. These figures are methodologically different and are not additive.

The scientific problem is not only missing data. Existing evidence is distributed across clinical records, patient surveys, registries, case reports, research articles, ontologies, and patient communities. Symptoms are often treated in isolation, while subtype and phenotype differences complicate diagnosis, management, and perioperative planning. A system that converts this evidence into interoperable phenotypes could make hidden subgroups, mechanisms, and risk patterns testable.

## Scientific question

Can harmonized clinical, patient-reported, and literature-derived phenotype data reveal reproducible symptom clusters and mechanistic relationships across EDS, and can those relationships support an explainable, evidence-grounded research navigator?

## Working hypotheses

1. Harmonized multisystem phenotypes will reveal reproducible patient clusters that are obscured by broad diagnostic labels.
2. Ontology-aligned data will expose mechanistic relationships among symptoms, comorbidities, pathways, variants, and overlapping disorders.
3. Bleeding, wound-healing, and surgical-readiness features can be represented as phenotype-specific evidence rather than one undifferentiated EDS risk label.
4. Claude-assisted extraction and synthesis can expand evidence coverage while maintaining expert-validated accuracy, provenance, and uncertainty.
5. An explainable Navigator can surface relevant research and care questions that are difficult to identify from fragmented records alone.

## Scope

### Included

- Ehlers-Danlos syndromes, with an initial hEDS pilot.
- HSD where scientifically necessary for differential or comparative analysis.
- Phenotypes, diagnoses, interventions, patient-reported outcomes, comorbidities, bleeding, wound healing, and perioperative considerations.
- Approved structured and unstructured data.
- Basic science hypothesis generation and model evaluation.
- Expert and patient usability testing.

### Excluded from the six-month pilot

- Autonomous diagnosis or treatment selection.
- Prescribing or replacing clinician judgment.
- Prospective interventional clinical trials.
- Use of identifiable or nonapproved patient data.
- Public release of restricted patient-level information.
- Claims of clinical efficacy or symptom improvement without a properly designed study.

## Data sources and resources

Planned sources, subject to permission and governance review, include:

- Existing EDS clinical and research datasets.
- Self-management and patient-experience studies.
- Consented, deidentified patient-reported symptoms, diagnoses, interventions, and outcomes.
- Peer-reviewed literature and case reports.
- Human Phenotype Ontology (HPO).
- Mondo Disease Ontology.
- Monarch Knowledge Graph.
- DisMech.
- OMIM and Orphanet.
- Expert annotations and adjudications.

If approval for new patient-data collection cannot be obtained during the project period, the team will complete the pilot using existing public and deidentified approved data and release a governed intake schema for future collection.

## Deliverable 1: Research-ready EDS dataset

### Required characteristics

- Common, documented phenotype schema.
- Data dictionary and ontology mappings.
- Deduplication and data-quality checks.
- Source-level provenance.
- Consent, access, and sharing classifications.
- Confidence, uncertainty, and expert-review status.
- Exportable formats for analysis and contribution to compatible public resources.

### Intended analyses

- Symptom and comorbidity clustering.
- Phenotype-to-disease matching.
- Mechanistic relationship discovery.
- Comparison of hEDS and overlapping hypermobility phenotypes.
- Bleeding and wound-healing phenotypes.
- Surgical-readiness and perioperative risk-factor capture.
- Model failure and uncertainty analysis.

### Public output

The team will publish the schema, data dictionary, ontology mappings, evaluation materials, expert-reviewed hypotheses, and all deidentified or aggregate data permitted by consent and governance. Restricted patient-level data will remain restricted.

## Deliverable 2: Personalized EDS Navigator research prototype

### Inputs

- Structured symptoms and severity.
- Medical and family history.
- Diagnostic stage and existing diagnoses.
- Prior interventions and reported outcomes.
- Bleeding, bruising, wound-healing, and surgical history.

### Outputs

- Explainable phenotype summary.
- Phenotype-to-disease pathways.
- Differential for qualified clinician review.
- Evidence-linked diagnostic questions.
- Evidence-linked management questions and monitoring considerations.
- Bleeding, wound-healing, and perioperative considerations.
- Rationale, sources, uncertainty, and review status.

### Safety boundaries

- No autonomous diagnosis.
- No prescribing.
- No unsupported high-risk guidance.
- Clear escalation language for urgent or specialist evaluation.
- Expert approval required for research-facing claims.
- Explicit distinction among evidence, hypothesis, uncertainty, and patient report.

## Claude-assisted workflow

1. Ingest approved literature, case reports, registry schemas, and deidentified records.
2. Extract symptoms, diagnoses, interventions, outcomes, variants, mechanisms, and relationships.
3. Normalize terms and map phenotypes to HPO, Mondo, and compatible resources.
4. Deduplicate records and reconcile conflicting or redundant evidence.
5. Attach provenance, confidence, uncertainty, and review status.
6. Generate candidate phenotype clusters and mechanistic hypotheses.
7. Produce structured Navigator responses from approved evidence.
8. Route extractions, hypotheses, and high-risk outputs through human review.
9. Measure performance against a documented manual baseline and blinded cases.
10. Publish governance-permitted data, evaluations, failure analysis, and system components.

Claude Code will support ingestion pipelines, schema validation, data-quality checks, analysis scripts, evaluation harnesses, and the web prototype. Claude Science and API use will support corpus-scale extraction, synthesis, hypothesis generation, and repeated evaluation.

## Human review

Scientific and clinical experts will:

- Define the scientific questions and inclusion criteria.
- Approve the data schema and ontology mappings.
- Review a stratified sample of extractions.
- Adjudicate conflicting evidence.
- Review every research-facing mechanistic claim.
- Review all bleeding, wound-healing, and perioperative outputs.
- Approve materials before public release.

Patient testers will assess clarity, relevance, burden, missing context, and whether outputs surface useful questions without presenting themselves as medical conclusions.

## Work plan

### Month 1: Scope and governance

- Confirm scientific lead and team roles.
- Confirm pilot population.
- Resolve data access and sharing permissions.
- Determine required ethics or institutional review board pathway.
- Finalize schema, source inventory, evaluation design, and manual baseline.

### Months 2 and 3: Data harmonization

- Build ingestion and normalization pipelines.
- Map terminology to HPO, Mondo, and Monarch-compatible structures.
- Deduplicate and quality-check approved data.
- Establish provenance and review workflows.

### Months 3 and 4: Analysis and evaluation

- Analyze symptom and comorbidity clusters.
- Generate candidate mechanisms.
- Develop bleeding and surgical-readiness module.
- Compare Claude-assisted curation with the manual baseline.
- Conduct expert adjudication and error analysis.

### Months 4 and 5: Navigator

- Implement the end-to-end research prototype.
- Integrate the approved dataset and evidence layer.
- Add explanations, citations, uncertainty, and safety constraints.
- Prepare blinded retrospective cases and usability protocols.

### Month 6: Validation and public release

- Complete blinded case evaluation.
- Conduct expert and patient testing.
- Document failures and material expert corrections.
- Release governance-permitted artifacts.
- Select at least two hypotheses for follow-on study.

## Success criteria

The proposed targets are:

- At least three independent EDS data sources.
- At least 2,000 governance-approved patient records.
- At least ten times the evidence volume of a documented manual baseline.
- At least 90% expert-validated phenotype extraction and ontology-mapping accuracy.
- Complete provenance, uncertainty, and review status for research-facing outputs.
- At least five expert-endorsed phenotype clusters or mechanistic hypotheses.
- At least two hypotheses advanced into follow-on studies.
- At least 100 blinded retrospective cases.
- At least 90% capture of documented diagnostic, bleeding, wound-healing, and perioperative risk factors.
- No unflagged unsupported high-risk guidance in the blinded evaluation.
- At least 50 patient testers and 20 clinician or researcher testers.
- At least 80% of testers report that the Navigator surfaces a relevant, expert-validated risk, management question, or next step not readily visible in the source record.

Targets will be revised before execution if confirmed data access, governance, or expert review capacity makes them scientifically invalid or infeasible. Any revision will be documented rather than silently lowering the bar.

## Team and roles

- **Lucas Chatham:** Project lead; AI workflow, data integration, software development, evaluation, coordination, and patient perspective.
- **Christina Marie Laukaitis:** Medical genetics, hEDS, omics, tissue mechanisms, and scientific validation.
- **Jennifer G. Andrews, PhD, MBA:** Translational research, patient-reported data, pediatric and genetic conditions, EDS symptoms, and bleeding.
- **Rohith Jesudas, MD:** Hemostasis, thrombosis, bleeding, and surgical-readiness validation.
- **Russell Norris, PhD:** Connective-tissue and hEDS mechanisms. Participation is pending confirmation.

The collaboration must designate a confirmed scientific lead before submission or award activation. Team members retain their institutional affiliations, and their institutions are not represented as sponsors unless separately confirmed.

## Governance

- Use only public, consented, deidentified, or otherwise approved data.
- Obtain required ethics or institutional review board approval before new human-subjects research.
- Apply data minimization and role-based access.
- Keep protected or restricted data outside the public repository.
- Document source, consent, permitted use, and sharing status.
- Publish only governance-permitted data and derived outputs.
- Maintain an audit trail of model outputs and expert corrections.
- Report negative results and model failures.

## Principal risks and mitigations

| Risk | Mitigation |
| --- | --- |
| Data access is delayed or denied | Use public and existing deidentified data; release a governed future intake schema |
| EDS subtypes are conflated | Record subtype, diagnostic criteria, provenance, and uncertainty; separate hEDS and HSD analyses where possible |
| Model extraction errors | Expert-validate a stratified sample; use blinded evaluation and error analysis |
| Unsupported medical claims | Require citations, uncertainty, review status, safety boundaries, and expert approval |
| Surgical risk is overgeneralized | Model individual phenotype and subtype; distinguish bleeding, tissue fragility, wound healing, and documented history |
| Patient data cannot be public | Release schema, aggregates, mappings, evaluations, and permitted deidentified components only |
| Six-month scope becomes too broad | Keep hEDS and bleeding or surgical readiness as the bounded pilot |

## Long-term direction

If the pilot succeeds, the system can expand across EDS subtypes, institutions, registries, and countries; support prospective natural-history research; improve identification of underrecognized patients; help prioritize symptom-management studies; and provide a reusable architecture for other heterogeneous rare diseases.

## Current open decisions

- Scientific lead.
- Final team participation.
- Pilot inclusion and exclusion criteria.
- Data owners and permissions.
- Ethics and consent pathway.
- Public-data and content licenses.
- Final success targets after source review.
