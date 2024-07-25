# Ontologies and files Repository
# Paper: Ontology Engineering Methodologies for Parkinson's Disease Monitoring and Alerting using Large Language Models

## Abstract
This project demonstrates the integration of Large Language Models (LLMs) in ontology engineering for Parkinson's Disease (PD) monitoring and alerting. The proposed collaborative ontology engineer methodologies (human and LLM), provides robusts approaches to developing quality ontologies, showcasing notable time efficiency and comprehensive knowledge representation.

## Introduction
Ontology engineering is crucial for structuring knowledge in various domains, including healthcare. This project focuses on leveraging LLMs to improve the efficiency and accuracy of ontology development for PD monitoring and alerting.

## Related Work
Previous studies have explored automatic ontology extraction and alignment using various models. However, the integration of human expertise with LLMs in ontology engineering remains underexplored, motivating this research.

## Research Methodology
### Experiment Phases
1. **Phase 1**: LLMs independently construct an ontology from scratch.
2. **Phase 2-4**: Hybrid approaches where human experts and LLMs collaborate to refine the ontology.

### Techniques Used
- **One Shot (OS)**: Single prompt approach.
- **Chain of Thought (CoT)**: Sequential prompting method.
- **H-HCOME**: Collaborative enviroment (Human and LLM) for OEM
- **Expert Review of the X-HCOME**: Collaborative enviroment (Human and LLM) for OEM
- **SimX-HCOME+**: Simulated environment for human-supervised LLM-led ontology development.

## Experimental Setup
### Ontology Construction
1. LLM constructs the ontology using provided data.
2. Human compares and refines the ontology against a gold standard.
3. Repeat the process to ensure comprehensiveness and accuracy.

### Validation and Evaluation
- Tools: OOPS!, Protégé
- Metrics: Precision, Recall, F-1 Score

## Results
### Experiments 1 and 2
- LLM performance and X-HCOME  in class definition consistency and syntactical correctness.

### Experiment 3
- Expert review and false positive analysis.

### Experiment 4
- Evaluation of SimX-HCOME+ methodology.

## Discussion
### Human-LLM Collaboration
- Enhanced structural integrity and enriched knowledge representation through human-LLM collaboration.
- Future potential for advancing ontology engineering.

## Conclusion
The X-HCOME and SimX-HCOME+ methodologies demonstrate the effectiveness of integrating human expertise with LLM capabilities in ontology engineering, particularly for PD monitoring and alerting.


## Supplementary Material
- [GitHub Repository](https://github.com/GiorgosBouh/Ontologies_by_LLMst): Access to code, data, and results.


## Directories and Files

### Chain_of_Thought_or_Few_Shot_Prompts
- **Bard_chain_of_thought_19.ttl**: A Turtle (TTL) file containing ontology data generated using the Chain of Thought method with the Bard model.
- **GPT3.5_chain_of_thought_23.ttl**: A TTL file containing ontology data generated using the Chain of Thought method with the GPT-3.5 model.
- **GPT4_chain_of_thought_17.ttl**: A TTL file containing ontology data generated using the Chain of Thought method with the GPT-4 model.
- **Llama2_chain_of_thought_21.ttl**: A TTL file containing ontology data generated using the Chain of Thought method with the Llama2 model.

### One_Shot_Prompt
- **Bard_one_shot_18.ttl**: A TTL file containing ontology data generated using the One Shot prompt method with the Bard model.
- **GPT3.5_one_shot_22.ttl**: A TTL file containing ontology data generated using the One Shot prompt method with the GPT-3.5 model.
- **GPT4_one_shot_16.ttl**: A TTL file containing ontology data generated using the One Shot prompt method with the GPT-4 model.
- **Llama2_one_shot_20.ttl**: A TTL file containing ontology data generated using the One Shot prompt method with the Llama2 model.

### Metrics
- Excel documents detailing the metrics used for evaluating the methodologies, X-HCOME, Expert review and X-HCOME. Also the file contains the gold ontology (WEAR4PDMOVE)
### SimXHCOME+
- **REPORT on SimXHCOME+.docx**: A detailed report on the SimXHCOME+ methodology.
- **SimXHCOME+-CLAUDE-PD.ttl**: A TTL file containing ontology data generated using the SimXHCOME+ methodology with the Claude model.
- **SimXHCOME+-GEMINI-PD.ttl**: A TTL file containing ontology data generated using the SimXHCOME+ methodology with the Gemini model.
- **SimXHCOME+-GPT3.5-PD.ttl**: A TTL file containing ontology data generated using the SimXHCOME+ methodology with the GPT-3.5 model.
- **SimXHCOME+-GPT4-PD.ttl**: A TTL file containing ontology data generated using the SimXHCOME+ methodology with the GPT-4 model.
- **SWRL PD_SimXHCOME+.docx**: A Word document related to the Semantic Web Rule Language (SWRL) rules used in the SimXHCOME+ methodology.
- **Metrics for Sim-X-HCOME+.docx**: A Word document detailing the metrics used for evaluating the Sim-X-HCOME+ methodology.

### XHCOME
- Files related to the X-HCOME generated ontologies and the prompts for this OEM


