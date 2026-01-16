# Generative-AI-for-NFL-Play-Calling

## Overview:
This project includes an end-to-end pipeline, utilizing NFL data from Kaggle, for predicting the outcome of plays based on pre-play statistics. By utilizing a T5 model a natural language play-by-play for this prediction is also provided to explain the prediction further. Among many other evaluation techniques, a BERT model is also used to evaluate the accuracy of the T5 model's prediction. The T5 model achieves a BLEU score of 0.33 and the BERT model achieves an accuracy alone of 0.77.

## Project Goal:
Predicting the outcome of plays in the NFL is a difficult task, but one that is doable using player, game, and play-by-play statistics. However, taking that prediction and generating an explanation for coaches to use as a tool is not something as explored. This projects main method aims to tackle this issue through the training and evaluation of a T5 model. The model’s main task is providing a stylized play-by-play description while predicting the outcome of a play. After evaluating the model using multiple evaluation metrics, including a BERT model to ensure accuracy, this T5 model had relatively good performance. Further study could be done using different pre-trained models or different features in the input to the T5 model.

## Repository Structure:
  - project_code.ipynb: All code for the full pipeline. Sections include data cleaning, data splitting, data tuning for T5 parameters, tokenization for BERT model, and data             training and evaluation for both the BERT and T5 model.
  - project_report.pdf: This contains a complete explanation of the project as well as methods for repeatability utilizing the code. In addition their is discussion of further          improvements to this project.

## References:
  - https://github.com/nflverse/nfl data py.
  - doi: 10.2478/ijcss-2020-0009
  - https://statsbomb.com/wp-content/uploads/2023/10/TacticalGPT-Uncovering-the-Potential-of-LLMs-for-Predicting-Tactical-Decisions-in-Professional-Football.pdf.
  - https://dl.acm.org/doi/pdf/10.1145/3606038.3616157.
  - https://medium.com/nlplanet/a-full-guide-to-finetuning-t5-for-text2text-and-building-a-demo-with-streamlit-c72009631887.
  - https://learnopencv.com/fine-tuning-t5/.
  - https://www.tensorflow.org/tfmodels/nlp/fine tune bert.
  - https://lajavaness.medium.com/multiclass-and-multilabel-text-classification-in-one-bert-model-95c54aab59dc.\
  - https://cloud.google.com/translate/docs/advanced/automl-evaluate.
  - https://www.kdnuggets.com/2023/01/micro-macro-weighted-averages-f1-score-clearly-explained.html.
  - https://www.datacamp.com/tutorial/fine-tuning-gpt-3-using-the-open-ai-api-and-python.
  - https://arxiv.org/abs/2011.07805.
