#### **Your friend suspects that movies are getting shorter and they've found some initial evidence of this. Having peaked your interest, you will perform exploratory data analysis on the netflix_data.csv data to understand what may be contributing to movies getting shorter over time.**

#### **You will use your data manipulation and visualization skills to explore movie durations and how they vary across time.**

## **Getting Started**

1. **Clone the Repository**
    ```Git 
    git clone https://github.com/ShadowConYT/Netflix-Data-Analysis.git
    ```

2. **Install necessary packages**
    ```Python
    pip install -r requirements.txt
    ```
3. **Open the notebook**
    ```Python
    jupyter notebook
    ```
4. **Run the notebook**
    ```Python
    run all cells
    ```
5. **Enjoy!**


## **Instructions**

1. Load the CSV file and store as netflix_df.

2. Filter the data to remove TV shows and store as netflix_subset.

3. Investigate the Netflix movie data, keeping only the columns "title", "country", "genre", "release_year", "duration" and saving this into a new DataFrame called netflix_movies.

3. Filter netflix_movies to find the movies that are shorter than 60 minutes, saving the resulting DataFrame as short_movies; inspect the result to find possible contributing factors.

4. Using a for loop and if/elif statements, iterate through the rows of netflix_movies and assign colors of your choice to four genre groups ("Children", "Documentaries", "Stand-Up", and "Other" for everything else). Save the results in a colors list. 

5. Initialize a figure object called fig and create a scatter plot for movie duration by release year using the colors list to color the points and using the labels "Release year" for the x-axis, "Duration (min)" for the y-axis, and the title "Movie Duration by Year of Release".

6. After inspecting the plot, answer the question "Are we certain that movies are getting shorter?" by assigning either "yes", "no", or "maybe" to the variable answer.

## **Try Answering these Questions**

1. What are the most common genres on Netflix?

2. Which countries produce the most content on Netflix?

3. What is the average duration of movies vs. TV shows?

4. How has the release year distribution of content changed over time?