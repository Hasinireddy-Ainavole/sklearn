# sklearn

## Name : Ainavole Hasini Reddy
## Student Id : 700773828

## Q7: Build a Decision Tree (sklearn)

Max Depth 1: Train Accuracy = 0.6476, Test Accuracy = 0.7111  
Max Depth 2: Train Accuracy = 0.9429, Test Accuracy = 0.9778  
Max Depth 3: Train Accuracy = 0.9524, Test Accuracy = 1.0000  

**Analysis:**  
- **Depth 1:** Likely underfitting – simple model, both accuracies relatively low  
- **Depth 2-3:** Better balance – good performance without excessive complexity  
- Generally, if **train accuracy >> test accuracy**, it indicates **overfitting**  
- If both accuracies are **low**, it suggests **underfitting**  


## Q8: kNN Classification (sklearn)

 **Decision Boundary Analysis:**  
- **k=1:** Very complex, jagged boundaries – prone to overfitting  
- **k=3:** Smoother boundaries while capturing class structure  
- **k=5:** Even smoother, more generalized boundaries  
- **k=10:** Very smooth boundaries – may be too simple (underfitting)  

 As **k** increases, boundaries become smoother and more generalized  


<img width="1189" height="990" alt="image" src="https://github.com/user-attachments/assets/1485c232-1c03-42d7-b85a-212c56b6fddf" />




## Q9: Performance Evaluation Programming

<img width="653" height="547" alt="image" src="https://github.com/user-attachments/assets/d3975ddc-1b50-41a4-aa70-64ef5c2c74bb" />

## Confusion Matrix

[[19  0  0]
 [ 0 13  0]
 [ 0  0 13]]

## Classification Report

| Class       | Precision | Recall | F1-Score | Support |
|-------------|-----------|--------|----------|---------|
| Setosa      | 1.00      | 1.00   | 1.00     | 19      |
| Versicolor  | 1.00      | 1.00   | 1.00     | 13      |
| Virginica   | 1.00      | 1.00   | 1.00     | 13      |
| **Accuracy**|           |        | **1.00** | **45**  |
| Macro Avg   | 1.00      | 1.00   | 1.00     | 45      |
| Weighted Avg| 1.00      | 1.00   | 1.00     | 45      |



<img width="857" height="701" alt="image" src="https://github.com/user-attachments/assets/2c78761d-1b58-4844-ac9c-fc6e49593241" />



## AUC Values

- **Setosa:** 1.0000  
- **Versicolor:** 1.0000  
- **Virginica:** 1.0000  
- **Macro-average AUC:** 1.0000  



