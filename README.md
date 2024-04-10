# Duke Masters Final Project

This repository contains the code and data for my master's project on evaluating models for two specific tasks: coding challenges similar to those in interviews at large tech companies, and passing the medical USMLE Step 1 exam.

## Models and Datasets

The models and datasets are available on Hugging Face:
[https://huggingface.co/dhyay](https://huggingface.co/dhyay)

## Presentation

For a detailed overview, please see the project presentation:
[Presentation Link](https://docs.google.com/presentation/d/1dkAmKN-p-qZpB2oQBuZMT2CafxSKT8O1hj4m02jbQ40/edit?usp=sharing)

## Data Files

The following data files are included in this repository:

- `Medical LLM Data.xlsx` - Contains the medical questions, training data, and scores.
- `Code LLM Data.xlsx` - Contains the coding questions, training data, and scores.
- `Medical_testdata.xlsx` - Contains the correct medical questions and answers for testing the models.
- `Code Test.xlsx` - Contains the correct coding questions and answers for testing the models.

## Code Files

The repository includes the following Jupyter notebooks:

- `finetuning_mistral7b_combined_dataset.ipynb` - Fine-tuning Mistral 7B with options for using Hugging Face data, your own data, or a mix of both.
- `fintuningphi_customdata.ipynb` - Notebook for fine-tuning phi (in 8-bit quantization).
- `mistralMergeDPOinference.ipynb` - Perform inference on the DPO model trained.
- `mistralMergeDPO.ipynb` - Guide on performing DPO using a Hugging Face dataset.
- `Merging models with Mergekit.ipynb` - Merge two models using SLERP and upload to Hugging Face with an Apache license.
- `Simple_Gating.ipynb` - Demonstrates the simple gating mechanism for this task, effective due to the distinct prompts for each task.

