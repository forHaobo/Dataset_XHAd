# Dataset_XHAd

This dataset contains real clinical data from a traditional Chinese medicine (TCM) hospital, meticulously anonymized to ensure no privacy or ethical issues. The dataset includes information on diseases, Chinese medicines, and syndromes, which are crucial for studying the clinical efficacy of TCM, the characteristics of syndromes, and the use of Chinese medicines.

Due to the confidential nature of the original data, we have provided a small portion of the anonymized original data for readers to use in order to better understand our paper's code and perform tests. It is important to note that the complete original data cannot be publicly disclosed due to confidentiality requirements.

This dataset aims to provide high-quality TCM clinical data samples to researchers and students, supporting their research and learning in the field of TCM. By sharing this data, we hope to advance TCM research and provide data support for clinical decision-making in TCM.

## Data Structure

Each data file includes the following:
- `train_data`: Training set, consisting of `dis`, `tcm`, and `syn` data
- `test_data`: Testing set, consisting of `dis`, `tcm`, and `syn` data
- `valid_data`: Validation set, consisting of `dis`, `tcm`, and `syn` data

Additionally, the dataset includes graph data constructed in the paper:
- `graph_tcm`: Constructed graph data

## Data Format

Each data file is a Python dictionary containing multiple numpy ndarrays, as follows:
- `train_data`: A tuple containing `dis`, `tcm`, and `syn`
- `test_data`: A tuple containing `dis`, `tcm`, and `syn`
- `valid_data`: A tuple containing `dis`, `tcm`, and `syn`

## Usage Notes
Please note that this dataset is intended for research and educational purposes only and is prohibited from any commercial use. Any form of dissemination and use of the dataset must comply with relevant laws and regulations.
