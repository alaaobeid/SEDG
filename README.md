# Bias Evaluation in Biometric Verification: Metrics Implementation

This repository contains the implementation of the metrics used in the paper:

**A. Elobaid, N. Ramoly, L. Younes, S. Papadopoulos, E. Ntoutsi, and I. Kompatsiaris, "Sum of Group Error Differences: A Critical Examination of Bias Evaluation in Biometric Verification and a Dual-Metric Measure," 2024 IEEE 18th International Conference on Automatic Face and Gesture Recognition (FG), Istanbul, Turkiye, 2024, pp. 1-9, doi: [10.1109/FG59268.2024.10582012](https://doi.org/10.1109/FG59268.2024.10582012).**

---

## Overview

To promote accessibility and encourage exploration of fairness in biometric verification, we have hosted the implementation of the metrics on a [Hugging Face Space](https://huggingface.co/spaces/alaaobeid/Bias_Evaluation_in_Biometric_Verification). This space provides an easy-to-use interface for researchers, practitioners, and the broader biometric fairness community to utilize the metrics described in the paper.

The metrics aim to evaluate bias comprehensively by introducing the **Sum of Group Error Differences (SGED)**, a dual-metric measure that critically examines biases in biometric systems.

---

## Access the Hugging Face Space

The implementation is available here:  
[Hugging Face Space: Bias Evaluation in Biometric Verification](https://huggingface.co/spaces/alaaobeid/Bias_Evaluation_in_Biometric_Verification)

### Key Features:
- Accepts **distance and label data** in the form of a **pickle file**.
- Outputs the computed metrics for bias evaluation.
- Easy-to-use interface for evaluating bias metrics.
- Explanation and examples of the metrics used.
- Open for the biometric fairness community to use and provide feedback.

---

## Descriptions of the Metrics

For detailed explanations of the metrics and how they are calculated, visit the space's [README file](https://huggingface.co/spaces/alaaobeid/Bias_Evaluation_in_Biometric_Verification/blob/main/README.md).

This documentation provides an in-depth understanding of the evaluation criteria and their importance in ensuring fairness in biometric systems.

---

### Citation

If you use the implementation or metrics in your work, please cite the following paper:

```bibtex
@inproceedings{elobaid2024sum,
  author={A. Elobaid and N. Ramoly and L. Younes and S. Papadopoulos and E. Ntoutsi and I. Kompatsiaris},
  title={Sum of Group Error Differences: A Critical Examination of Bias Evaluation in Biometric Verification and a Dual-Metric Measure},
  booktitle={2024 IEEE 18th International Conference on Automatic Face and Gesture Recognition (FG)},
  year={2024},
  pages={1-9},
  doi={10.1109/FG59268.2024.10582012}
}
