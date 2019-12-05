---
title: Project Finalization & Conclusion
description: Finlization of project and results.
---

# Project Finalization & Conclusion

## Interpertation of Micro-average and Macro-average

- Micro-average:
	- Consturct a 2 x 2 confusion matrix by summing up the TP, FP, TN, and FN from all k one-vs-all matrices.
	- Performance calculation should be carried out based on this average

- Macro-average:
	- Obtain performance measurements from each of the k one-vs-all matrices separately.
	- Calculate average of all aforementioned measurements.	

Since this is a multiclassification problem, there are two types of analysis for evaluation. Macro-average analysis and micro-average analysis. The latter is the preferred analysis method.
	
## KNN Result

### K-fold Micro-average analysis

- **Accuracy**: 91%
- **Sensitivity**: 81%
- **Specificity**: 93%

### K-fold Macro-average analysis

- **Accuracy**: 82%

For Class 1:

- **Sensitivity**: 89%
- **Specificity**: 96%

### K-fold Stratified Micro-average analysis

- **Accuracy**: 93%
- **Sensitivity**: 93%
- **Specificity**: 97%

### K-fold Stratified Macro-average analysis

- **Accuracy**: 85%

For Class 1:

- **Sensitivity**: 88%
- **Specificity**: 97%

*** 

## Naive-Bayes Result

### K-fold Micro-average analysis

- **Accuracy**: 97.6%
- **Sensitivity**: 95%
- **Specificity**: 98.7%

### K-fold Macro-average analysis

- **Accuracy**: 95%

For Class 1:

- **Sensitivity**: 93%
- **Specificity**: 99%

### K-fold Stratified Micro-average analysis

- **Accuracy**: 99%
- **Sensitivity**: 98%
- **Specificity**: 99.5%

### K-fold Stratified Macro-average analysis

- **Accuracy**: 98%

For Class 1:

- **Sensitivity**: 100%
- **Specificity**: 98%

## Overall results

A table of the aforementioned results has been compiled below to provide a more pleasent reading experience. 

| Model  | KNN K-fold Micro-average analysis | KNN K-fold Macro-average analysis | KNN K-fold Stratified Micro-average analysis  | K-fold Stratified Macro-average analysis  |  NB K-fold Micro-average analysis | NB K-fold Macro-average analysis  | NB K-fold Stratified Micro-average analysis  | NB K-fold Stratified Macro-average analysis  |
|---|---|---|---|---|---|---|---|---|
|  Accuracy |  91% |  82% | 93%  | 85%  |  97.6% | 95%  |  99% | 98%  |
|  Sensitivity |  81% |  89% | 93%  |  88% |  95% |  93% |  98% |  100% |
| Specificity  | 93%  |  96% |  97% | 87%  | 98.7%  |  99% | 99.5%  | 98%  |


## Quick interpertations of sensitivity, specificity.

- Sensitivity: True Postive Rate: TP / (TP + FN)
- Specificity: True Negative Rate: TN / (TN + FP)




