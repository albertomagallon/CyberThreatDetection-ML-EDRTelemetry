# CyberThreatDetection-ML-EDRTelemetry

This repository contains the code for the project "Enhancing Cyber Threat Detection using Machine Learning on EDR Telemetry." The project aims to improve threat detection accuracy and efficiency in Endpoint Detection and Response (EDR) systems by leveraging machine learning models trained on client-specific telemetry data. The implementation follows the CRISP-DM methodology.

## Project Overview

The primary goal of this project is to enhance the detection of cyber threats by using machine learning models on telemetry data collected from EDR systems. By customizing the models to the specific environment of the client, we achieve more accurate threat detection and reduce false positives.

## Repository Contents

- `CyberThreatDetection_EDR_Telemetry.ipynb`: Jupyter Notebook containing the anonymized code for training and evaluating the machine learning models.
- `data/Sampled_Anonymized_Subset.csv`: Anonymized sample dataset used for training and testing the models.
- `README.md`: Project documentation.

## Setup Instructions

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/CyberThreatDetection-ML-EDRTelemetry.git
    cd CyberThreatDetection-ML-EDRTelemetry
    ```

2. **Install required dependencies**:
    Make sure you have Python 3 and `pip` installed. Then, install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

3. **Launch Jupyter Notebook**:
    ```sh
    jupyter notebook
    ```
    Open the `CyberThreatDetection_EDR_Telemetry.ipynb` notebook in the Jupyter interface.

## Usage

Open the Jupyter Notebook and follow the steps provided to train and evaluate the machine learning models on the anonymized dataset. The notebook includes sections for data loading, preprocessing, model training, and evaluation.

## Methodology

The project follows the CRISP-DM methodology, which includes the following phases:
1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Modeling**
5. **Evaluation**
6. **Deployment**

## Data

The dataset used in this project is an anonymized sample of telemetry data from an EDR system. It includes various features related to threat detection, such as threat identifiers, classification, confidence levels, and timestamps.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for any changes or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
