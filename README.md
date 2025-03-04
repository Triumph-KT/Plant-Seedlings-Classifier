# Plant Seedlings Classification Using Convolutional Neural Networks (CNN)

Developed a deep learning system to classify RGB images of plant seedlings into 12 species using Convolutional Neural Networks (CNN), leveraging advanced image preprocessing, data augmentation, and regularization techniques to optimize model accuracy and generalization.

## Project Overview

This project applies deep learning techniques to agricultural image data, automating the classification of plant seedlings. By designing and training a custom CNN architecture with preprocessing strategies like HSV color space conversion and masking, the model accurately identifies plant species to support real-world applications in precision agriculture and automated crop monitoring.

## Dataset

The **Plant Seedlings dataset** contains:
- **4,750 RGB images** of size **128x128 pixels**.
- Each image represents one of **12 plant species** at various growth stages.
- 12 plant species:
  - Black-grass
  - Charlock
  - Cleavers
  - Common Chickweed
  - Common Wheat
  - Fat Hen
  - Loose Silky-bent
  - Maize
  - Scentless Mayweed
  - Shepherds Purse
  - Small-flowered Cranesbill
  - Sugar beet

## Objectives

- Preprocess RGB images with noise reduction, color space transformation, and masking.
- Build and train a deep CNN for multi-class plant species classification.
- Apply data augmentation and regularization techniques to prevent overfitting.
- Optimize model performance through learning rate adjustments and hyperparameter tuning.
- Evaluate and visualize model accuracy and learning dynamics.

## Methods

### Data Preprocessing:
- Converted RGB images to **HSV color space** to isolate key color features.
- Applied **Gaussian blurring** to reduce noise.
- Created **masks** to filter backgrounds and enhance seedling visibility.
- Performed **one-hot encoding** of categorical species labels.
- Visualized sample images before and after preprocessing.

### Model Development:
- Designed a custom CNN architecture with:
  - **6 convolutional layers** using 
