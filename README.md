# Awesome-Medical-AI-Healthcare-LLMS

## Top Medical AI & Healthcare LLMs Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Clinical Documentation, Medical Reasoning & Healthcare AI*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Medical AI & Healthcare LLMs**. These tools assist clinicians with ambient documentation, clinical decision support, medical question answering, and patient interaction using large language models and speech recognition.

**Examples** include Hippocratic AI, Glass Health, Ambience Healthcare, Nabla Copilot, Abridge, Heidi Health, Nuance DAX Copilot, Suki AI, DeepScribe, Corti, and maziyarpanahi/openmed (the category leaders and notable projects).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, medical LLM fine-tuning, and clinical NLP — ideal for researchers, health systems, and developers building transparent, auditable healthcare AI without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Hippocratic AI](https://hippocraticai.com/)**  
  Patient-facing AI agents built on the Polaris model family, benchmarked for clinical safety and used for outreach, triage, and care coordination [citation:1].

- **[Glass Health](https://glass.health/)**  
  Clinical decision support API providing evidence-grounded reasoning, differential diagnosis, and treatment plan synthesis with inline citations [citation:2][citation:14].

- **[Ambience Healthcare](https://www.ambiencehealthcare.com/)**  
  Enterprise clinical intelligence platform spanning ambient documentation, revenue integrity, and inpatient care orchestration, deployed at major academic medical centers [citation:3][citation:15].

- **[Nabla Copilot](https://www.nabla.com/)**  
  Ambient AI scribe that demonstrated a statistically significant reduction in time-in-note in a randomized trial versus control [citation:4].

- **[Abridge](https://www.abridge.com/)**  
  Unified healthcare intelligence platform linking clinical conversations to structured documentation, decision support, and payment alignment workflows [citation:5].

- **[Heidi Health](https://www.heidihealth.com/)**  
  Highly customizable AI medical scribe operating ambiently across diverse clinical settings, with over 1 million weekly consultations reported [citation:6].

- **[Nuance DAX Copilot](https://www.microsoft.com/en-us/health-solutions/clinical-workflow/dax-copilot)**  
  Microsoft's ambient clinical documentation solution integrated with EHR workflows, capturing patient encounters and generating structured notes [citation:7].

- **[Suki AI](https://www.suki.ai/)**  
  Voice-enabled clinical assistant with an "Ask" feature combining patient chart data and UpToDate evidence for point-of-care information retrieval [citation:8].

- **[DeepScribe](https://www.deepscribe.ai/)**  
  Ambient AI specialized for oncology workflows, with integrations into oncology-specific EMR systems and reported improvements in diagnosis code specificity [citation:9].

- **[Corti](https://www.corti.ai/)**  
  API-first healthcare AI platform offering real-time ambient scribing, medical coding (ICD-10/CPT), and conversational analysis for clinical documentation [citation:10].

- **[maziyarpanahi/openmed](https://github.com/maziyarpanahi/openmed)**  
  Open-source medical LLM and inference framework for healthcare applications, providing accessible model weights and deployment tooling.

## Open-Source GitHub Projects

- **[HuatuoGPT-3](https://github.com/FreedomIntelligence/HuatuoGPT-3)**  
  Medical LLM series (7B/8B/32B) trained via RL-only domain adaptation from base models, supporting thinking-mode reasoning for clinical questions [citation:11].

- **[OpenMed (maziyarpanahi/openmed)**  
  Open medical LLM ecosystem providing model weights, inference scripts, and tooling for self-hosted healthcare AI.

- **[DocuScribe AI](https://github.com/abh2050/docu_scribe_ai)**  
  Agent-based clinical documentation pipeline that transcribes conversations, extracts medical concepts, generates SOAP notes, and exports FHIR-compatible data [citation:12].

- **[Open Health NLP (OHNLP)](https://github.com/OHNLP)**  
  Suite of clinical natural language processing tools from Mayo Clinic for entity extraction, assertion classification, and temporal reasoning on clinical text.

- **[MedCAT](https://github.com/CogStack/MedCAT)**  
  Medical Concept Annotation Tool for extracting and linking clinical concepts from unstructured text to SNOMED-CT and UMLS ontologies.

- **[CLAMP](https://github.com/OHNLP/CLAMP)**  
  Clinical Language Annotation, Modeling, and Processing toolkit for building custom clinical NLP pipelines.

- **[cTAKES](https://github.com/apache/ctakes)**  
  Apache clinical Text Analysis and Knowledge Extraction System for information extraction from electronic medical records.

### Additional Strong Open-Source Options

- **[MetaMapLite](https://github.com/lhncbc/metamaplite)** — NLM's lightweight concept mapping tool for biomedical text.
- **[NegBio](https://github.com/ncbi-nlp/NegBio)** — Negation and uncertainty detection for biomedical text, useful in clinical note processing.
- **[MedSpaCy](https://github.com/medspacy/medspacy)** — Clinical NLP library built on spaCy with rules and components tailored for medical text.
- **[FHIR-PYrate](https://github.com/UMEssen/fhir-pyre)** — Python library for querying and analyzing FHIR healthcare data, useful for building clinical AI pipelines.
- **Community medical LLM fine-tunes** — Models such as Meditron, BioMistral, and OpenBioLLM available on Hugging Face for research and self-hosted deployment.

**Frameworks for building custom systems**: Combine **HuatuoGPT-3** or **OpenMed** for medical reasoning, **MedCAT** or **cTAKES** for clinical concept extraction, **DocuScribe AI** as a documentation pipeline reference, and **FHIR-PYrate** for healthcare data integration. Deploy with **vLLM** or **SGLang** for efficient inference.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Medical AI tools must comply with healthcare regulations (HIPAA, GDPR, FDA guidance, etc.) and require clinical validation before patient-facing use.
- Self-hosted open-source solutions require proper security hardening, BAA agreements where applicable, and rigorous evaluation for clinical accuracy and safety.

---

**Made for clinical informaticists, healthcare AI researchers, physician builders, and health system technologists.**  
Let's make medical AI more open, auditable, and clinically trustworthy.
