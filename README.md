# 📚 Book Recommender System

A Machine Learning based Book Recommendation System that suggests similar books based on user preferences. The project uses collaborative filtering and cosine similarity to recommend books that are similar to the selected book.

## 🚀 Features

* Top 50 Popular Books Display
* Book Recommendation Based on Similarity
* Interactive Web Interface using Flask
* Dropdown Search for Easy Book Selection
* Responsive and Attractive UI
* Error Handling for Invalid Book Names

## 🛠️ Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Scikit-Learn
* HTML
* CSS
* Bootstrap
* Pickle

## 📂 Project Structure

```
Book-Recommender-System/
│
├── app.py
├── Book Recommender System.ipynb
├── Live Demo.mp4
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   └── recommend.html
│
└── Dataset & Model Files (Google Drive)
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/book-recommender-system.git
cd book-recommender-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download Dataset & Model Files

Due to GitHub file size limitations, dataset and trained model files are not included in this repository.

Download them from:

**Google Drive Link:**
https://drive.google.com/file/d/15BbvcaqN0-rW-AsTHaioTlp4HMpGJjFL/view?usp=sharing

Extract the ZIP file and place all files in the project root directory.

Required files:

* Books.csv
* Users.csv
* Ratings.csv
* books.pkl
* pt.pkl
* popular.pkl
* similarity_scores.pkl

### Run Application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🧠 Machine Learning Approach

The recommendation system uses:

1. Collaborative Filtering
2. User-Book Interaction Matrix
3. Cosine Similarity
4. Popularity-Based Ranking

Books with similar user interaction patterns are recommended to the user.

## 📸 Screenshots

Add screenshots of:

* Home Page
* Recommendation Page
* Book Recommendation Results

## 🎥 Demo Video

Demo Video Link:

Project Demo: ▶ [Click to watch Live Demo.mp4](./Live Demo.mp4)

## 👨‍💻 Author

Kousik Chakraborty

B.Tech Student | Machine Learning & Data Science Enthusiast

## ⭐ Future Improvements

* Deploy on Render/Streamlit
* Add Book Search Autocomplete
* User Authentication
* Personalized Recommendations
* Advanced Recommendation Algorithms

---

If you found this project useful, consider giving it a ⭐ on GitHub.
