<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Detection of Defective Solar Panels</title>
</head>
<body>
    <h1>Detection of Defective Solar Panels</h1>

    <h2>Objective</h2>
    <p>
        The objective of this project is to classify solar panels into "clean" or "unclean" categories and 
        further identify defect types in unclean panels, including:
        <ul>
            <li>Dust</li>
            <li>Physical damage</li>
            <li>Electrical damage</li>
            <li>Snow</li>
            <li>Bird droppings</li>
        </ul>
        The system is implemented using <strong>EfficientNet</strong> for efficient and accurate classification. 
        This enables early detection of faults, optimal energy output, and reduced maintenance costs.
    </p>

    <h2>Methodology</h2>
    <p>
        The project uses a two-stage classification system:
    </p>
    <ol>
        <li>
            <strong>Stage 1:</strong> Classify panels as "clean" or "unclean" using a sigmoid function.
        </li>
        <li>
            <strong>Stage 2:</strong> Further classify unclean panels into defect types using a softmax function.
        </li>
    </ol>
    <p>
        The implementation leverages a PyTorch-based workflow, including:
        <ul>
            <li>Image preprocessing (e.g., color filtering, feature enhancement).</li>
            <li>Segmentation and defect identification.</li>
            <li>Model evaluation with metrics like accuracy, recall, and precision.</li>
        </ul>
    </p>

    <h2>Contributions</h2>
    <p>
        Key contributions of this project include:
        <ul>
            <li>An end-to-end pipeline for dataset preprocessing, model training, and inference.</li>
            <li>A user-friendly interface for real-time image classification.</li>
            <li>Optimized classification accuracy through the use of ResNet and EfficientNet architectures.</li>
        </ul>
    </p>

    <h2>Results</h2>
    <p>
        The project achieved significant improvements in classification accuracy:
        <ul>
            <li>Improved accuracy from <strong>78%</strong> to <strong>89.9%</strong> using ResNet.</li>
            <li>Achieved <strong>90%</strong> accuracy for clean/unclean classification using EfficientNet.</li>
        </ul>
    </p>

    <h2>Flowchart</h2>
    <p>
        The system workflow includes:
        <ol>
            <li>Data acquisition (collecting images via cameras/drones).</li>
            <li>Preprocessing the images.</li>
            <li>Model selection (ResNet/EfficientNet).</li>
            <li>Training and performance evaluation.</li>
            <li>Classification and result visualization.</li>
        </ol>
    </p>

    <h2>How to Use This Repository</h2>
    <p>
        <ol>
            <li>Clone the repository to your local machine.</li>
            <li>Install the required dependencies from <code>requirements.txt</code>.</li>
            <li>Run the preprocessing script to prepare the dataset.</li>
            <li>Train the model using the provided training script.</li>
            <li>Use the inference script for real-time classification of solar panel images.</li>
        </ol>
    </p>

    <h2>Folder Structure</h2>
    <pre>
    ├── src/               # Python scripts for preprocessing, training, and evaluation
    ├── data/              # Sample datasets or data access instructions
    ├── notebooks/         # Jupyter notebooks for EDA and prototyping
    ├── models/            # Saved models and checkpoints
    ├── results/           # Outputs, metrics, and visualizations
    ├── docs/              # Documentation and flowcharts
    ├── requirements.txt   # List of dependencies
    └── README.md          # Project overview and usage instructions
    </pre>

    <h2>Technologies Used</h2>
    <ul>
        <li>Python</li>
        <li>PyTorch</li>
        <li>EfficientNet</li>
        <li>ResNet</li>
    </ul>

    <h2>License</h2>
    <p>
        This project is licensed under the <strong>[Your License Here]</strong>.
    </p>
</body>
</html>
