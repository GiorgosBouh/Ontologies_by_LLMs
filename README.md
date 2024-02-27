This repository contains ontologies files 
# Ontologies Repository

This repository contains ontologies developed through two methodologies: Assisted Autonomy Ontology Development (AAOD) and X-HCOME (Human-Aided LLM Enhancement). These ontologies focus on Parkinson's disease monitoring and alerting, aiming to provide structured representations of knowledge in this domain.

## Methodologies

### Phase 1: Assisted Autonomy Ontology Development (AAOD)

In this phase, four state-of-the-art Large Language Models (LLMs) — GPT3.5, GPT4, Bard, and Llama2 — independently constructed the "Wear4PDmove" ontology. The methodology involved:
- Prompt Engineer: Utilization of One Shot Prompt (OS) and Chain of Thought Prompt (CoT) approaches.
- Prompt Formulation: Design of specialized prompts covering various facets of Parkinson's disease monitoring.
- Prompt Refinement: Iterative refinement of prompts for enhanced relevance and accuracy.
- Ontology Creation: Development of ontology structure within OWL covering symptoms, treatment options, progression stages, and related metrics.
- Ontology Validation: Employing metrics including Precision, Recall, F1-score, OOPS!, Syntactical errors, and Pellet Consistency for accuracy and consistency assessment.

### Phase 2: X-HCOME — Human-Aided LLM Enhancement

Building upon AAOD, the X-HCOME methodology integrated human-defined requirements with LLM-generated frameworks. The steps included:
- Human Task: Outline of ontology's aim, scope, requirements, and Competency Questions (CQs) by domain experts.
- LLM Task: Development of ontology based on human-defined requirements using LLMs, output in OWL format for Protégé.
- Human Task: Formulation of IF-THEN rules targeting ontology classes and object properties by experts.
- LLM Task: Construction of SWRL rules adhering to provided prompts and ontology axioms by LLMs.
- Human-LLM Collaborative Evaluation: Critical comparison and evaluation of LLM-generated ontology and rules against established framework.

## Contents

This repository includes ontologies generated through both methodologies and any associated scripts or resources.

## Usage

The ontologies are provided in ttl format and can be opened and utilized in tools such as Protégé. Feel free to adapt or extend these ontologies to suit your specific requirements in Parkinson's disease monitoring and related research.

## Contributing

Contributions to this repository are welcome. If you have developed ontologies or related resources in the domain of Parkinson's disease monitoring and alerting, feel free to submit a pull request.


## Contact

For inquiries or further information, you can contact [bouhouras@yahoo.com].

