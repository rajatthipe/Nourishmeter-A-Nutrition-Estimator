# 🥗 Nourishmeter: A Nutrition Estimator

**Nourishmeter** is an intelligent system that estimates the nutritional content of food from images using deep learning. This project employs Convolutional Neural Networks (CNNs) to identify food items and compute approximate calorie values, offering a smart solution for dietary tracking and analysis.

---

## 🚀 Features

- 📷 **Image-Based Food Recognition**  
  Upload a food image and let the model predict the food category.

- 🔢 **Calorie Estimation**  
  Calculates calorie content based on the predicted food class.

- 🧠 **Convolutional Neural Network (CNN)**  
  Leverages a deep learning model for accurate classification.

- 🧪 **Demo Ready**  
  Includes demonstration scripts to test the functionality easily.

- 🔌 **Modular Architecture**  
  Organized codebase for easy maintenance and enhancement.

---

## 🧠 Methodology

The Nourishmeter system follows this pipeline:

1. **Image Acquisition**  
   The user provides a food image as input.

2. **Preprocessing**  
   Image is resized, normalized, and converted into a suitable format for the model.

3. **Food Classification**  
   A CNN model processes the image and predicts the food item class (e.g., pizza, salad, burger).

4. **Nutritional Estimation**  
   Based on the food class, the corresponding average calorie content is retrieved from a predefined dataset or dictionary.

5. **Output**  
   The system returns the estimated calorie content and optionally other nutritional information.

---

## 🧰 Model Used

- **Architecture**: Convolutional Neural Network (CNN)  
- **Framework**: TensorFlow / Keras  
- **Input**: RGB food image  
- **Output**: Predicted food class → Estimated calories  

The model is trained on a dataset of labeled food images and optimized for generalization across common food categories.

---

## 📁 Project Structure

