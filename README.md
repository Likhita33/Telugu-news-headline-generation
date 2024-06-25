Overview
This project focuses on finetuning models for Telugu News Headline Generation. It includes datasets, code files for model finetuning, and generated summaries/headlines.

Contents
Datasets : Created by scraping news articles and headlines from Telugu news website "Sakshi".
final_train.csv: Training dataset in Telugu consisting of article and headlines pairs.
final_test.csv: Test dataset in Telugu consisting of article and headlines pairs.

Code Files
There are three main code files provided to finetune the models:
finetuning_mBART50.ipynb: Code for finetuning mBART50-large.
finetuning_mT5.ipynb: Code for finetuning mT5-small.
finetuning_IndicBART.ipynb: Code for finetuning IndicBART.

Generated Summaries/Headlines
mBART50_generated_summaries.csv: contains generated summaries/headlines after finetuning mBART50-large.
mT5_generated_summaries.csv: contains generated summaries/headlines after finetuning mT5-small.
IndicBART_generated_summaries.csv: contains generated summaries/headlines after finetuning IndicBART.
