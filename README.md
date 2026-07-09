# llmops-slr-appendix
Appendix tables for the paper: Exploring Large Language Model Operations (LLMOps) and Related Challenges in Production Environments: A Systematic Literature Review


## Appendix A: Quality Assessment Template for Included Studies

**Table 13: Quality Assessment Template for Included Studies**

| QA ID | Target Criterion | Justification (Why this matters) | LOW Risk (High Quality) [Score: 1] | HIGH Risk (Low Quality) [Score: 0] | UNCLEAR (Risk) [Score: 0.5] |
|---|---|---|---|---|---|
| QA1 | Is the operational context clearly defined (e.g., production scale, model size)? | Ensures the study is relevant to real-world "Production Environments" rather than just academic toy examples. | The study explicitly details the production environment, scale, infrastructure, and specific models used. | The study uses purely theoretical scenarios, toy datasets, or local execution with no mention of production scale. | The study mentions a production environment but lacks specific details on the actual scale, constraints, or models used. |
| QA2 | Is the proposed LLMOps framework, architecture, or tool adequately described? | Necessary to accurately map, extract, and compare architectures to answer RQ2 and RQ3. | Comprehensive architectural details, workflows, or code repositories are provided, making the system clear. | The framework is only mentioned conceptually or at a marketing level without technical or architectural depth. | The framework is described at a high level, but specific technical integrations or lifecycle stages are vague. |
| QA3 | Are the research findings based on empirical evidence? | Ensures the study's conclusions are grounded in actual data, real-world deployments, or structured experiments rather than purely hypothetical scenarios. | Findings are explicitly supported by real-world deployments, quantitative experiments, case studies, or structured qualitative data. | Findings are purely speculative, assumed, or based solely on the authors' opinions without any supporting data. | It is difficult to distinguish whether the reported findings were actually observed in practice or merely hypothesized, or the data methodology is vague. |
| QA4 | Does the study have relevance with any research questions? | Reduces bias by prioritizing papers with the most actionable data for the research questions. | Targets at least one of the research questions directly and offers significant actionable data. | Meets inclusion criteria but offers minimal actionable data for the RQs. | Relevant to the broader field of LLMOps but is not the core focus of a specific RQ. |
| QA5 | Are the threats of validity of the research described? | Evaluates the authors' transparency regarding the limitations, potential biases, and generalizability of their study. | Threats to validity along with mitigation actions are discussed for the findings. | There is no discussion of threats to validity of the study findings. | Threats to validity of the findings of the study are discussed without mitigation actions. |
| QA6 | Is the aim of the study discussed? | Ensures the paper has a clear purpose and research objective, providing necessary context for why the study was conducted. | The aim of the study is explicitly discussed. | There are no mentions of the study's aim. | The aim can be inferred but is not explicitly stated. |


## Appendix B: Data Extraction Properties for LLMOps SLR

**Table 14: Data Extraction Properties for LLMOps SLR**

| ID | Target RQ | Property Name | Description / Focus Area |
|---|---|---|---|
| DP1 | NA | Publication Identifier | Unique study identifier for tracking and cross-referencing throughout the review. |
| DP2 | NA | Publication Year | Publication year (2017–2026) used to map evolution of LLMOps literature over time. |
| DP3 | NA | Geography | Country or region of origin used to identify global and regional evidence patterns. |
| DP4 | NA | Publication Source | Venue type (journal/conference/workshop) for assessing publication context. |
| DP5 | NA | Research Method | Reported empirical method (e.g., case study, survey, experiment). |
| DP6 | NA | Artifact Readiness | Readiness level of contribution: theoretical artifact, prototype, or production implementation. |
| DP7 | RQ1 | LLMOps Definition | Extracted definitions and direct terminology statements for conceptual synthesis. |
| DP8 | RQ1 | Scope | Statements distinguishing LLMOps from other operational paradigms. |
| DP9 | RQ2 | Lifecycle Stages | Coverage of design, development, and operations phases in the LLM lifecycle. |
| DP10 | RQ2 | Frameworks and Architecture | Architectural or pipeline patterns (e.g., RAG, agentic workflows). |
| DP11 | RQ2 | Platforms and Tools | Tooling and platform stack used in implementation (e.g., LangChain, Pinecone). |
| DP15 | RQ4 | Technical Challenges | Implementation and operational technical challenges (e.g., hallucination control). |
| DP16 | RQ4 | Regulatory Challenges | Compliance, governance, and policy constraints (e.g., GDPR-related requirements). |
| DP17 | NA | Performance Metrics | Evaluation indicators used by studies (e.g., perplexity, latency, cost). |
| DP18 | NA | Aim of the study | Aim of the study in context of LLMOps. Captures the core research objective to understand the primary focus and intended contribution of the paper (e.g., "To propose a scalable framework for RAG deployment"). |
| DP19 | NA | Abstract | Direction, goal and context of LLMOps. Captures the direction and goal of the study and how it contributes to the research. Example abstract quote from the paper. |
