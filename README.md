<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Collaborative Ontology Engineering for PD</title>
    <style>
        body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; line-height: 1.6; color: #24292e; max-width: 900px; margin: auto; padding: 45px; }
        h1 { border-bottom: 1px solid #eaecef; padding-bottom: .3em; color: #0366d6; }
        h2 { border-bottom: 1px solid #eaecef; padding-bottom: .3em; margin-top: 24px; }
        h3 { margin-top: 20px; }
        code { background-color: rgba(27,31,35,.05); border-radius: 3px; padding: .2em .4em; font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace; }
        ul { padding-left: 2em; }
        .directory { font-weight: bold; color: #005cc5; }
        .file-list { background: #f6f8fa; padding: 15px; border-radius: 6px; border: 1px solid #d1d5da; }
        hr { height: .25em; padding: 0; margin: 24px 0; background-color: #e1e4e8; border: 0; }
    </style>
</head>
<body>

    <h1>Collaborative Ontology Engineering for Parkinson's Disease Monitoring using LLMs</h1>
    <p>This repository contains the supplementary material, ontologies, and experimental data for the paper:<br>
    <strong>"Leveraging LLMs for Collaborative Ontology Engineering in Parkinson Disease Monitoring and Alerting"</strong>.</p>

    <h2>Abstract</h2>
    <p>This project investigates the integration of Large Language Models (LLMs) into ontology engineering (OE) processes for the clinical domain of Parkinson's Disease (PD) monitoring. We evaluate and compare four distinct methodologies—ranging from fully autonomous to human-in-the-loop collaborative frameworks—to identify the most effective approach for developing high-quality, clinically relevant ontologies. Our findings highlight that while LLMs excel at initial knowledge drafting, human-centric collaborative methodologies like <strong>X-HCOME</strong> and <strong>SimX-HCOME+</strong> are essential for structural integrity and domain accuracy.</p>

    <h2>Research Methodologies</h2>
    <ul>
        <li><strong>One-Shot (OS) Prompting</strong>: Fully autonomous ontology generation from a single high-level prompt.</li>
        <li><strong>Decomposed Sequential Prompting (DSP)</strong>: A step-by-step (sequential) prompting method designed to guide the LLM through complex modeling tasks by breaking them into smaller components.</li>
        <li><strong>X-HCOME</strong>: A human-LLM collaborative environment for evolving and refining ontologies through iterative interaction.</li>
        <li><strong>SimX-HCOME+</strong>: A simulated, human-supervised environment for LLM-led ontology development, focusing on expert-driven refinement and validation.</li>
    </ul>

    <h2>Experimental Setup</h2>
    <h3>Ontology Construction & Refinement</h3>
    <ul>
        <li><strong>Initial Drafting</strong>: LLMs generate an initial ontology based on clinical data and specific methodological prompts.</li>
        <li><strong>Human-in-the-Loop</strong>: Expert reviewers compare and refine the generated models against the <strong>WEAR4PDMOVE</strong> gold standard ontology.</li>
        <li><strong>Iterative Evolution</strong>: Continuous refinement to ensure clinical comprehensiveness, logical consistency, and syntactical accuracy.</li>
    </ul>

    <h3>Validation and Evaluation</h3>
    <ul>
        <li><strong>Tools</strong>: OOPS! (Ontology Pitfall Scanner) and Protégé for logical correctness.</li>
        <li><strong>Metrics</strong>: Precision, Recall, and F1-Score for structural comparison against the gold standard.</li>
        <li><strong>Expert Review</strong>: Qualitative analysis of "false positives" to recover valid clinical concepts missing from the reference ontology.</li>
    </ul>

    <hr>

    <h2>Directories and Files</h2>

    <h3 class="directory">/Decomposed_Sequential_Prompting</h3>
    <div class="file-list">
        <p>Contains ontologies generated using the <strong>DSP</strong> methodology across various models:</p>
        <ul>
            <li><code>Bard_DSP_19.ttl</code>: Ontology generated using DSP with Bard.</li>
            <li><code>GPT3.5_DSP_23.ttl</code>: Ontology generated using DSP with GPT-3.5.</li>
            <li><code>GPT4_DSP_17.ttl</code>: Ontology generated using DSP with GPT-4.</li>
            <li><code>Llama2_DSP_21.ttl</code>: Ontology generated using DSP with Llama2.</li>
        </ul>
    </div>

    <h3 class="directory">/One_Shot_Prompt</h3>
    <div class="file-list">
        <ul>
            <li><code>Bard_one_shot_18.ttl</code>, <code>GPT3.5_one_shot_22.ttl</code>, <code>GPT4_one_shot_16.ttl</code>, <code>Llama2_one_shot_20.ttl</code>: Fully autonomous single-prompt outputs.</li>
        </ul>
    </div>

    <h3 class="directory">/Metrics</h3>
    <div class="file-list">
        <p>Excel workbooks detailing structural evaluation, X-HCOME results, and the <strong>WEAR4PDMOVE</strong> reference ontology data.</p>
    </div>

    <h3 class="directory">/SimXHCOME+</h3>
    <div class="file-list">
        <ul>
            <li><code>REPORT_on_SimXHCOME+.docx</code>: Comprehensive methodological report.</li>
            <li><code>SimXHCOME+-[Model]-PD.ttl</code>: Ontology files for Claude, Gemini, GPT-3.5, and GPT-4.</li>
            <li><code>SWRL_PD_SimXHCOME+.docx</code>: Documentation for Semantic Web Rule Language (SWRL) rules.</li>
        </ul>
    </div>

    <h3 class="directory">/XHCOME</h3>
    <div class="file-list">
        <p>Iterative refinement files, prompts, and generated ontologies for the X-HCOME methodology.</p>
    </div>

    <hr>

    <h2>Supplementary Material</h2>
    <p>For further information, access the full repository at: 
    <a href="https://github.com/GiorgosBouh/Ontologies_by_LLMst">https://github.com/GiorgosBouh/Ontologies_by_LLMst</a></p>

</body>
</html>