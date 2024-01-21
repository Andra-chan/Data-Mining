# Data-Mining
Sentiment analysis in text project for Data Mining Master course (2023-2024)


  Our project is focusing on sentiment analysis in text, specifically movie reviews written in Romanian. Our implementation is capable of classifying the overall sentiment behind a review as either positive or negative, based on the words used. Additionally, a scale between 0 and 1 is in place to determine how positive or negative a sentence is, this way also classifying the neutral sentences.

  Our project is written in Python, using Jupyter Notebook. The main requirement is for Python 3.11 to be installed, being available in the Microsoft Store.
![image](https://github.com/Andra-chan/Data-Mining/assets/80649212/52340a48-5c83-44b7-9ed6-bb0482e7cd3d)

  Additionally, Jupyter Notebook needs to be downloaded via cmd, using “pip install jupyter notebook”. Furthermore, we can launch the application using “python -m notebook”.
  
  The “ipynb” file can be imported into the notebook, where we can find the runnable code. The dataset can be found under the following Github: https://github.com/katakonst/sentiment-analysis-tensorflow/tree/master/datasets.
  
  Every cell in the notebook needs to be executed in order to see the results. The following libraries need to be installed in order to have no errors when running the code:
-	pip install pandas
-	pip install matplotlib
-	pip install scikit-learn
-	pip install lime
-	nltk.download(‘stopwords’)
-	nltk.download(‘punkt’)
-	pip install tensorflow

After these commands have been run, we can execute the cells, in order, from top to bottom. 
Note: The Neural Network model training takes approximately 20-30 minutes. :)
