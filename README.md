# nearest-neighbor-algorithm-for-classification-tasks
Creating a model class for classification tasks using the nearest neighbor algorithm. We have created a machine learning method that does not make use of sklearn. 

We have data from the website of a real estate agency. The target variable is air conditioner: apartment has air conditioner-(1); no air conditioner-(0).
We have created a class <code>NearestNeighborClassificator</code> which contains methods <code>fit()</code> and <code>predict()</code>. <code>fit()</code> stores the entire training set while <code>predict()</code> uses the <code>nearest_neighbor_predict()</code> function to predict the value.
