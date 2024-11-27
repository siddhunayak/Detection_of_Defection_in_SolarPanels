# Detection of Defective Solar Panels

## Objective
The objective of this project is to classify solar panels into "clean" or "unclean" categories and further identify defect types in unclean panels, including:
- Dust
- Physical damage
- Electrical damage
- Snow
- Bird droppings

The system is implemented using **EfficientNet** for efficient and accurate classification. This enables early detection of faults, optimal energy output, and reduced maintenance costs.

## Methodology
The project uses a two-stage classification system:

1. **Stage 1:** Classify panels as "clean" or "unclean" using a sigmoid function.
2. **Stage 2:** Further classify unclean panels into defect types using a softmax function.

The implementation leverages a PyTorch-based workflow, including:
- Image preprocessing (e.g., color filtering, feature enhancement).
- Segmentation and defect identification.
- Model evaluation with metrics like accuracy, recall, and precision.

## Contributions
Key contributions of this project include:
- An end-to-end pipeline for dataset preprocessing, model training, and inference.
- A user-friendly interface for real-time image classification.
- Optimized classification accuracy through the use of ResNet and EfficientNet architectures.

## Results
The project achieved significant improvements in classification accuracy:
- Improved accuracy from **78%** to **89.9%** using ResNet.
- Achieved **90%** accuracy for clean/unclean classification using EfficientNet.

## Flowchart
The system workflow includes:
1. Data acquisition (collecting images via cameras/drones).
2. Preprocessing the images.
3. Model selection (ResNet/EfficientNet).
4. Training and performance evaluation.
5. Classification and result visualization.

## How to Use This Repository
1. Clone the repository to your local machine.
2. Install the required dependencies from `requirements.txt`.
3. Run the preprocessing script to prepare the dataset.
4. Train the model using the provided training script.
5. Use the inference script for real-time classification of solar panel images.

## Folder Structure
