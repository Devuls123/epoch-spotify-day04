# epoch-spotify-day04

# Spotify Tracks Dataset – EDA & Data Visualization

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and data visualization on the Spotify Tracks Dataset. The objective is to understand the structure of Spotify tracks, explore relationships between audio features, analyze track popularity, and communicate important findings through effective visualizations.

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn.

---

##  Dataset Overview

The dataset contains information about Spotify tracks along with various audio features and metadata.

### Important Features

* **track_name** – Name of the track
* **artists** – Artist or artists associated with the track
* **album_name** – Name of the album
* **track_genre** – Genre of the track
* **popularity** – Popularity score of the track
* **danceability** – How suitable a track is for dancing
* **energy** – Perceptual measure of intensity and activity
* **acousticness** – Confidence that the track is acoustic
* **instrumentalness** – Likelihood that the track contains no vocals
* **liveness** – Detects the presence of an audience in the recording
* **valence** – Musical positivity or happiness of the track
* **tempo** – Estimated tempo of the track in beats per minute

---

##  Exploratory Data Analysis

The following EDA steps were performed:

* Examined the dataset structure and dimensions
* Identified numerical and categorical features
* Generated descriptive statistics
* Checked for missing values
* Checked for duplicate records
* Examined unique values in categorical columns
* Analyzed relationships between Spotify audio features

---

## 📊 Visualizations and Key Insights

### 1. Distribution of Track Popularity


<img width="861" height="525" alt="popularity_distribution" src="https://github.com/user-attachments/assets/29aec732-4720-4513-b034-cd678f05cad7" />

**Key Insight:**
The popularity distribution shows how Spotify tracks are spread across different popularity scores and helps identify the most common popularity range.

---

### 2. Top 10 Music Genres

<img width="732" height="390" alt="top_genres" src="https://github.com/user-attachments/assets/b5fee801-59de-4624-80ea-f7050ebbe3c8" />


**Key Insight:**
The visualization identifies the most represented music genres in the dataset and shows the relative distribution of tracks across these genres.

---

### 3. Distribution of Danceability

<img width="767" height="491" alt="danceability_distribution" src="https://github.com/user-attachments/assets/ff8e772d-4237-416b-8e34-951790be22ee" />

**Key Insight:**
The distribution illustrates the range of danceability values across Spotify tracks and shows the general tendency of tracks in the dataset.

---

### 4. Energy vs Popularity

<img width="727" height="478" alt="energy_vs_popularity" src="https://github.com/user-attachments/assets/98597ff5-0ed9-458c-bf35-788b0c8f94e8" />

**Key Insight:**
The scatter plot explores the relationship between track energy and popularity. The distribution of points indicates whether energy is strongly associated with popularity.

---

### 5. Correlation Between Audio Features

<img width="741" height="580" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/aaa68333-ab24-4abb-b97f-9a487b908a53" />


**Key Insight:**
The correlation heatmap highlights relationships between Spotify audio features. Strong correlations can indicate audio characteristics that tend to vary together.

---

### 6. Popularity Across Top Genres

<img width="731" height="438" alt="genre_popularity" src="https://github.com/user-attachments/assets/02fd07a1-cf04-482e-b79d-84697043bf07" />


**Key Insight:**
The box plot compares popularity across major genres and reveals differences in median popularity, spread, and potential outliers.

---

### 7. Danceability vs Energy

<img width="732" height="476" alt="danceability_vs_energ" src="https://github.com/user-attachments/assets/91ccd0b3-6056-404a-80e1-c090c8d569bb" />


**Key Insight:**
The visualization examines the relationship between danceability and energy, helping identify whether more danceable tracks generally tend to have higher energy levels.

---

##  Overall Conclusions

The analysis provides an overview of Spotify tracks based on their metadata and audio characteristics. The visualizations demonstrate that music tracks vary considerably in terms of popularity, danceability, energy, and other audio features.

The genre analysis highlights differences in the representation and popularity of music categories. The correlation analysis helps identify relationships between audio characteristics, while scatter plots provide a better understanding of how features such as energy and danceability relate to popularity.

Overall, the analysis demonstrates how Exploratory Data Analysis and effective visualization can be used to identify patterns and communicate insights from a large music dataset.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

##  Repository Structure

```text
spotify-eda-visualization/
│
├── visualization.ipynb
├── README.md
│
└── images/
    ├── popularity_distribution.png
    ├── top_genres.png
    ├── danceability_distribution.png
    ├── energy_vs_popularity.png
    ├── correlation_heatmap.png
    ├── genre_popularity.png
    └── danceability_vs_energy.png
```

---

## 📓 Notebook

The complete analysis, EDA, visualizations, and insights can be found in:

`visualization.ipynb`
