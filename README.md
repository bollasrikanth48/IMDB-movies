# **Suggestions for as sucessful movie**

## **Overview**
This project analyzes the **Top 100 IMDb movies** spanning two decades (2003–2022). Using Python and data analytics, we aim to uncover insights that can guide filmmakers and studios to create successful and impactful movies.

---

## **Objectives**
1. Identify key trends in popular movies to inform decision-making for filmmakers.
2. Analyze the factors that drive a movie's success, such as:
   - **Top Directors** by the number of movies and Return on Investment (ROI).
   - **Popular Genres** and frequent themes.
   - **Actors** with the highest appearances in popular movies.
3. Provide practical insights for casting, scriptwriting, marketing, and budgeting decisions.

---

## **Key Questions Explored**
1. Who are the top directors with the most movies in the Top 100 list, and their highest-rated films?
2. What genres have been most frequent and successful over the past two decades?
3. What is the most common word in movie titles from the dataset?
4. Which directors achieved the highest ROI, and how does it vary by year?
5. What are the average IMDb ratings for movies directed by the top directors?
6. Who are the top actors appearing most frequently in popular movies?

---

## **Dataset Description**
- **Source**: [Kaggle](https://www.kaggle.com/datasets/georgescutelnicu/top-100-popular-movies-from-2003-to-2022-imdb)
- **Size**: 13 columns, 2,000 rows
- **Missing Data**:
  - `Budget`: 15.2%
  - `Income`: 7.25%
  - `Runtime`: 2%

### **Columns**
- **Title**: Movie name  
- **Rating**: IMDb score  
- **Year**: Release year  
- **Month**: Release month  
- **Certificate**: Certification (e.g., PG-13, R)  
- **Runtime**: Movie duration  
- **Directors**: Film directors  
- **Stars**: Actors/Actresses  
- **Genre**: Primary genres  
- **Filming Location**: Shooting location  
- **Budget**: Production cost  
- **Income**: Revenue earned  
- **Country of Origin**: Country of production  

---

## **Technologies Used**
- **Tools**: Google Colab, Jupyter Notebook
- **Libraries**:
  - **Analysis**: NumPy, Pandas, Regular Expressions
  - **Visualization**: Matplotlib, Seaborn

---

## **Exploratory Data Analysis (EDA)**
1. **Data Cleaning**:
   - Converted all monetary values (budget and income) to USD.
   - Replaced missing values with zeros and dropped rows where necessary.
   - Created new ROI column: `(Income - Budget) / Budget`.
2. **Insights**:
   - Top directors like Ridley Scott and Steven Spielberg dominate the list.
   - Action, Adventure, and Sci-Fi are the most popular genres.
   - The word "Christmas" appears frequently in movie titles.
   - Makoto Shinkai's *Your Name* achieved the highest ROI of 128%.

---

## **Findings**
1. **Top Directors**:
   - Ridley Scott directed the most movies (13), with *The Martian* (2015) being his top-rated movie (8.0).
2. **Top Genres**:
   - Action, Adventure, and Sci-Fi accounted for 92 movies, making them the most popular genres.
3. **Popular Words in Titles**:
   - Excluding common words like "the" and "of," *Christmas* was the most recurring term.
4. **ROI Insights**:
   - Makoto Shinkai achieved the highest ROI with his anime movie *Your Name*, grossing over $360M on a $2.7M budget.
   - 2004 had the highest average ROI across all movies.
5. **Top Actors**:
   - Dwayne Johnson, Mark Wahlberg, and Ryan Reynolds appeared in the highest number of movies, with Johnson leading at 25 appearances.

---

## **Key Visualizations**
- **Top Directors**: Bar chart of the top directors by the number of movies directed.
![image](https://github.com/user-attachments/assets/67d1f372-698b-4436-937d-6a1381fc488d)

- **Top Genres**: Pie chart showing the percentage distribution of genres.
![image](https://github.com/user-attachments/assets/2736228e-0cec-4cfb-beed-3e6c75bcb36b)

- **ROI by Year**: Line graph depicting ROI trends over time.
---

## **Conclusion**
This analysis provides actionable insights for filmmakers to:
- Focus on popular genres and themes.
- Optimize casting by collaborating with actors and directors with proven track records.
- Recognize the potential of high-ROI movies made on modest budgets.
- Understand trends in audience preferences over two decades.

---

## **Future Work**
- Expand the analysis to include global box office data.
- Explore sentiment analysis of critic reviews to correlate with movie success.
- Use predictive modeling to forecast future trends.

---
