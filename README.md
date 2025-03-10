Installation & Setup

Clone this repository:

git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
pip install -r requirements.txt

Download the dataset from Kaggle using the API:

mkdir ~/.kaggle
cp kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
kaggle datasets download -d mlg-ulb/creditcardfraud
unzip creditcardfraud.zip

Usage

1. Data Preprocessing

python src/data_processing.py

2. Train Models

python src/model_training.py

3. Evaluate Models

python src/evaluation.py

4. Run Inference on New Data
