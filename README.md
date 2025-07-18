# B2B Call Transcript Analysis

Analyze B2B customer call transcripts and visualize insights using Power BI.

---

## 📁 Project Overview

- **Input**: `input_transcript.csv` – raw call transcripts (Call_ID, Date, Company, Person, Product, Transcript_Text)
- **Processing**: A Jupyter notebook (`call_analysis.ipynb`) that uses OpenAI GPT‑4 to:
  - Classify feedback type (Complaint, Compliment, Suggestion, Neutral)
  - Extract product/service mentions and reasons
  - Generate concise call summaries
- **Output**: `output_transcript.csv` with added columns:
  - `Sentiment`, `Feedback_Type`, `Product_Extracted`, `Reason`, `Summary`

- **Visualization**: Power BI Dashboard (`powerbi/Report.pbix`) featuring:
  - Line chart (Complaints over time by product)
  - Bar/Pie charts (Feedback type & Sentiment breakdown)
  - Heat map of sentiment vs. products

---

## ⚙️ Requirements

- Python 3.8+
- `openai`, `pandas`, `tqdm`
- Power BI Desktop

Install Python dependencies:

```bash
pip install openai pandas tqdm
```

---

## 🚀 How to Run

1. Open `call_analysis.ipynb`
2. Add your OpenAI API key (e.g., `openai.api_key = "sk-..."`)
3. Run all cells to generate `output_transcript.csv`
4. Open `powerbi/Call_Transcript_Analysis.pbix` in Power BI and enjoy the dashboard

---

## 🙋 Questions or Contributions?
- Feel free to submit issues or PRs!
- Connect with me on GitHub: @Devarshi07 — or email devarshim2002@gmail.com
