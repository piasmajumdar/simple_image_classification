
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

### Dataset

Download the Intel Image Classification dataset from Kaggle and place the folders under `data/`:

* `data/seg_train/`
* `data/seg_test/`

---

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
