# NLP-Performance-Status-project

README

This repository contains code used in the research for automating Performance Status (PS) annotation in oncology patient records using Llama-3. The files are organized into categories based on the specific tasks they address. Below is a step-by-step guide on how to use the files in the correct order.

1. Preprocess_Calculate Metrics.ipynb
   - Purpose: Processes the CSV annotations to create a structured annotated dataset.

2. Annotated dataframes split to sentence rows.ipynb
   - Purpose: Splits the annotated dataset into individual sentence rows (with note-number) for further processing.

3. Create folds for validation and test set.ipynb
   - Purpose: Creates stratified folds for the validation and test sets.

4. Confirm INCEpTION positive labels.ipynb
   - Purpose: Manually reviews and confirms positive labels from the INCEpTION annotations.

5. ACSESS find examples.ipynb
   - Purpose: Selects examples from the validation set using ACSESS for application on the test set.

6. Training.ipynb
   - Purpose: Runs the Llama model on the on the validation set and on the test set using examples selected by ACSESS.

7. Evaluation binary classification task.ipynb
   - Purpose: Evaluates the regression task's performance metrics (e.g., MAE, MSE, RMSE).

8. Evaluation regression task.ipynb
   - Purpose: Evaluates the binary classification task's performance metrics (e.g., Precision, Recall, F1-score).

Some examples of fake clinical notes in Dutch can be found in the folder "Clinical notes examples (unprocessed)". 
