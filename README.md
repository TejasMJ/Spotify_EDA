# Spotify Tracks & Playlists EDA 🎧📊

A comprehensive **Exploratory Data Analysis (EDA)** on Spotify tracks, playlists, and audio features using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights around music curation, popularity, genres, and audio characteristics.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling missing values, duplicates, and data type standardization.
- **Statistical Insights:** Summary statistics, distribution analysis, and skewness detection.
- **Playlist & Genre Analysis:** Understanding how tracks are distributed across genres and playlists.
- **Popularity Analysis:** Examining how popularity varies across tracks and features.
- **Audio Feature Analysis:** Exploring danceability, energy, valence, tempo, and acoustic properties.
- **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Spotify_Tracks_Playlists_EDA/
├── data
|   ├── spotify_songs.csv             # Spotify tracks & playlist dataset
├── Spotify_EDA.ipynb                 # Jupyter Notebook with full EDA
├── requirements.txt                  # Python dependencies
└── venv/                             # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+----------------------------+  
|        DATA LAYER          |  
|  Spotify track & playlist  |  
|  metadata (CSV)            |  
+-------------+--------------+  
              ↓  
+-------------------------------+  
|       ANALYSIS LAYER          |  
|  - Data Cleaning              |  
|  - Popularity Distribution   |  
|  - Genre & Playlist Analysis |  
|  - Audio Feature Insights    |  
|  - Release Date Trends       |  
+-------------+-----------------+  
              ↓  
+-------------------------------------------+  
|        VISUALIZATION LAYER                 |  
|  - Interactive Plots (Plotly)              |  
|  - Static Charts (Seaborn & Matplotlib)    |  
|  - Scatter, Bar, Histograms                |  
+-------------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** Publicly available Spotify track metadata & audio features

---

## 📊 Dataset Overview

- **Rows:** 20,000+ tracks  
- **Key Columns include:**
  - **Track metadata:** `track_name`, `track_artist`, `track_popularity`
  - **Playlist information:** `playlist_name`, `playlist_genre`, `playlist_subgenre`
  - **Audio features:** `danceability`, `energy`, `valence`, `tempo`, `loudness`
  - **Release information:** `track_album_release_date`, `duration_ms`

**Context:**  
This dataset combines Spotify track metadata, playlist categorization, and audio features to analyze how music is curated, promoted, and positioned across playlists.

**Acknowledgements:**  
- Audio features and metadata derived from Spotify’s public APIs and community datasets.  
- Thanks to open-source contributors for making music analytics datasets accessible.

**Inspiration:**  
Understanding how audio characteristics, genre placement, and recency influence playlist exposure and popularity can guide artists, curators, and music analysts in data-driven decision-making.
---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Google-Play-Store-App-EDA-.git
cd Google-Play-Store-App-EDA-
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 🎧 Spotify Music Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Remove duplicate tracks
- Handle missing or invalid values
- Convert date and numeric columns to proper formats

### Statistical Insights
- Distribution of `track_popularity`
- Summary statistics for audio features
- Detection of skewed or extreme values

### Playlist & Genre Analysis
- Track distribution across playlist genres
- Subgenre-level representation
- Repeated track appearances across playlists

### Popularity Analysis
- Popularity distribution and concentration
- Relationship between popularity and playlist exposure
- Identification of mid- vs high-popularity tracks

### Audio Feature Analysis
- Popularity vs danceability, energy, and valence
- Tempo and loudness trends
- Audio characteristics of playlisted tracks

### Temporal Analysis
- Track distribution by release year
- Recency bias in playlist curation

### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
