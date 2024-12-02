# Clinicaltrial Engagement and Education

## Summary Generation
### Data:
Data related to our summarization experiments are present in *Data/ICF* folder.
1. **11trials_for_analysis:** All 11 trials used in *Clinician summary evaluation*
    - **summary_trials_gpt4_031124.xlsx:** Generated summaries using both approaches
2. **Surveys:** Contains survey for both *Clinician summary evaluation* and *Patient survey evaluation*

### Code:
Below notebooks will generate summaries.
1. **datascraping_clinicaltrials.ipynb:** Notebook to collect ICFs from [clinicaltrials.gov](https://clinicaltrials.gov/)

2. **pdf_extract.ipynb:** Notebok to extract text from PDFs

3. **summarization_11trials.ipynb:** Notebook to perform summarization based on two approaches mentioned in paper -- Direct summarization from text, and sequential extraction and summarization

## MCQAs Generation and Evaluation
### Data
1. **mcqa_icfs.cvs:** Study number of the selected ICFs on clinicaltrials.gov used for MCQAs generation
2. **Example MCQA test for NCT03923790.xlsx:** Expert-created example MCQAs based on NCT03923790.


### Code
Below notebooks will generate and evaluate MCQA Generation.
1. **mcaq_generation.ipynb:** generating MCQAs for the selected cancer trial ICFs

2. **mcqa_generation_eval.ipynb:** processing the human evaluation results for MCQAs generation and query API LLMs to evaluate the MCQAs' quality

3. **gpt4_generated_mcqas folder:** all MCQAs generated based on the selected ICFs for studies listed in **mcqa_icfs.cvs:**
