### Qns

- [Q1: k-Nearest Neighbor classifier](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/knn.ipynb) 🤣
  [[Notes]](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/Q1.%20KNN.pdf)
- [Q2: Training a Support Vector Machine](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/svm.ipynb)
- [Q3: Implement a Softmax classifier](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/softmax.ipynb)
- [Q4: Two-Layer Neural Network](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/two_layer_net.ipynb)
- [Q5: Higher Level Representations: Image Features](https://github.com/Yuxinn-J/CS231n/blob/main/assignment1/features.ipynb)

### Goals

In this assignment you will practice putting together a simple image classification pipeline based on the k-Nearest Neighbor or the SVM/Softmax classifier. The goals of this assignment are as follows:

- Understand the basic **Image Classification pipeline** and the data-driven approach (train/predict stages)
- Understand the train/val/test **splits** and the use of validation data for **hyperparameter tuning**.
- Develop proficiency in writing efficient **vectorized** code with numpy
- Implement and apply a k-Nearest Neighbor (**kNN**) classifier
- Implement and apply a Multiclass Support Vector Machine (**SVM**) classifier
- Implement and apply a **Softmax** classifier
- Implement and apply a **Two layer neural network** classifier
- Understand the differences and tradeoffs between these classifiers
- Get a basic understanding of performance improvements from using **higher-level representations** as opposed to raw pixels, e.g. color histograms, Histogram of Gradient (HOG) features, etc.

### Download CIFAR-10. Run the following from the assignment1 directory:

```bash
cd cs231n/datasets
bash get_datasets.sh
```
