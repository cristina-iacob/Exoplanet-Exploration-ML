## ML - Exoplanet Exploration

Classification of exoplanets candidates

### Results

Random Forest is better than SVM, even without GridSearchCV.
***

### **SVM**

|                | Before GridSearchCV   | After GridSearchCV  |
| -------------- |:---------------------:| :------------------:|
| Training Score | 0.84550               | 0.88651             |
| Testing Score  | 0.84153               | 0.87929             |

---

### **Random Forest**

|                |  Before GridSearchCV  | After GridSearchCV  |
| -------------- |:---------------------:| :------------------:|
| Training Score | 0.99495               | 1.0                 |
| Testing Score  | 0.87643               | 0.89988             |

---

The least performant tried model was KNN with:
	Training score 0.840
	Testing score: 0.850
