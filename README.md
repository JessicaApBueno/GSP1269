# GSP1269
### Supervised Fine Tuning with Gemini for Question & Answering

Overview
This lab provides a hands-on introduction to fine-tuning Gemini generative models using Vertex AI's Supervised Tuning feature. You'll learn how to leverage your own labeled data to refine a base Gemini model, adapting it to excel at specific tasks like classification, summarization, question answering, and chat.

The fine-tuning process involves these key steps:

Data Preparation: Providing high-quality, well-labeled training data is crucial. Your data directly influences the model's performance and helps mitigate potential biases.
Training: Experiment with different training configurations to optimize the model for your target task. This iterative process allows you to maximize the model's potential.
Evaluation: Carefully select evaluation metrics and a separate dataset to accurately assess the fine-tuned model's performance.
Recommended Configurations:

To guide your fine-tuning journey, we provide recommended starting points for various tasks:

Task	Examples in Dataset	Epochs
Classification	500+	2-4
Summarization	1000+	2-4
Extractive QA	500+	2-4
Chat	1000+	2-4
Prerequisites
Before starting this lab, you should be familiar with:

Basic Python programming.
General API concepts.
Running Python code in a Jupyter notebook on Vertex AI Workbench.
Objectives
In this lab, you will:

Understand the process to utilize supervised fine-tuning.
Enhance results from Gemini using data from BigQuery.
Fine-tune Gemini using question & answer data from StackOverflow.

Lab Link: https://www.cloudskillsboost.google/games/5996/labs/38261?locale=en