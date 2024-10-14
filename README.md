# CNN CIFAR-10 Image Classification

This project was developed as part of my Master's program in Data Science and Artificial Intelligence. It focuses on classifying images from the CIFAR-10 dataset using Convolutional Neural Networks (CNNs). The primary goal was to achieve at least 80% accuracy on the test set through architectural modifications alone. I conducted a total of 12 experiments, exceeding the minimum requirement of 10 different experiments.

## Project Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes. The goal of this project was to enhance the performance of a very basic CNN model provided by the professors, implementing 12 different experiments (in addition to the baseline model) to improve its accuracy.

- **Baseline Accuracy**: 60.6% on the test set.
- **Best Accuracy without Data Augmentation**: 87.7%.
- **Best Overall Accuracy**: 90.7% using Data Augmentation.
- **Transfer Learning**: The final experiment applied VGG-16, achieving lower accuracy than the augmented CNN. Future improvements will focus on better applying transfer learning.

## Key Skills Demonstrated

- **Deep Learning**: Implementation and optimization of CNN architectures.
- **Model Optimization**: Techniques like dropout, batch normalization, and data augmentation.
- **Data Augmentation**: Applied to improve model generalization and performance.
- **Transfer Learning**: Initial exploration using VGG-16, with plans to improve this aspect in future work.
- **Keras**: All models and experiments were implemented using the Keras library.

## Repository Structure

- `/notebooks`: Jupyter notebooks for each experiment conducted, detailing modifications and results.
- `/docs`: Final project report (PDF) with detailed explanations of each experiment, results, and future developments.

## Dataset

The CIFAR-10 dataset is available through [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/cifar10) or can be downloaded from the [official page](https://www.cs.toronto.edu/~kriz/cifar.html).

## Results and Future Work

The project successfully reached an accuracy of 90.7% using Data Augmentation. However, there is still room for improvement, especially in the area of **Transfer Learning**. The VGG-16 model used in the final experiment did not surpass the results obtained with Data Augmentation, and further study in this area could yield better results.

---

**Feel free to reach out for any questions or further discussions!**

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

