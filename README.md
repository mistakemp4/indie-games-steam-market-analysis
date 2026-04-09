The Rise of Indie Games: Steam Market Analysis (2010-2023)

This project analyzes Steam game data to explore how indie games have changed over time in terms of release volume, engagement, pricing, and genre patterns. The analysis focuses on turning exploratory data analysis into a market-focused case study.

Project highlights
- cleaned and prepared a large Steam games dataset for analysis
- engineered an is_indie flag from genre data
- analyzed release trends for indie games from 2010 to 2023
- compared indie and non-indie games on user scores and pricing
- used linear regression to measure long-term growth in indie releases
- filtered out incomplete years and extreme playtime outliers to improve interpretation
- visualized common indie genres with a word cloud

Business questions
- How has the number of indie games on Steam changed over time?
- Do indie games perform competitively on user scores and engagement?
- Are indie games priced differently from non-indie games?
- What genres appear most often in indie releases?

Tools used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- Jupyter Notebook

Repository contents
.
├── indie_games_analysis.ipynb
├── README.md
└── requirements.txt

Key findings
- Indie game releases grew quickly through the mid-2010s, then stabilized.
- A simple linear trend shows a positive long-run increase in indie releases.
- Indie games tend to be lower priced than non-indie games.
- User scores for indie and non-indie titles are broadly comparable.
- Genre patterns suggest variety and innovation rather than concentration in a single category.

Data notes

The dataset used in this project is publicly available on Kaggle:
https://www.kaggle.com/datasets/artermiloff/steam-games-dataset
Download the file `games_march2025_full.csv` and place it in the project folder before running the notebook.

- Pre-2010 years were treated cautiously because of sparse observations.
- 2024 and 2025 were excluded from the main trend discussion because the data was incomplete or unreliable for comparison.
- Extreme playtime outliers were filtered when analyzing average engagement trends.

Portfolio takeaway
This project shows data cleaning, exploratory analysis, visualization, basic regression, and business interpretation using a real entertainment-industry dataset.
