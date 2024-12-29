**Bank Marketing Term Deposit Prediction**

### Description
This project predicts whether a client will subscribe to a term deposit using the Bank Marketing dataset. Two machine learning models, Random Forest and Neural Network, were implemented and compared.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Place the dataset (`bank-full.csv`) in the root directory.
2. Run the preprocessing and model training script:
   ```bash
   python main.py
   ```
3. Saved models:
   - Random Forest: `random_forest_model.pkl`
   - Neural Network: `neural_network_model.h5`

### Repository Structure
- `main.py`: Main script for data preprocessing, model training, and evaluation.
- `requirements.txt`: Required Python libraries.
- `README.md`: Project overview and instructions.
- `bank-full.csv`: Input dataset.

### Results
| Model            | Accuracy |
|------------------|----------|
| Random Forest    | 0.90     |
| Neural Network   | 0.88     |

