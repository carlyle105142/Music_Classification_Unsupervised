# Music_Classification_Unsupervised
Dimension Reduction, K-Means Clustering

This project was completed as a UC Davis  coursework under supervision of Prof. Wolfgang. The data is provided as course material and the analysis
conducted was based on unsupervised learning techniques taught in class.

Some feature extraction was completed first with 'librosa', a Python package designed to deal with audio data.
Several manifold learning methods are then applied to reduce the dimensionality of the audio feature data in order to visually check cluster structures.
The best dimension reduction method was used for K-Means algorithm to run on the 2-dimensional approximate of the feature vectors.
Silhouette score was used to evaluate the result of the clustering.
For more detials please check the notebook file.
