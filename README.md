# toxity-classification-practice

Practice notebook for learning basic NLP and ML workflows using the Jigsaw Toxic Comment Classification dataset.

## What I explored

- Text preprocessing with pandas
- Binary toxicity classification
- TF-IDF vectorisation
- Logistic Regression baseline
- Precision / Recall / F1-score
- Confusion matrix analysis
- Threshold trade-offs
- Recall comparison by toxicity subtype
  - toxic
  - severe_toxic
  - obscene
  - insult
  - threat
  - identity_hate

## Main observations

- The model achieved relatively high recall for toxic comments.
- Lower thresholds increased recall but also increased false positives.
- Severe toxic comments were generally easier for the model to detect than milder or context-dependent toxicity.
