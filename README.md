# Under development

# Clinicaltrial Engagement and Education

## DATA for Summary Generation
Data related to our summarization experiments are present in *Data/ICF* folder.
1. **11trials_for_analysis:** All 11 trials used in *Clinician summary evaluation*
    - **summary_trials_gpt4_031124.xlsx:** Generated summaries using both approaches
2. **Surveys:** Contains survey for both *Clinician summary evaluation* and *Patient survey evaluation*

## Data for MCQAs Generation
1. **mcqa_icfs.cvs:** Study number of the selected ICFs on clinicaltrials.gov used for MCQAs generation
2. **Example MCQA test for NCT03923790.xlsx:** Expert-created example MCQAs based on NCT03923790.

## CODE for Summary Generation
**DataScraping_ClinicalTrials.ipynb:** Notebook to scrape ICFs from [clinicaltrials.gov](https://clinicaltrials.gov/)

**pdf_extract.ipynb:** Notebok to extract text from PDFs

**summarization_11trials.ipynb:** Notebook to perform summarization based on two approaches mentioned in paper -- Direct summarization from text, and sequential extraction and summarization

## CODE for MCQAs Generation
**mcaq_generation.ipynb:** generating MCQAs for the selected cancer trial ICFs

## CODE for MCQAs Evaluation
**mcqa_generation_eval.ipynb:** processing the human evaluation results for MCQAs generation and query API LLMs to evaluate the MCQAs' quality

## Generated MCQAs
**gpt4_generated_mcqas folder:** all MCQAs generated based on the selected ICFs for studies listed in **mcqa_icfs.cvs:**
