## The Rise of Indie Games: Steam Market Analysis (2010–2023)

This project analyzes trends in indie game development on Steam, focusing on growth, player engagement, pricing, and genre patterns. The goal is to understand how indie games have evolved and what factors contribute to their success.

---

### Project highlights

* Cleaned and processed ~95,000 game records from Steam
* Identified indie games using genre-based feature engineering
* Analyzed release trends, engagement metrics, and pricing strategies
* Applied linear regression to quantify growth in indie game releases
* Removed outliers and filtered unreliable time periods for accurate analysis
* Visualized genre trends using a word cloud

---

### Business questions

* How has the number of indie games changed over time?
* Do indie games achieve similar engagement and quality as AAA titles?
* How does pricing differ between indie and non-indie games?
* What genres dominate the indie game market?

---

### Tools used

* Python
* pandas
* numpy
* matplotlib
* seaborn
* wordcloud
* Jupyter Notebook

---

### Repository contents

```
.
├── indie_games_analysis.ipynb
├── README.md
├── requirements.txt
```

---

## Dataset

The dataset used in this project is publicly available on Kaggle:

[https://www.kaggle.com/datasets/artermiloff/steam-games-dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset)

Download the file `games_march2025_full.csv` and place it in the project folder before running the notebook.

---

## Key findings

### Indie game growth

* Indie game releases increased rapidly from 2010 to around 2017
* Growth stabilized after 2017
* Regression analysis shows a positive long-term trend

<img width="1969" height="978" alt="Screenshot 2026-04-09 111536" src="https://github.com/user-attachments/assets/8594a3ac-c0ca-41eb-ae42-d12ff600a05e" />
<img width="1980" height="968" alt="image" src="https://github.com/user-attachments/assets/c44d8aed-26b8-4150-a228-27da45384366" />


---

### Player engagement

* Average playtime remains strong over time, with some variability
* User scores are relatively stable, indicating consistent perceived quality

<img width="1976" height="980" alt="image" src="https://github.com/user-attachments/assets/a5e399cc-848b-4e0a-9dce-ae07b424dd4e" />


---

### Value proposition

* Indie games are generally priced lower than non-indie titles
* Despite lower prices, user scores are comparable

This suggests strong value for players.

<img width="1200" height="910" alt="image" src="https://github.com/user-attachments/assets/44d8de8a-68e4-489c-82ec-d08080c65a63" />
<img width="1164" height="954" alt="image" src="https://github.com/user-attachments/assets/dde280b2-8428-4939-beba-77170e33b066" />


---

### Genre trends

* Indie games span a wide variety of genres
* Common genres include action, adventure, and simulation

<img width="1584" height="1002" alt="image" src="https://github.com/user-attachments/assets/e79827a5-9aca-4851-8b21-ea4f6a9da5ec" />


---

### Data considerations

* Excluded pre-2010 data due to low sample size
* Removed extreme playtime outliers (top 1 percent)
* Excluded 2024–2025 due to incomplete data

---

## Business insights

* Indie games represent a growing and stable segment of the market
* Lower pricing combined with strong engagement creates a competitive advantage
* Developers can succeed with niche genres without AAA budgets
* Platforms benefit from supporting indie creators due to strong user demand

