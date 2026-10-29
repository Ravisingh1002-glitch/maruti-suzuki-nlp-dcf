# maruti-suzuki-nlp-dcf
Dynamic DCF model incorporating a custom macro-regime toggle to stress-test Base, Bear, and Bull scenarios.  Architected a programmatic Natural Language Processing (NLP) pipeline utilizing Python (Pandas, PyPDF2) and Hugging Face’s FinBERT to quantify management sentiment across four quarters of unstructured earnings call transcripts.  
# Maruti Suzuki Quantitative Valuation & NLP Sentiment Pipeline

## Project Overview
An institutional-grade equity research pipeline that bridges qualitative management commentary with quantitative financial forecasting. This project utilizes a custom Natural Language Processing (NLP) framework to programmatically extract and analyze 4 quarters of earnings transcripts, dynamically mapping real-time sentiment shifts directly into a 3-statement DCF valuation engine.

## Tech Stack
* **Quantitative Engine:** Microsoft Excel (Dynamic 3-statement DCF model with embedded What-If scenario logic)
* **NLP Pipeline:** Python, Pandas, PyPDF2
* **Machine Learning:** Hugging Face `Transformers`, `ProsusAI/finbert` (Pre-trained financial NLP model)

## Methodology & Execution
1. **Document Ingestion:** Automated the extraction of unstructured text across 4 quarters of Maruti Suzuki earnings call PDFs.
2. **Sentiment Analysis:** Segmented transcripts and scored management sentiment utilizing FinBERT, effectively quantifying shifts in tone regarding raw material costs and capacity expansion.
3. **Data-Driven Catalyst Identification:** Identified a 41% sequential surge in negative sentiment during the Q1 FY27 call, specifically surrounding commodity inflation (steel, copper).
4. **Dynamic DCF Integration:** Architected a Macro Regime toggle inside the Excel DCF. The quantitative bearish signal from the NLP pipeline justified triggering the Bear scenario, compressing raw material assumptions to 81.0% of sales and stress-testing the target share price.

This infrastructure eliminates emotional bias from the valuation process, anchoring scenario analysis in mathematically rigorous text analytics.
