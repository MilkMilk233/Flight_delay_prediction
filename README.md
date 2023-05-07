# Flight_delay_prediction

Author: Chen Zhixin

Date: 2023/5/7

Result & Evaluation:

- Training dataset on Jan.1 ~ Mar. 31, 2015, US
- Applied test on flight record of Apr.1 ~ Feb. 30, 2015, US
- 89.2% of the predictions are ±30 mins within the ground truth,
which is acceptable. (Baseline: random-forest, 82.1%)

Content: `solution.ipynb`

Approach: LSTM + random forest regression

Structure:

![4010](https://github.com/MilkMilk233/Flight_delay_prediction/assets/86474550/4a6bcf93-7934-44d0-b9c8-ec5e44138eab)
