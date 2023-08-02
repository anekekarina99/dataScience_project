# Customer Segmentation for E-money Users in DKI Jakarta

![E-money logo](emoney_logo.png)

## Introduction

Customer segmentation is an effective marketing technique that allows businesses to identify the most potential target markets. With the increasing usage of E-money in DKI Jakarta and the availability of E-money products from various banks, customer segmentation becomes crucial to stay competitive in the global market. In this project, we aim to segment E-money users in DKI Jakarta by applying the DBSCAN (Density Based Spatial Clustering Application with Noise) algorithm. The quality of segments will be measured using the Silhouette Coefficient.

## Data

The dataset used for this project consists of transaction data from E-money users in DKI Jakarta. It includes information such as user demographics, transaction details (amount, date, type), bank usage, reasons for using E-money, transaction activities, number of transactions, nominal balance, and frequency of top-up.

## Methodology

The customer segmentation process involves the following steps:

1. Data Preprocessing: Cleaning the dataset, handling missing values, and transforming the data into a suitable format for analysis.
2. Feature Engineering: Creating new features or transforming existing ones, such as grouping transaction activities and determining bank usage.
3. DBSCAN Algorithm: Applying the DBSCAN algorithm to group customers based on the density of their transactions and other attributes.
4. Silhouette Coefficient: Evaluating the quality of segments using the Silhouette Coefficient, which measures the separation and compactness of clusters.
5. Segment Identification: Identifying potential customer segments with the highest average values across selected attributes.
6. Interpretation: Interpreting the results and providing actionable insights for targeted marketing strategies.

## Results

The results of the customer segmentation analysis will be presented with the following findings:

1. The application of DBSCAN with a density radius of 2 and a minimum of 3 objects formed 2 segments and identified 17 noises in the dataset.
2. The Silhouette Coefficient value of 0.26 indicates the quality of the segments.
3. The most potential segment will be identified based on attributes that have an average greater than the overall average of all data.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies specified in the `requirements.txt` file.
3. Obtain the dataset of E-money users in DKI Jakarta and place it in the project directory.
4. Run the Jupyter notebooks in the `notebooks` directory to perform data preprocessing, DBSCAN clustering, and segment evaluation.
5. Review the results and insights in the `results` directory.

## Contributing

We welcome contributions to this project! If you find any issues or have ideas for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

By contributing to this project, you agree to the terms and conditions outlined in the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).

For any questions or inquiries, please contact us at [your-email@example.com](mailto:your-email@example.com).