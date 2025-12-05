# Cell-Biology-Misconceptions-Evaluation
## Project Overview
This project evaluates AI models on their responses to common misconceptions in cell biology by scoring their accuracy, clarity, and completeness— demonstrating practical skills in AI evaluation, biological fact-checking, and model quality assessment.

## Dataset
- **Dataset Type:** AI Biological Knowledge Evaluation  
- **Domain:** Cell Biology & Misconceptions  
- **Methods / Metadata:** Responses collected between 15–30 Nov 2025.  
- **Models Tested:** ChatGPT-5, Claude (latest public), Copilot.  
- **Scoring:** Responses were copied verbatim; Each response is manually assessed for Accuracy, Clarity, Completeness and given a
               Final Score (0–2) based on correctness and explanation quality.

### Scoring Rubric
- **Accuracy:** Factual correctness (no scientific errors)  
- **Clarity:** Understandability and well-phrased answers  
- **Completeness:** Whether the response fully addresses the question  
  - Differences in length or detail do not affect the score unless they introduce confusion or misinformation.  
  - Model output length is not a scoring factor.  

**Rating Scale (Accuracy / Clarity / Completeness):**  
1 = poor, 2 = fair, 3 = good, 4 = very good, 5 = excellent  

**Final Score (0–2):**  
- 2 = fully correct (accuracy 5, no major omissions)  
- 1 = partially correct (accuracy 3–4 OR clarity/completeness issues)  
- 0 = incorrect (accuracy ≤2 or misleading fact)  

---

## Key Takeaways
1. **ChatGPT-5:** Consistently provided short, accurate, and clear responses, but sometimes answers can be oversimplified, which may miss clarification or completeness; clarification language is recommended.  
2. **Claude:** Consistently provided accurate and clear responses with no complexity.  
3. **Copilot:** Responses were mostly correct with extra explanation, which is excellent for learners wanting deeper knowledge, but sometimes used phrasing that could reinforce misconceptions.  

**Observed AI Errors:**  
- ChatGPT-5: Oversimplification  
- Copilot: Misleading phrasing  
- Claude: None  

---

## AI Model Performance Summary

| AI Model   | Average Accuracy| Average Clarity| Average Completeness| Average Final Score | Observed Errors         |
|------------|-----------------|----------------|---------------------|---------------------|-------------------------|
| ChatGPT-5  | 4.9             | 4.8            | 4.5                 | 1.9                 | Oversimplification      |
| Claude     | 5.0             | 5.0            | 5.0                 | 2.0                 | None                    |
| Copilot    | 4.9             | 4.9            | 4.9                 | 1.9                 | Misleading phrasing     |

> **Notes:**  
> - Averages are based on the 10 evaluation questions.  
> - Final score is calculated as `(sum of individual question scores) ÷ total questions`.  
> - “Observed Errors” highlights recurring issues, if any; blank for models with none.
> - Final Score is not calculated from the 1–5 category averages — it is a separate correctness rating (0–2).
 

---

## Example Evaluation Entry (CSV format)

| S. No. | Misconception | Prompt | AI Model | AI Response | Accuracy | Clarity | Completeness | Score | Comment | Source Used |
|--------|---------------|--------|----------|-------------|----------|---------|--------------|-------|---------|-------------|
| 1      | DNA is larger than a cell | Is DNA larger than a cell? | ChatGPT-5 | No. A cell is massively larger. DNA is a long molecule inside the cell nucleus (or nucleoid), but the cell itself is much bigger. | 5 | 5 | 4 | 2 | Correct answer; short and clear. | [Khan Academy: Organelles in eukaryotic cells](https://www.khanacademy.org/test-prep/mcat/cells/eukaryotic-cells/a/organelles) |

> The full dataset is saved in CSV UTF-8 (comma-delimited) format for easy access and reproducibility.

---

| File          | Description                                      |
| ------------- | ------------------------------------------------ |
| `dataset.csv` | Full evaluation dataset (AI responses + scoring) |
| `README.md`   | Project documentation (this file)                |

---

## How This Demonstrates Evaluation Skill
- ✔ Manual verification of biological correctness  
- ✔ Identifying subtle misconceptions and misleading phrasing  
- ✔ Structured scoring rubric for accuracy, clarity & completeness  
- ✔ Comparative performance analysis across LLMs  
- ✔ Clear reporting with tables & summary insights — relevant for AI evaluation roles  

---

## Usage
- Open the CSV in Excel, Google Sheets, or Python for analysis.  
- Use the README and CSV together for presentations, reporting, or AI evaluation tasks.  
- Ideal for showcasing expertise in **AI biological knowledge evaluation** or **science-focused AI assessment roles**.

---

## License
This repository is for educational and professional demonstration purposes. All sources are cited directly in the dataset.
