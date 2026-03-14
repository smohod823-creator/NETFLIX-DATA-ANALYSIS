# 🎬 Netflix Data Analysis

An Exploratory Data Analysis (EDA) project on Netflix movies and TV shows dataset to uncover trends and insights about genres, popularity, and release patterns.

---

## 📌 Project Overview

This project performs end-to-end exploratory data analysis on a Netflix dataset containing ~9,826 movies and TV shows. It includes data cleaning, preprocessing, and interactive visualizations to answer key questions about content trends on Netflix.

---

## 📊 Key Questions Explored

1. **Which genre appears most often?**
2. **Which movies have the highest popularity?**
3. **How has movie production changed over time?**
4. **Which genres have the highest average popularity?**
5. **What is the distribution of popularity scores?**

---

## 🔍 Key Findings

- **Drama** is the most frequently occurring genre on Netflix.
- **Spider-Man: No Way Home** has the highest popularity score in the dataset.
- **Adventure** movies have the highest average popularity among all genres.
- Movie releases increased **significantly after the year 2000**, reflecting the rapid growth of the film industry and streaming platforms.
- Popularity scores are **highly right-skewed** — most movies have average popularity, with only a few becoming blockbuster hits.

---

## 🗂️ Dataset

The dataset (`NetflixData.csv`) contains the following columns:

| Column | Description |
|---|---|
| `Release_Date` | Date the movie/show was released |
| `Title` | Name of the movie/show |
| `Overview` | Brief description |
| `Popularity` | Popularity score (float) |
| `Vote_Count` | Number of votes received |
| `Vote_Average` | Average vote rating |
| `Original_Language` | Language of the original content |
| `Genre` | Genre(s) of the movie/show |
| `Poster_Url` | URL to the poster image |

> **Dataset size:** 9,826 rows × 9 columns (before preprocessing)

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — Data manipulation and analysis
- **Plotly Express** — Interactive visualizations
- **Google Colab** — Development environment

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add the dataset

Place your `NetflixData.csv` file in the project root directory (or update the file path in the notebook).

### 4. Run the notebook

Open `Netflix_Data_Analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run all cells.

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main analysis notebook
├── NetflixData.csv               # Dataset (add manually)
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📈 Visualizations Included

- Bar chart — Most common movie genres
- Horizontal bar chart — Top 10 most popular movies
- Line chart — Movies released over the years
- Bar chart — Average popularity by genre
- Histogram — Distribution of popularity scores

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

