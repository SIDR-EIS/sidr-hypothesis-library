# Chronos Anomaly Protocol v3 (D.R.E.A.M. Filter) – Benchmark Suite

This repository contains  
1. the **Chronos Anomaly Protocol v3 – The D.R.E.A.M. Filter** test specification,  
2. official result transcripts from four large‑language‑model (LLM) runs, and  
3. a peer‑review–style **comparative analysis paper** that evaluates those runs across multiple performance dimensions.

The materials enable researchers to replicate the test, generate new model submissions, and compare results against the published baseline evaluation.

---

## Repository Structure

```

│
├─ protocol/
│   └─ Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md
│
├─ results/
│   ├─ ChatGPT 4o Results - Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md
│   ├─ Claude Sonnet 4 Results - Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md
│   ├─ Gemini 2.5 Pro Results (aistudio) - Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md
│   └─ Grok Web 3.0 Results - Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md
│
├─ analysis/
│   └─ Comparative\_Evaluation\_of\_LLM\_Performance\_on\_Chronos\_Anomaly\_Protocol\_v3.md
│       (the academic paper produced from the four result files)
│
└─ README.md   ← you are here

```

---

## Quick Start

### 1. Review the Protocol
Open `protocol/Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md`.  
It defines:

* **Role hierarchy:** Facilitator + three cognitive layers (Macro/German, Meso/Hungarian, Micro/Mandarin).  
* **Cognitive suppressions:** ID, EGO, SUPEREGO.  
* **Metacontext Tagging Protocol (MTP):** `[Confidence]`, `[Hypothesis]`, `[Data_Integrity]`.  
* **Three‑phase workflow:** re‑analysis, cross‑layer conflict resolution, final SIDR report.

### 2. Run a New Model
1. Prompt the target LLM with the full protocol file content.  
2. Instruct it to **complete all three phases in one pass**.  
3. Capture the entire response and save it to `results/<Model Name> Results - Chronos Anomaly Protocol v3 - The D.R.E.A.M. Filter.md`.

### 3. Update the Analysis (optional manual workflow)
The provided comparative paper covers GPT‑4o, Claude 4 Sonnet, Gemini 2.5 Pro, and Grok Web 3.0.  
To extend the evaluation:

1. Add your new result file under `results/`.  
2. Draft an additional subsection in `analysis/Comparative_Evaluation_...md`:
   * Summarise protocol fidelity, MTP usage, conflict‑resolution behaviour, anomaly classification, and notable strengths/weaknesses.  
   * Update any tables or figures accordingly.  
3. Commit changes for peer review.

---

## Evaluation Criteria (abridged)

| Metric | Description |
|--------|-------------|
| **Protocol Fidelity** | Adherence to all formatting and procedural rules. |
| **Layer Simulation Quality** | Accuracy of each layer’s language, suppression behaviour, and MTP tagging. |
| **Integration & Conflict Resolution** | Depth of cross‑layer dialogue; ability to recognise or resolve deadlocks. |
| **Interpretive Accuracy** | Correct identification of ATAMIRI‑corrupted data and proper anomaly classification. |
| **Coherence & Consistency** | Logical soundness across all phases; absence of contradictions or meta leakage. |

Full scoring guidance appears in the comparative paper (§ Methodology).

---

## How to Cite

If you publish work that uses this benchmark, please cite the analysis paper:

```

@misc{chronos-anomaly-v3-llm-eval,
title  = {Comparative Evaluation of Large Language Model Performance on the Chronos Anomaly Protocol v3},
author = {Raymond Cava et al.},
year   = {2025},
note   = {Version 1.0, July 2025},
url    = {[https://github.com/SIDR-EIS/sidr-hypothesis-library](https://github.com/SIDR-EIS/sidr-hypothesis-library)}
}

```

---

## Contributing

* **Bug reports / clarifications:** Open an issue.  
* **New model results:** Fork → add your `.md` transcript in `results/` → submit a pull request.  
* **Extended analyses:** Follow the quick‑start update instructions above and include clear diff notes.

---

## License

All protocol text and baseline results are released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.  
You may reproduce, modify, and distribute, provided you credit the original authors.

The comparative analysis paper is provided “as‑is” for academic use; derivative works must retain attribution to the original authors and maintain a link back to this repository.

---
