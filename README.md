# Netflix Content Strategy vs Global GDP Growth

## What is this project about?
I started watching a lot of movies and TV shows during COVID-19 and kind of never stopped — so when it came to picking a project topic, this felt like a natural choice. I wanted to see if Netflix actually reacts to economic crises by adding more content, the idea being that when times are tough, people turn to cheap home entertainment. So I looked at Netflix's content additions from 2008 to 2021 and compared them with global GDP growth rates.

## Data
- **Netflix Titles** from Kaggle: 8,807 titles with info like type, country, date added, and release year
- **World Bank GDP data**: annual global GDP growth rate (%) from 2008 to 2021

## How to run
1. Open `dsaproj_final.ipynb` in Google Colab
2. Upload `archive.zip` (Netflix data) and `API_NY.GDP.MKTP.KD.ZG_DS2_en_csv_v2_175549.zip` (GDP data)
3. Run all cells in order

## What I did
- Explored the Netflix dataset: content growth over time, top genres, countries, ratings, Movie vs TV Show trends
- Ran hypothesis tests to check if economic downturns correlate with more Netflix content
- Built Linear Regression and Random Forest models to predict content additions from GDP growth

## What I found
Honestly, the data doesn't support the hypothesis. Netflix kept growing regardless of what the economy was doing — the real driver seems to be their internal expansion strategy, especially after 2015 when they went global. The ML models also couldn't predict content additions from GDP alone.

## AI Usage
I used Claude (Anthropic) throughout this project for help with code, debugging, and structuring the analysis.
