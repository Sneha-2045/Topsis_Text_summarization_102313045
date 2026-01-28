# TOPSIS Based Selection of Pretrained Model for Text Summarization

## Objective

To identify the best pretrained model for text summarization using the
TOPSIS multi-criteria decision making method.

## Models Evaluated

-   LSTM Seq2Seq
-   BERTSum
-   T5
-   BART
-   PEGASUS

## Evaluation Criteria

-   ROUGE Score (Benefit)
-   Inference Time (Cost)
-   Model Size (Cost)
-   RAM Usage (Cost)
-   Readability (Benefit)

## Methodology

1.  Construct decision matrix.
2.  Normalize the data.
3.  Apply weights to criteria.
4.  Identify ideal best and worst solutions.
5.  Calculate distances and TOPSIS score.
6.  Rank models based on scores.

## Result

The model with the highest TOPSIS score is considered the best for text
summarization.

## Files Included

-   TOPSIS_Text_Summarization.xlsx (Results Table)
-   TOPSIS_Score_Graph.png (Score Visualization)
