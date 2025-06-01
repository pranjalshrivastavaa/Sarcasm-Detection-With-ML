#  SARCASM DETECTION WITH MACHINE LEARNING

This project is built to classify whether a given sentence is sarcastic or not using machine learning. It includes dataset preprocessing, feature extraction, model training, and performance evaluation.

## 📁 Project Structure

📦 Sarcasm-Detection-With-ML/  
├── SARCASM DETECTOR.py → Main script for training & evaluating the model  
├── Sarcasm_Headlines_Dataset.json → Dataset for sarcasm classification  

## 🧠 Features

- Loads and processes JSON sarcasm dataset  
- Applies text preprocessing and TF-IDF vectorization  
- Trains using `LogisticRegression`  
- Evaluates with classification report and accuracy  
- Shows examples of sarcastic vs non-sarcastic predictions  

## 🗃 Dataset

- **File:** `Sarcasm_Headlines_Dataset.json`  
- Contains headlines labeled as sarcastic (1) or not (0)  
- Source: News headlines used for sarcasm detection research  

## ⚙️ Requirements

Install dependencies:  
```bash
pip install pandas numpy scikit-learn nltk
```

Also, make sure to download NLTK stopwords:

```python
import nltk
nltk.download('stopwords')
```

## 🚀 How to Run

Run the script to train and test the sarcasm detection model:

```bash
python "SARCASM DETECTOR.py"
```

The model will output performance metrics and prediction samples.

## 🛠 Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- NLTK (stopword removal)  
- Logistic Regression classifier

## 🙌 Author

**Pranjal Shrivastava**  
GitHub: [@pranjalshrivastavaa](https://github.com/pranjalshrivastavaa)

## 📄 License

Licensed under the **MIT License**

## 💡 Future Improvements

- Build a web app with Streamlit or Flask  
- Try LSTM or transformer-based models  
- Add sarcasm confidence scores  
- Use pretrained BERT embeddings for better accuracy
