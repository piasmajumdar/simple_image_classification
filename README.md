
# Image Classifier for Simple Objects

This repository contains the code and resources for training an image classification model that categorizes outdoor scene images into six classes: **buildings**, **forest**, **glacier**, **mountain**, **sea**, and **street**. The model is implemented using the FastAI library with a ResNet-18 backbone and trained on the Intel Image Classification dataset.

---

## 📁 Repository Structure

```
├── Data/
│   └── train.txt # Link is given here 
├── notebooks/
│   └── image\_classifier.ipynb   # Jupyter notebook with end-to-end implementation
├── slides/
│   └── Image\_Classifier\_Presentation.pptx   # Project PPT
├── README.md              # This file

````

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher  
- GPU-enabled environment (optional but recommended)  
- At least 8 GB RAM  

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/image-classifier-simple-objects.git
   cd image-classifier-simple-objects
   ````

2. **Create a virtual environment (optional)**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
Here's a polished version suitable for inclusion in a `README.md` file:

---

### 🖼️ Dataset Overview

* **Number of Classes:** 6

  * `Buildings`, `Forest`, `Glacier`, `Mountain`, `Sea`, `Street`
* **Image Type:** RGB (`.jpg`)
* **Input Image Size:** Resized to `224x224` pixels
* **Total Images:** \~25,000+
* **Source:** [Kaggle - Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)

### 📁 Dataset Structure

After downloading and extracting the dataset, place the folders as follows:

```
data/
├── seg_train/
└── seg_test/
```

Each folder contains subdirectories for the 6 classes, each filled with labeled images.

---

Let me know if you’d like a code snippet to automate the download or preprocessing steps.


## 🛠 Usage

1. **Launch the Jupyter notebook**

   ```bash
   jupyter notebook notebooks/image_classifier.ipynb
   ```

2. **Run the cells** in order:

   * Data loading & preprocessing
   * Learning rate finder
   * Model training & fine-tuning
   * Evaluation & visualization
   * Exporting the trained model

---

## 📈 Results

* **Validation Accuracy:** > 93%
* **Key Visualizations:**

  * Confusion matrix
  * Top loss examples
  * Sample predictions

---
