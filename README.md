# 🎵 Spotify Song Recommendation Model

This project uses machine learning to recommend songs based on track features from the **Spotify Million Song Dataset**. The core implementation is in a single Jupyter notebook: `1.Spotify_model_training.ipynb`.

---

## 📘 About the Project

This project builds a **music recommendation model** using features such as:

- Danceability  
- Energy  
- Tempo  
- Acousticness  
- Valence  
- Loudness  
- and more...

It uses Spotify's audio features to train a content-based recommendation system that suggests similar songs.

---

## 📁 File in This Repository

- `1.Spotify_model_training.ipynb`: Contains the entire end-to-end pipeline — data loading, preprocessing, EDA, feature selection, model training, and prediction.

---

## 📊 Dataset

- **Source**: [Spotify Million Song Dataset (Kaggle)](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset)
- To use this notebook, you must:
  1. Download the dataset from Kaggle.
  2. Place the CSV file in the same directory as the notebook or update the file path accordingly.

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/Ayush54555/Song-Recommendation-Model.git
   cd Song-Recommendation-Model
   ```

2. **Install dependencies**
   Make sure you have Python 3.8+ and Jupyter installed. You can install required packages using:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run the notebook**
   Open the notebook in Jupyter:
   ```bash
   jupyter notebook 1.Spotify_model_training.ipynb
   ```
   Make sure to adjust the dataset path as needed in the first few cells.

---

## 🧠 Future Work

- Add collaborative filtering and hybrid models
- Evaluate using metrics like precision@K, recall@K
- Deploy with a Streamlit or Flask app
- Integrate user interaction for real-time recommendation

---

## 📋 License

This project is under the MIT License.

---

## 🙌 Acknowledgment

- [Spotify Million Song Dataset on Kaggle](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset)
