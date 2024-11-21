# Fashion Product Recommendation System

This project demonstrates a simple **Fashion Product Recommendation System** that uses a pre-trained **ResNet50** model to extract image features and calculate similarity between a target image and product images. The application ranks and recommends the most similar products to the target.

---

## **Features**
- Automatically downloads the **Fashion Product Images Small** dataset from Kaggle.
- Uses **ResNet50** for feature extraction.
- Ranks product images by cosine similarity to the target image.
- Displays the recommended images with their similarity scores.

---

## **Technologies Used**
- **Python 3.8+**
- **TensorFlow** (Deep Learning Framework)
- **ResNet50** (Pre-trained model)
- **Matplotlib** (Image visualization)
- **KaggleHub** (Dataset download)
- **Scikit-learn** (Cosine similarity calculation)

---

## **Getting Started**

### **Prerequisites**
1. Python environment with the following libraries:
    ```bash
    pip install tensorflow matplotlib kagglehub
    ```
2. Kaggle API key:
   - Download your Kaggle API key (`kaggle.json`) from your Kaggle account settings.
   - Place the file in `~/.kaggle/` or the root directory of your project.

---

### **Usage**

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/fashion-recommendation-system.git
    cd fashion-recommendation-system
    ```

2. Run the script:
    ```bash
    python main.py
    ```

3. View the recommendations:
    - The script will download the dataset, process the images, and display recommendations ranked by similarity.

## **Output**

The script outputs a visualization of the target image alongside recommended products with their similarity scores, as shown below:

| Target Image                | Recommendations                   |
|-----------------------------|------------------------------------|
| ![target](example_target.jpg) | ![product1](example_product1.jpg), ![product2](example_product2.jpg) |

---

## **Acknowledgments**
- **Dataset**: [Fashion Product Images Small](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)
- **Model**: [ResNet50](https://keras.io/api/applications/resnet/)

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it as needed.
