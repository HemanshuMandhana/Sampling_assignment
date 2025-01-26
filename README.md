| Sampling Method       | Random Forest | Logistic Regression | Decision Tree | KNN    | SVM    |
|-----------------------|---------------|---------------------|---------------|--------|--------|
| Simple Random Sampling| 1.0000        | 0.9248              | 0.9739        | 0.9641 | 0.6503 |
| Stratified Sampling   | 0.9967        | 0.9216              | 0.9837        | 0.9608 | 0.6471 |
| Clustered Sampling    | 1.0000        | 0.9281              | 0.9804        | 0.9575 | 0.6438 |
| Systematic Sampling   | 0.9837        | 0.8987              | 0.9608        | 0.9248 | 0.6765 |
| Bootstrap Sampling    | 1.0000        | 0.9379              | 0.9804        | 0.9771 | 0.7157 |

# Best Sampling Method for Each Model

This document summarizes the best-performing sampling method for each machine learning model based on their accuracy scores.

## Results

| Model                | Best Sampling Method | Accuracy |
|----------------------|----------------------|----------|
| Random Forest        | Simple Random Sampling| 1.0000   |
| Logistic Regression  | Bootstrap Sampling    | 0.9379   |
| Decision Tree        | Stratified Sampling   | 0.9837   |
| KNN                  | Bootstrap Sampling    | 0.9771   |
| SVM                  | Systematic Sampling   | 0.7157   |

## Key Insights
1. **Random Forest** performs best with **Simple Random Sampling**, achieving perfect accuracy (1.0000).
2. **Logistic Regression** excels with **Bootstrap Sampling**, reaching an accuracy of 0.9379.
3. **Decision Tree** performs optimally with **Stratified Sampling**, with an accuracy of 0.9837.
4. **KNN** shows its best performance with **Bootstrap Sampling**, scoring an accuracy of 0.9771.
5. **SVM** performs best with **Systematic Sampling**, although it achieves lower accuracy (0.7157) compared to other models.

### Conclusion
Each model has its own optimal sampling method, with **Random Forest** showing the strongest overall performance across different sampling strategies.

