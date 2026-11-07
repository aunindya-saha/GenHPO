# GenHPO-A-Single-Stage-LLM-Framework-for-Hyperparameter-Optimization-in-Medical-Imaging

Code repository accompanying a manuscript under peer review.

This repository is provided for anonymous evaluation purposes. 

## Repository Structure

* **`HPM_Generate_by_LLM_Updated.ipynb`**: Main pipeline script implementing the GenHPO framework to generate 180 hyperparameter configurations using frontier LLMs, prompt variations, and historical HPO logs.
* **`Copy_of_ensemble_llm_as_a_judge.ipynb`**: Implementation of the ensemble LLM-as-a-judge evaluation mechanism assessing configuration logic and expected quality.
* **`GenHPO_HP_Config_by_LLM_Evaluation.ipynb`**: Benchmarking script for running and evaluating the top-selected configurations.
* **`HPO_LLM_Analysis.xlsx`**: Detailed analytical breakdown of the 36 selected top configurations, featuring performance metrics, latency, and token consumption statistics.
* **`Final_ensemble_llm_judge_scores (1).csv`**: Judge scoring records for the evaluated hyperparameter combinations.
* **`hpm value logs.csv`**: Historical log data and results from baseline HPO algorithm experiments.
