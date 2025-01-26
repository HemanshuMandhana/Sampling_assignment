| Sampling Method       | Random Forest | Logistic Regression | Decision Tree | KNN    | SVM    | Best Model           |
|-----------------------|---------------|---------------------|---------------|--------|--------|----------------------|
| Simple Random Sampling| 1.0000        | 0.9248              | 0.9739        | 0.9641 | 0.6503 | Random Forest         |
| Stratified Sampling   | 0.9967        | 0.9216              | 0.9837        | 0.9608 | 0.6471 | Decision Tree         |
| Clustered Sampling    | 1.0000        | 0.9281              | 0.9804        | 0.9575 | 0.6438 | Random Forest         |
| Systematic Sampling   | 0.9837        | 0.8987              | 0.9608        | 0.9248 | 0.6765 | Random Forest         |
| Bootstrap Sampling    | 1.0000        | 0.9379              | 0.9804        | 0.9771 | 0.7157 | Random Forest         |

Best Model for Each Sampling Method:
Simple Random Sampling: Random Forest (Accuracy = 1.0000)
Stratified Sampling: Decision Tree (Accuracy = 0.9837)
Clustered Sampling: Random Forest (Accuracy = 1.0000)
Systematic Sampling: Random Forest (Accuracy = 0.9837)
Bootstrap Sampling: Random Forest (Accuracy = 1.0000)
