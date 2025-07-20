# 🧥👗 Fashion Multi-Task Classification

A deep learning project for **multi-task prediction** on fashion product images.  
This model simultaneously predicts several attributes from a single clothing image, including:

- **Gender**
- **Master Category**
- **Subcategory**
- **Article Type**
- **Base Colour**
- **Season**
- **Usage**

<br/>

## 📂 Dataset

- Source: [Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)
- Preprocessed to remove missing/invalid samples.
- Used only valid samples with complete labels and images.

Note:
Please upload the dataset to your own Google Drive and update the path accordingly in the notebook.

<br/>

## 🚀 Project Structure

```
fashion-multitask-classification/
│
├── fashion_multilabel.ipynb        # Main Jupyter/Colab notebook
├── requirements.txt                # List of required packages
├── README.md                       # This file!
└── (Optional: sample images, saved models, etc.)
```

<br/>

## 🛠️ How to Run

1. **Clone or download** the repository.
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook (`fashion_multilabel.ipynb`) in Google Colab or Jupyter.
4. Follow the step-by-step instructions in the notebook to preprocess data, train, and evaluate the model.

> **Note:**  
> The full dataset is not included due to size. Please download it separately and set the data path as described in the notebook.

<br/>

## 📊 Model

- Built with TensorFlow/Keras (CNN multi-head architecture)
- Multi-label (multi-task) output: predicts all tags at once
- Evaluated with per-label accuracy and error analysis

<br/>

## 📈 Visualizations & Error Analysis

The notebook includes:
- Class distribution plots for each label
- Training & validation accuracy/loss curves
- Confusion matrices and sample error analysis

<br/>

## License

This project is for educational purposes.  
Feel free to use, modify, and share with reference to the author!

## 🤝 Author

**Shayan Salehi**
Email: shayansalehisut@gmail.com

