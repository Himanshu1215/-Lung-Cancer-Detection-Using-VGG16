# Lung Cancer Detection Using VGG16

## Description

Developed a robust Lung Cancer Detection system utilizing transfer learning with the VGG16 model to classify lung cancer cases from CT scan images. The project leverages the IQOTHNCCD Lung Cancer dataset to train the model, enhancing its ability to accurately differentiate between malignant, benign, and normal cases.

## Key Features

- **Transfer Learning with VGG16:** Utilized the pre-trained VGG16 model, applying transfer learning techniques to adapt the model for lung cancer classification, significantly improving training efficiency and accuracy.
- **Comprehensive Dataset:** Employed the IQOTHNCCD Lung Cancer dataset, consisting of CT scan images categorized into malignant, benign, and normal cases.
  - **Dataset Distribution:** Malignant cases: 561, Normal cases: 416, Benign cases: 120.
- **Model Training and Fine-Tuning:** Fine-tuned the VGG16 model to achieve optimal performance in lung cancer detection, ensuring high accuracy and robustness in diverse conditions.
- **Evaluation and Validation:** Conducted thorough evaluation and validation of the model using various metrics to ensure reliable lung cancer classification.

## Technologies Used

- Python
- TensorFlow/Keras
- VGG16
- IQOTHNCCD Lung Cancer Dataset
- OpenCV (for image processing and augmentation)

## Achievements

- Successfully implemented a lung cancer detection system with high accuracy and reliability.
- Demonstrated proficiency in deep learning, transfer learning, and medical image analysis techniques.
- Developed a practical application with potential uses in medical diagnosis and healthcare.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/adityamahimkar/iqothnccd-lung-cancer-dataset.git
    cd iqothnccd-lung-cancer-dataset
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Download and prepare the IQOTHNCCD Lung Cancer dataset:
    - Ensure the dataset is structured correctly within the project directory.

2. Run the training script:
    ```sh
    python train.py
    ```

3. Evaluate the model:
    ```sh
    python evaluate.py
    ```

4. Use the model for lung cancer detection:
    ```sh
    python detect_lung_cancer.py --image path_to_image
    ```

## Training Results

- **Epochs:** 50
- **Best Performance:** Achieved at epoch 22
  - **Training Loss:** 0.2617
  - **Training Accuracy:** 91.13%
  - **Validation Loss:** 0.2529
  - **Validation Accuracy:** 89.70%
  - **Learning Rate:** 1.0000e-04

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or further information, feel free to contact me via [LinkedIn](https://www.linkedin.com/in/himanshhuu/).

---

**Link to Project Repository:** [GitHub](https://github.com//Himanshu1215/-Lung-Cancer-Detection-Using-VGG16)
