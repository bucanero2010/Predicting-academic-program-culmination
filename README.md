# Predicting-academic-program-culmination

Challenge taken from 2020 Maratona Behind the Code from IBM. Several datasets were provided in order to solve this problem, each of those gave a piece of information of the student's academic record. Merging these datasets effectively and creating valuable variables for the model was essential to obtaing a good F1 score. Oversampling techniques were also applied to account for the fact that the target class was highly unbalanced.

1. ForTraining contains StudentId, academic program and semester.
2. TablaConexiones contains metrics from the institute's virtual platform.
3. TablaTareas contains homework grades and status.
4. OrdenMaterias contains information about the academic program and its courses.
5. ToBePredicted has the Ids to be predicted with the trained model.
6. Anahuac is the notebook including EDA and modeling.
