The task involves predicting race based on a person name.

Process:
1. Import relevant library (numpy, pandas, sklearn, tensorflow, matplotlib, seaborn).
2. Check tensorflow and system version.
3. Clean the dataset, check for any duplicate and empty cell. Remove leading and trailing whitespace.
4. Convert all string to lowercase.
5. Label encoding and count vectorization, save count vector.
6. Train test split the dataset.
7. Define the model using tensorflow, with 64 for the first layer and 32 for the second layer, softmax is used for activation to convert integer to probabilty, creating decimal.
8. Compile the model.
9. Train the model using epochs 10 with batch size 32.
10. Save the tensorflow model.
11. Model evaluation and model prediction.
12. Use classification report to see precision, recall, f1-score, and support.
13. Use confusion matrix to observe predicted data.
14. Use different dataset to test model reliability and prediction.
