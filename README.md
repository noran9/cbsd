# Cognitive, Behavioral ans Social data project
### Dark triad dirty dozen

### Group members: Nora Nikoloska, Matteo Reddavide, Ellada Aslanova

For the purpose of the CBSD course, the Dark Triad Dirty Dozen dataset of honest and dishonest responses 
from 493 volunteers has been analyzed. The findings are reported in **report.pdf**.

Contents of the repository:

- preprocessing_and_accuracy.ipynb - Notebook for exploratory data analysis, computation of benchmark accuracy, generation of train and test data
- raw_data_modified.csv - The data used after removal of qualitative outliers
- classification.ipynb - Comparison of classification methods using **train.csv** and **test.csv** as well as modified data: **tfidf_train_dataset.csv**
and **tf_idf_test_dataset.csv**
- tf_idf.ipynb - Alternative implementation of TF-IDF not used in the analysis and comparison with the sklearn implementation
