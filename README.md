This project focuses on diagnosing diseases in cassava plants, a vital staple crop in Uganda, using images from a Kaggle dataset. The goal is to classify plants as healthy or affected by one of four diseases. Key features include data preprocessing (normalization, resizing, and balancing classes), CNN-based model training, and addressing challenges like overfitting. This solution aims to help farmers quickly identify crop issues and improve yield sustainability.
**In the 022-explore-dataset we will find**
Our data needs to be loaded and processed
We can normalize our data to help our models
If we have unbalanced classes, our model might favor one class over another
We can correct this by undersampling, throwing away data in the larger classes
**In the 023-multiclass-classification:**
Once more we preprocessed our data to make it ready for deep learning.
We built a CNN with 3 convolutional and max pooling layers, followed by flattening and two dense layers.
We used nn.Sequential to easily build our model's architecture by defining the order of the layers.
Training the model for too many epochs produced an overfit model.
We discussed techniques to combat overfitting, which we'll see in future lessons.
