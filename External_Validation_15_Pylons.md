# External validation of the aesthetic network

The aesthetic network trained using Qwen-generated labels was evaluated on 15 human-rated pylon samples from Ref. [32], comprising five samples from each of the high-, intermediate-, and low-rated groups. These samples had not been used for network training, validation, or model selection.

The network correctly classified all five high-rated and all five low-rated samples, giving **100% agreement for these ten samples**. Agreement was lower for the intermediate-rated group, where 24–25 of the 50 participants assigned a high-quality rating. This pattern is consistent with less clear-cut human judgments for borderline forms. Overall agreement with the reported binary reference labels was **73.33% (11/15)**.

## Sample results

Probabilities are network outputs. Human votes are counts of high-quality ratings out of 50 participants. The group describes the sample's human-rating stratum; the reference label is binary. Sample identifiers retain their original within-type numbering.

| No. | Group | Pylon type | Sample ID | High probability (%) | Low probability (%) | Prediction | Reference label | Human votes / 50 |
| --- | --- | --- | --- | ---: | ---: | --- | --- | ---: |
| 1 | High | Cable-stayed | 207_1 | 92.45 | 7.55 | High | High | 47 |
| 2 | High | Cable-stayed | 161_1 | 87.64 | 12.36 | High | High | 45 |
| 3 | High | Suspension | 125_1 | 73.90 | 26.10 | High | High | 41 |
| 4 | High | Suspension | 218_2 | 54.36 | 45.64 | High | High | 43 |
| 5 | High | Cable-stayed | 201_1 | 97.16 | 2.84 | High | High | 45 |
| 6 | Intermediate | Cable-stayed | 162_1 | 84.22 | 15.78 | High | Low | 25 |
| 7 | Intermediate | Cable-stayed | 218_1 | 88.02 | 11.98 | High | Low | 25 |
| 8 | Intermediate | Cable-stayed | 222_1 | 73.67 | 26.33 | High | Low | 24 |
| 9 | Intermediate | Suspension | 108_1 | 57.30 | 42.70 | High | Low | 25 |
| 10 | Intermediate | Suspension | 147_1 | 39.59 | 60.41 | Low | Low | 25 |
| 11 | Low | Cable-stayed | 164_1 | 40.43 | 59.57 | Low | Low | 2 |
| 12 | Low | Cable-stayed | 113_1 | 28.69 | 71.31 | Low | Low | 8 |
| 13 | Low | Suspension | 134_1 | 25.99 | 74.01 | Low | Low | 5 |
| 14 | Low | Suspension | 177_1 | 32.77 | 67.23 | Low | Low | 7 |
| 15 | Low | Suspension | 184_1 | 16.23 | 83.77 | Low | Low | 8 |

## Interpretation

The findings support discrimination between clearly contrasting aesthetic qualities in these selected samples. The intermediate group's near-even human vote split indicates less clear-cut collective preference; it does not by itself establish the cause of the network's disagreements. This small-sample evaluation is separate from the independent 134-sample classification and calibration test reported in the supplementary Word document.

**Ref. [32]:** Xiang C, Chen A, Wang D, Ning Y. Deep-learning-based aesthetic evaluation network for bridge pylon and aesthetics-oriented bridge design. *Structures*. 2025;71:108167.
