# Cell-Biology-Misconceptions-AI Model Evaluation
## Project Overview
This project evaluates how different AI models respond to common misconceptions in cell biology. Their answers were scored based onir Accuracy, Clarity, and Completeness to assess scientific reliability and reasoning quality. Responses were scored manually and fact-checked using biological references

## Dataset Information
- **Dataset Type:** AI Biological Knowledge Evaluation  
- **Domain:** Cell Biology & Misconceptions  
- **Data Collection Period:** 15–30 Nov 2025.  
- **Models Evaluated:** ChatGPT-5, Claude (latest public), Copilot.  
- **Evaluation Method:** Responses copied verbatim; assessed manually and scored numerically
  
### Scoring Rubric
**Category Scoring (1–5 per response)**

| Score | Meaning                                  |
| ----- | ---------------------------------------- |
| **1** | Poor – incorrect or unclear              |
| **2** | Fair – partially correct or vague        |
| **3** | Good – mostly correct                    |
| **4** | Very Good – clear and correct            |
| **5** | Excellent – correct, clear, and complete |

**Final Correctness Score (0–2)**

| Final Score | Meaning                                               |
| ----------- | ----------------------------------------------------- |
| **2**       | Fully correct – no major issues                       |
| **1**       | Partially correct – minor clarity/completeness issues |
| **0**       | Incorrect or misleading                               |

> - Length of response does not affect scoring unless it causes confusion or misinformation.
---

## Key Takeaways
1. **ChatGPT-5:** Consistently provided short, accurate, and clear responses, but sometimes answers can be oversimplified, which may miss clarification or completeness; clarification language is recommended.  
2. **Claude:** Consistently provided accurate and clear responses — no observed misconceptions.  
3. **Copilot:** Responses were mostly correct with extra explanation, which is excellent for learners wanting deeper knowledge, but sometimes used phrasing that could reinforce misconceptions.  

**Observed Error Types:**  

| Model     | Common Issue        |
| --------- | ------------------- |
| ChatGPT-5 | Oversimplification  |
| Copilot   | Misleading phrasing |
| Claude    | No error            |

---

## AI Model Performance Summary

| AI Model   | Average Accuracy| Average Clarity| Average Completeness| Average Final Score | Observed Errors         |
|------------|-----------------|----------------|---------------------|---------------------|-------------------------|
| ChatGPT-5  | 4.9             | 4.8            | 4.5                 | 1.9                 | Oversimplification      |
| Claude     | 5.0             | 5.0            | 5.0                 | 2.0                 | No error                |
| Copilot    | 4.9             | 4.9            | 4.9                 | 1.9                 | Misleading phrasing     |

> **Notes:**  
> - Averages are based on the 10 evaluation questions.  
> - Final score is calculated as `(sum of individual question scores) ÷ total questions`.  
> - “Observed Errors” highlights recurring issues, if any; blank for models with none.
> - Final Score is not calculated from the 1–5 category averages — it is a separate correctness rating (0–2).
 
---

Model Reliability Summary
-------------------------------------------------
- Claude — Most reliable overall, no errors
- Copilot — Good detail, one misleading phrasing case (rare)
- ChatGPT-5 — Accurate, short & clear, sometimes too brief for full completeness
-------------------------------------------------
---

## Example Evaluation Entry (CSV-style table for reference)

| S. No. | Misconception | Prompt | AI Model | AI Response | Accuracy | Clarity | Completeness | Score | Comment | correction (if any) | Source Used | Error Type|
|--------|---------------|--------|----------|-------------|----------|---------|--------------|-------|---------|-------------|------|--------|
| 1      | DNA is larger than a cell | Is DNA larger than a cell? | ChatGPT-5 | No. A cell is massively larger. DNA is a long molecule inside the cell nucleus (or nucleoid), but the cell itself is much bigger. | 5 | 5 | 4 | 2 | Correct answer; short and clear. | No correction needed. (Optional: add numeric comparison: cell ~10–100 µm vs DNA ~2 m when stretched for clarity.)| [Khan Academy: Organelles in eukaryotic cells](https://www.khanacademy.org/test-prep/mcat/cells/eukaryotic-cells/a/organelles) | No error|

> The full dataset is saved in dataset.xlsx, with the main sheet named “AI response analysis” for easy access to scoring, charts, and observations.

---

| File          | Description                                                                                              |
| ------------- | -------------------------------------------------------------------------------------------------------- |
| `dataset.xlsx`| Full evaluation dataset (AI responses + scoring), AI model performance summary and charts & observations. Main sheet: “AI response analysis”|                                                                                        
| `README.md`   | Documentation and project summary                                                                        |

---

## How This Demonstrates Evaluation Skill
- ✔ Manual verification of biological correctness  
- ✔ Identifying subtle misconceptions and misleading phrasing  
- ✔ Structured scoring rubric for accuracy, clarity & completeness  
- ✔ Comparative performance analysis across LLMs  
- ✔ Clear reporting with tables & summary insights — relevant for AI evaluation roles
  
> Ideal for showcasing expertise in **AI biological knowledge evaluation** or **science-focused AI assessment roles**.

---

## Usage
- Open the dataset.xlsx in Excel, Google Sheets, or Python for analysis.
  - Go to the “AI response analysis” sheet to see the main dataset, scoring, and charts.
- Charts, formatting, and multiple sheets are preserved in the Excel workbook
- CSV export is not provided because saving as CSV removes charts, formulas, and other sheets
- Use the README and xlsx together for presentations, reporting, or AI evaluation tasks.  

---

## License
This repository is for educational and professional demonstration purposes. All sources are cited directly in the dataset.
