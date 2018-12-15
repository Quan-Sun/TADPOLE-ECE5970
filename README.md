# TADPOLE - ECE5970

This project topic and the dataset have been derived from an on-going data science challenge - **[The Alzheimer's Disease Prediction Of Longitudinal Evolution, TADPOLE 2017 Challenge](https://tadpole.grand-challenge.org.).**

This project represents a typical clinical scenario, where on each individual subject, various sources of information may or may not be available. Moreover, the individual might have visited the clinic multiple times at different time intervals (longitudinal). For example, the study might acquire a brain MRI scan (and compute certain measurements of neuroanatomy) and conduct a cognitive test, but not draw a blood sample during one visit. On another day, the study might omit the brain MRI for that subject but conduct a blood test.

Our goal is to make a future prediction (forecast) about clinically-relevant variables based on all the historical data we have (both on the given individual and all other individuals). A very naive baseline strategy might be to simply use the very last relevant observation that contains the target clinical variable and assume nothing will change going forward. This strategy will ignore historical trends (assuming the individual has visited the clinic several times). Moreover, this naïve approach will not exploit data from other individuals.
