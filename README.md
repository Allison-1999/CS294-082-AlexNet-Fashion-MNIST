# CS294-082-AlexNet-Fashion-MNIST
This project is about Compression and Memory Equivalent Capacity Estimate of AlexNet 
## Author
- Jingjing Wei, Fang Hu, Yonghao Zhu
- University of California Berkeley, Berkeley, CA, USA
- {jingjingwei, fanghu, yonghao_zhu}@berkeley.edu
## Introduction
- In this project, we customize the AlexNet and analyze its experimental properties. The dataset used in the paper is Fashion MNIST. We chose three classes to train and test our model, including 0 (T-shirt), 1 (Trouser), and 2 (Pullover). Also, we performed random data sampling.
- Two experiments were studied in this paper. (1) Accuracy vs. Memory Equivalent Capacity. (2) The proportion of Training Data vs. MEC(Overfitting).
- Based on the result, we discuss multiple properties of our machine learner, including memory equivalent capacity, generalization, resilience, etc., by adjusting the number of neurons of fully connected layers. The capacity of the dataset and model are further explored. Moreover, we discuss our experiment's quality assurance, repeatability, and reproducibility.
