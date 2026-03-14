# Collaborative Ontology Engineering for Parkinson's Disease Monitoring using LLMs

This repository contains the supplementary material, experimental data, and generated ontologies for the research paper:  
**"Leveraging LLMs for Collaborative Ontology Engineering in Parkinson Disease Monitoring and Alerting"**.

---

## 📝 Abstract
This study investigates the integration of Large Language Models (LLMs) into ontology engineering (OE) processes for the clinical domain of Parkinson's Disease (PD) monitoring. We evaluate and compare four distinct methodologies—ranging from fully autonomous to human-in-the-loop collaborative frameworks—to identify the most effective approach for developing high-quality, clinically relevant ontologies. 

Our findings highlight that while LLMs excel at initial knowledge drafting, human-centric collaborative methodologies like **X-HCOME** and **SimX-HCOME+** are essential for ensuring structural integrity, logical consistency, and domain accuracy.

---

## 🔬 Research Methodologies
We investigated four primary ontology engineering approaches:

1.  **One-Shot (OS) Prompting**: Fully autonomous ontology generation from a single, high-level prompt.
2.  **Decomposed Sequential Prompting (DSP)**: A step-by-step (sequential) prompting method designed to guide the LLM through complex modeling tasks by breaking them into smaller, manageable components.
3.  **X-HCOME**: A human-LLM collaborative environment for evolving and refining ontologies through iterative interaction and consensus.
4.  **SimX-HCOME+**: A simulated, human-supervised environment for LLM-led ontology development, focusing on expert-driven refinement and validation.

---

## ⚙️ Experimental Setup

### Ontology Construction & Refinement
* **Initial Drafting**: LLMs generate an initial ontology based on clinical data and specific methodological prompts.
* **Human-in-the-Loop**: Expert reviewers compare and refine the generated models against the **WEAR4PDMOVE** gold standard ontology.
* **Iterative Evolution**: Continuous refinement to ensure clinical comprehensiveness and syntactical accuracy.

### Validation and Evaluation
* **Tools**: OOPS! (Ontology Pitfall Scanner) and Protégé for logical correctness and pitfall detection.
* **Metrics**: Precision, Recall, and F1-Score for structural comparison against the reference ontology.
* **Expert Review**: Qualitative analysis of "false positives" to identify valid domain extensions missed by the static gold standard.

---

## 📁 Directory Structure and Files

### `/Decomposed_Sequential_Prompting`
Contains ontologies generated using the **DSP** methodology across various models:
* `Bard_DSP_19.ttl`: Generated using Bard.
* `GPT3.5_DSP_23.ttl`: Generated using GPT-3.5.
* `GPT4_DSP_17.ttl`: Generated using GPT-4.
* `Llama2_DSP_21.ttl`: Generated using Llama2.

### `/One_Shot_Prompt`
Contains fully autonomous single-prompt outputs for baseline comparison:
* `Bard_one_shot_18.ttl`, `GPT3.5_one_shot_22.ttl`, `GPT4_one_shot_16.ttl`, `Llama2_one_shot_20.ttl`.

### `/Metrics`
Excel workbooks containing the detailed structural evaluation, X-HCOME results, and comparative data against the **WEAR4PDMOVE** reference ontology.

### `/SimXHCOME+`
Comprehensive documentation and outputs for the SimXHCOME+ methodology:
* `REPORT_on_SimXHCOME+.docx`: Detailed methodological report.
* `SimXHCOME+-[Model]-PD.ttl`: Refined ontologies for Claude, Gemini, GPT-3.5, and GPT-4.
* `SWRL_PD_SimXHCOME+.docx`: Documentation for Semantic Web Rule Language (SWRL) rules and logic.

### `/XHCOME`
Iterative refinement files, prompt logs, and generated ontologies specifically for the X-HCOME methodology.

---

## 🔗 Supplementary Material
* **Journal**: Submitted to *Applied Sciences (MDPI)*.
* **GitHub Repository**: [https://github.com/GiorgosBouh/Ontologies_by_LLMst](https://github.com/GiorgosBouh/Ontologies_by_LLMst)