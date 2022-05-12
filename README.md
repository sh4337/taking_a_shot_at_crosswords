# Taking A Shot At Crosswords

There exists little prior research for solving American-style crosswords using transformer-based language models. This project explore how these increasingly large language models perform on this task in general and with prompting. We ran experiments by coming up with a list of different ways to prompt the model in both zero- and few-shot settings. We show that we can improve upon the performance of existing fine-tuned and retrieval transformers using InstructGPT with prompting, achieving 38\% exact match accuracy compared to 24\% for the next best model. Our best approach achieves the highest known accuracy of transformer-based language models on these puzzles.

Files on this github will enable you to recreate our results! 

archive.zip: compressed net crossword clue-answer pair dataset found on https://www.kaggle.com/datasets/darinhawley/new-york-times-crossword-clues-answers-19932021

experiment.ipynb: notebook with code to clean crossword data, setup zero-, one- few shot baseline and constrained prompts, send prompts to InstructGPT and save results

results.zip: compressed master file of all outputs from InstructGPT

analysis.ipynb: notebook with code for calculating exact match and constraint match metrics using data found in the results.zip
