# Topic Discovery in Scholarly Articles

## Project Overview

This project demonstrates the application of unsupervised learning techniques, specifically K-Means clustering, for topic discovery in scholarly articles. Using a dataset of research paper abstracts from [arXiv](https://arxiv.org/), the project aims to uncover latent topics and group similar articles together.

## Dataset

The dataset consists of a sample of 5,000 paper abstracts from arXiv. Each entry includes:

1. **id**: Unique identifier for each submission, formatted as `YYMM.NNNNN` (e.g., `2104.12345`).
2. **title**: Title of the paper.
3. **abstract**: Text of the abstract.

## Key Features

- **Preprocessing**: Includes text cleaning, tokenization, stopword removal, and stemming.
- **Vectorization**: Transforms textual data into numerical form using TF-IDF.
- **Clustering**: Implements K-Means clustering to identify topics.
- **Visualization**: Employs methods like dimensionality reduction (e.g., PCA) to visualize clusters.

## Requirements

To run the project, install the following Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Topic_Discovery_in_Scholarly_Articles.ipynb
   ```
3. Follow the notebook instructions to preprocess data, perform clustering, and analyze results.

## Results

The analysis identifies key topics within the dataset, enabling insights into the main themes present in the scholarly articles. The clusters are visualized to aid interpretation.

## Project Structure

- ``: Main notebook containing code and analysis.
- ``: Folder to store the dataset (not included; please download as per instructions in the notebook).
- ``: Folder for saving clustering results and visualizations.

## Contributions

Feel free to contribute by submitting pull requests or reporting issues.

## License

This project is open-source and available under the MIT License.

