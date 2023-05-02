# Question quality assessment

## Dataset
* We will use Task 3 of [Diagnostic Questions competition](https://www.microsoft.com/en-us/research/academic-program/diagnostic-questions/), which was one of the [NeurIPS 2020 Competitions](https://neurips.cc/Conferences/2020/CompetitionTrack).
* The data were collected and kindly shared by Eedi, University of Cambridge, Rice University, Microsoft Research.
* Download the dataset from [here](https://dqanonymousdata.blob.core.windows.net/neurips-public/data.zip) and put it under `data` folder.
* subfolder structure
  * `images`: actual questions
  * `metadata`: some side information about questions and students  
  * `train_data`: use `train_task_3_4.csv` for training
  * `test_data`: use `quality_response_remapped_public.csv` for validation and `quality_response_remapped_private.csv` for test

## Task
* estimate the quality of questions from students responses and other information about questions.
* calculate the rankings of the questions using the template in [`submission/template.csv`](.submission/template.csv).
* save the file as `YOUR_STUDENT_ID.csv` and submit with your report.

## Report template
* Report must be a pdf file with filename `YOUR_STUDENT_ID.pdf`
* Summary (maximum 250 words): provide a brief overview, the problem statement, methodology, findings, and conclusions
* Introduction: provide background, define the problem, and state your objectives
* Methods: provide technical details (preproprocessing data, models used, details of experiments, how to analyze the results). Include the link to your `GitHub repository`. If you want to keep yor repository private, invite `ssuai` as a collaborator.
* Results: present findings (Use graphs or tables!)
* Discussion: interpret your findings and discuss implications
* Conclusion: summarize main findings, provide the main message, discuss future directions
* References: list of all the sources cited in the report

## References
* [Instructions and Guide for Diagnostic Questions](https://arxiv.org/abs/2007.12061)
* [Results and Insights from Diagnostic Questions](https://proceedings.mlr.press/v133/wang21a.html)
