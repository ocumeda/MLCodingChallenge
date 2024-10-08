**Objective:**

The goal of this assignment is to evaluate your ability to work with real-world datasets, perform data analysis, and apply machine learning techniques. You will be required to fine-tune a classifier using different strategies and effectively track and compare the experiments using the MLflow library. Your ability to set up a reproducible workflow is of utmost importance.

![Ohne Titel](https://user-images.githubusercontent.com/2522480/149497318-fe47c02c-696a-4cb5-8841-2dbe6785029d.png)

**Instructions:**

1. **Dataset Retrieval and Analysis:**
   - Access the dataset from the [AIROGS Challenge](https://airogs.grand-challenge.org/).
   - Retrieve approximately 1,000 cases.
   - Evaluate the distribution of the data to determine if it is balanced or unbalanced. Provide a summary of your findings.

2. **Classifier Fine-Tuning:**
   - Select a simple classifier (the specific choice of classifier is not critical).
   - Fine-tune the classifier using at least two of the following strategies:
     - **Strategy 1:** Fine-tune the last layer for 10 epochs.
     - **Strategy 2:** Fine-tune the last three layers for 10 epochs.
     - **Strategy 3:** Fine-tune the last three layers for 50 epochs.

3. **Experiment Tracking and Reproducibility:**
   - Set up the fine-tuning process in such a way that it is easily reproducible.
   - Use the **MLflow** library to track the configuration and metrics of each experiment.
   - Ensure that the experiments can be easily compared with one another.

4. **Conclusion:**

Based on the experiments and metrics tracked, draw a reasonable conclusion regarding the fine-tuning strategies. Prepare a discussion on which strategy performed best and why.

**Deliverables:**

- Python script containing:
  - The data analysis and distribution evaluation.
  - The code for each fine-tuning strategy.
  - The MLflow setup and logs for each experiment.
- A summary of your findings and conclusions.

**Submission:**

Please submit your completed assignment as a zip file that you send us via e-mail. Ensure that the ZIP file contains clear instructions on how to run your code.

**Deadline:**

Please submit your work at least 24h before your interview.
