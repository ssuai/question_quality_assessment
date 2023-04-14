# Question quality assessment (QQA)

## The dataset
* We will use Task 3 of [Diagnostic Questions competition](https://www.microsoft.com/en-us/research/academic-program/diagnostic-questions/), which was one of the [NeurIPS 2020 Competitions](https://neurips.cc/Conferences/2020/CompetitionTrack).
* Download the dataset from [here](https://dqanonymousdata.blob.core.windows.net/neurips-public/data.zip) and put it under `data` folder.
* subfolder structure
  * `images`: actual questions
  * `metadata`: some side information about questions and students  
  * `train_data`: use `train_task_3_4.csv` for training
  * `test_data`: use `quality_response_remapped_public.csv` for validation and `quality_response_remapped_private.csv` for test

## Goal
* estimate the quality of questions from students responses and other information about questions.
* calculate the rankings of the questions using the template in [`submission/template.csv`](.submission/template.csv)
* save the file as `YOUR_STUDENT_ID.csv` and submit with the report
