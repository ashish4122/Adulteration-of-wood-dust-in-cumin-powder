DATASET-[Dataset for Adulterated Jeera Powder with Wood Dust](https://data.mendeley.com/datasets/dxrwf74ddx/1)

## **Overview**

Adulteration of food products, especially spices like Jeera powder, poses significant health risks. Traditional detection methods often fall short in identifying sophisticated adulterants. In this project, we leverage Convolutional Neural Networks (CNN) combined with machine learning classifiers like Random Forest and KNN to improve the accuracy and reliability of adulteration detection.

## **Approaches**

### **1. CNN + Random Forest**
- **Objective:** To leverage the feature extraction capabilities of CNN with the robust classification of Random Forest.
- **Method:** The CNN model processes the input data to extract high-level features, which are then fed into a Random Forest classifier for final prediction.

### **2. CNN + KNN**
- **Objective:** To combine the spatial feature extraction of CNN with the simplicity and efficiency of the KNN algorithm.
- **Method:** CNN extracts features, and KNN is used to classify the data based on the nearest neighbor approach.

### **3. CNN + KNN + Random Forest**
- **Objective:** To further enhance detection accuracy by integrating the strengths of both KNN and Random Forest with CNN.
- **Method:** Features extracted by CNN are first classified using KNN, and the results are then refined using Random Forest.

### **4. Model Integration for Optimal Results**
- **Objective:** To explore the benefits of model integration for more accurate and reliable detection.
- **Method:** The predictions from multiple models are integrated, leveraging ensemble techniques to improve overall performance.

## **Results**

Each approach has been rigorously tested, and the integration of models has shown promising improvements in the accuracy of detecting wood dust in Jeera powder. The combination of deep learning with machine learning classifiers has proven effective in enhancing detection capabilities.

## **Conclusion**

This project demonstrates the potential of combining CNN with traditional machine learning algorithms for detecting adulterants in food products. The integration of multiple models leads to more reliable and accurate results, which can be critical in ensuring food safety.
