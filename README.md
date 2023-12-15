# K-Means Clustering with Multiple Distance Metrics

This Python script performs K-Means clustering on a given dataset using Euclidean, Cosine, and Jaccard distance metrics. The code includes data preprocessing, clustering implementation, SSE (Sum of Squared Errors) calculation, and accuracy assessment.

## Requirements

- Python 3
- Pandas
- NumPy
- Scikit-learn

## Usage

1. **Data Preparation:**
   - Ensure you have the required dataset (`data.csv`) and labels (`label.csv`) in the same directory as the script.

2. **Run the Script:**
   - Execute the Python script in a Python environment that has the necessary libraries installed.

   ```bash
   python kmeans_clustering.py
## Code Overview

- **Data Loading:**
  - The script reads the dataset from `data.csv` using Pandas.

- **Data Scaling:**
  - The script scales the data to the range (0, 1).

- **Random Centroids Initialization:**
  - Random centroids are initialized for the K-Means algorithm.

- **Clustering:**
  - K-Means clustering is performed with Euclidean, Cosine, and Jaccard distance metrics.

- **SSE Calculation:**
  - SSE is calculated for each distance metric.

- **Accuracy Assessment:**
  - Majority voting is applied to assign labels, and accuracy is calculated for each distance metric.
## Results

The script provides the SSE for each distance metric and the accuracy of K-Means clustering based on majority voting.
## Notes

- This script assumes the availability of the required dataset and labels.
- Ensure that you have the necessary Python libraries installed.
## Author

[Vladislav Kuznetsov](https://vlad-ds.pro/)
## License

This project is licensed under the [MIT License](LICENSE).
