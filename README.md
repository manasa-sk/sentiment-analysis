# sentiment-analysis
The model for sentiment analysis uses data on financial statements and their sentiments.
It vectorizes the statements and uses multiple classifiers to compare their performances.
It visualizes their accuracies and implements the best Classifier.


All the statements are vectorized using CountVectorizer :

![image](https://user-images.githubusercontent.com/89377221/156470190-ea0da1a1-e332-4191-8edf-2f60829dc333.png)

Individual Classifiers are trained:
1. SVM:
  
  ![image](https://user-images.githubusercontent.com/89377221/156470487-7712411d-6f43-469f-aeba-9a7d827342f4.png)

2. Decision Tree:
  
  ![image](https://user-images.githubusercontent.com/89377221/156470563-745108e2-c663-4c51-b02b-6945fe4684b1.png)

3. Random Forest Classifier:
  
  ![image](https://user-images.githubusercontent.com/89377221/156470626-064f466b-08e9-4c73-9f4f-296cd879e9d3.png)

4. Multinomial Naive Bayes:
  
  ![image](https://user-images.githubusercontent.com/89377221/156470698-ffc29323-9ba5-4f05-ac21-64d7542a158e.png)

5. Multi-Layer Perceptron:
  
  ![image](https://user-images.githubusercontent.com/89377221/156470904-472d214e-63fa-4c8a-8603-9373340e51de.png)

6. Logistic Regression:

  ![image](https://user-images.githubusercontent.com/89377221/156470983-45a8b4fc-eca0-4aff-94b7-f694f0f17e47.png)

Stacked Classifiers are then trained and tested using combinations of the Classifiers above:

![image](https://user-images.githubusercontent.com/89377221/156471129-bed06e8f-1db1-4379-8b99-e0df8a3c30b0.png)

The accuracies of all the Classifiers are compared:

![image](https://user-images.githubusercontent.com/89377221/156471258-300f7e4f-41ac-41e4-b80a-0ba20bec37f1.png)

Following the results, Stacked Classifier combination is implemented:

![image](https://user-images.githubusercontent.com/89377221/156471352-c8e63853-a94d-4084-accf-77fba8b7a55e.png)
