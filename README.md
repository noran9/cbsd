# Cognitive, Behavioral and Social data project
### Dark triad dirty dozen

### Group members: Nora Nikoloska, Matteo Reddavide, Ellada Aslanova

For the purpose of the CBSD course, the Dark Triad Dirty Dozen dataset of honest and dishonest responses 
from 493 volunteers has been analyzed. The findings are reported in **report.pdf**.

Contents of the repository:

- **preprocessing_and_accuracy.ipynb** - Notebook for exploratory data analysis, computation of benchmark accuracy, generation of train and test data
- **raw_data_modified.csv** - The data used after removal of qualitative outliers
- **Color_dishonest.ipynb** and **Data_Transformation.ipynb** - Notebooks for generating 3D plots of responses according to dark triad disorders
- **classification.ipynb** - Comparison of classification methods using **train.csv** and **test.csv** as well as modified data: **tfidf_train_dataset.csv**
and **tf_idf_test_dataset.csv**
- Lists of predicted dishonest responses: **orignal_model_predicted_dishonest.csv** and **tf-idf_model_predicted_dishonest**
- **Reconstruction of honest profile.ipynb** - Comparison of regressors for reconstructing honest responses from the dishonest ones
- **tf_idf.ipynb** - Alternative implementation of TF-IDF not used in the analysis and comparison with the sklearn implementation
