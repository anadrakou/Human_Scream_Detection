# Human Scream Detection

<img src="https://www.britishmuseum.org/sites/default/files/styles/uncropped_small/public/Edvard-Munch-The-Scream-Final-735x1024.jpg?itok=dKfpfxjn" alt="Project Logo" align="right" style="margin-left: 20px; width: 25%;">
    The Human Screaming Detection Dataset is a specialized collection focusing solely on identifying and analyzing human screams. This dataset is invaluable for developing machine learning models in critical areas such as security, healthcare, and emergency response. In today's world, where timely intervention can save lives, the ability to detect screams efficiently is paramount. For instance, in security, rapid scream detection can alert authorities to potential assaults or emergencies, enabling faster response times. In addition to traditional video surveillance, various audio processing techniques can also be added to existing CCTV cameras. These enhancements serve as additional features to help analyze the scene better and autonomously detect violence or any unwanted activity. In healthcare, scream detection can be used to monitor patients in distress, particularly in scenarios where immediate human intervention might not be feasible. Overall, the dataset plays a crucial role in advancing technologies that enhance safety and provide timely assistance in urgent situations. <br>
    The goal of this project is to develop and optimize deep learning models for human scream detection. By experimenting with various architectures and techniques, we aim to identify the most effective model for accurately detecting screams. This involves training, validating, and testing models on relevant datasets to ensure robustness and reliability. Ultimately, the objective is to enhance real-world applications such as security and emergency response systems by integrating the best-performing model into these frameworks.
<br> <br>

### Table of Contents
- [Files of the Project](#files-of-the-project)
- [Libraries and Dependencies](#libraries-and-dependencies)
- [Datasets](#datasets)
- [Project Contributors](#project-contributors)
- [Contact Information](#contact-information)
- [Acknowledgements](#acknowledgements)
<br>
  
### Files of the Project
- `Load_and_Preprocess_EDA.ipynb` : Load and preprocess our audio data into 17 features for EDA.
- `EDA.ipynb` : Exploratory Data Analysis of our main dataset.
- `Load_and_Preprocess.ipynb` : Load and Preprocess of our audio data into 128 me spectograms
- `SVM.ipynb` : A machine learning algorithm, SVM, will be used as a baseline to compare the metrics with deep learning models
- `FNN.ipynb` : Fully Connected Neural Network
- `CNN.ipynb` : Convolutional Neural Network
- `CNN_Regularization.ipynb` : Convolutional Neural Network with Regularizations
- `CNN_f1_score_callbacks.ipynb` : Convolutional Neural Network woth F1 score in callbacks
- `ResNet.ipynb` : Transfer learning model
- `Deploy_Load_and_Preprocess.ipynb` : Load and Preprocess of the deployment dataset
- `Deploy_Resnet.ipynb` : Running a transfer learning model to the deployment dataset
- `report.ipynb` : Results, insights and conclusions of our project
<br>

### Libraries and Dependencies
- **`tensorFlow`**: An open-source machine learning framework.
- **`librosa`**: A python package for music and audio analysis.
- **`python 3`**: The programming language used for this project.
- **`matplotlib`**: A plotting library for the Python programming language.
- **`numpy`**: Used for numerical operations.
<br>

### Datasets 
**Dataset :** The dataset utilized in this analysis was sourced from Kaggle. The link to access the dataset is provided: [Kaggle Dataset](https://www.kaggle.com/datasets/whats2000/human-screaming-detection-dataset/data)  
<br>
**Noise Dataset :** The noise dataset utilized in this project for data augmentation was obtained from a specialized sound engineer.  <br>

**Deployment Dataset :** The dataset utilized in this analysis was sourced from two different Kaggle datasets. The link to access the dataset is provided: for Screaming : [Kaggle Dataset 1](https://www.kaggle.com/datasets/sanzidaakterarusha/scream-dataset) and for Not Screaming : [Kaggle Dataset 2](https://www.kaggle.com/datasets/chrisfilo/urbansound8k) + [Kaggle Dataset 3](https://www.kaggle.com/datasets/vishnu0399/emergency-vehicle-siren-sounds?resource=download).    
<br>


### Project Contributors

| Name           | Registration Number                | GitHub Profile                              |
|----------------|---------------------|---------------------------------------------|
| Anastasia Drakou     | 2022202304006      | [anadrakou](https://github.com/anadrakou) |
| Aikaterini Karathanou       | 2022202304009     | [kathrinka](https://github.com/kathrinka)     |

### Contact Information
If you have any questions or suggestions, feel free to contact us at a.drakou@hotmail.com and katerinakarathanou26@gmail.com.

### Acknowledgements
- [TensorFlow](https://www.tensorflow.org/): An open-source machine learning framework.
- [Librosa](https://librosa.org/): A python package for music and audio analysis.
- [Python 3](https://www.python.org/): The programming language used for this project.
- [Matplotlib](https://matplotlib.org/): A plotting library for the Python programming language.
- [Numpy](https://numpy.org/): Used for numerical operations.
<br>
