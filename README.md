Data Narrative Projects
Welcome to the Data Narrative Projects repository! This collection includes in-depth analyses and narratives based on three diverse datasets. Each project involves reading data from CSV files, posing insightful questions, and writing Python code to derive meaningful insights and visualizations.

Projects
1. Faculty Salaries and Statistics
Dataset Description: Contains data on faculty members' salaries and other statistics across various institutions.

Key Features:

Detailed analysis of salary distributions.
Comparison of salaries across institutions.
Visualization of salary trends and statistics.
2. Book Statistics
Dataset Description: Encompasses various details about books, ratings, and tags from Goodreads.

Data Files:

books.csv: Contains columns such as author, average rating, year of publication, etc.
ratings.csv: Includes book_id, user_id, and rating.
books_tags.csv: Contains goodreads_book_id, tag_id, and count.
tags.csv: Consists of tag_id and tag_name.
to_read.csv: Information regarding user_id and book_id.
Key Features:

Analysis of book ratings and popularity.
Exploration of author statistics and publication trends.
Examination of book tags and reader preferences.
3. Tennis Matches 2013
Dataset Description: Data on tennis matches from the Australian Open, French Open, US Open, and Wimbledon in 2013.

Data Files:

Separate files for men's and women's matches for each tournament, each containing 42 columns of match data.
Key Features:

Analysis of player performance and match statistics.
Trend identification across different tournaments.
Visualization of player performance metrics.
Abstract
This document comprises analyses of different types of tennis tournaments, faculty salaries, and book statistics. Various probability functions and statistical methods are used to derive insights. Visualizations are employed to help better understand and interpret the data.

Overview of Datasets
Tennis Matches 2013
Tournaments: Australian Open, French Open, US Open, Wimbledon.
Details: Performance metrics of players, match statistics.
Book Statistics
Details: Book details, ratings, publication years, tags, and reader preferences.
Faculty Salaries and Statistics
Details: Faculty salaries, institution types, comparison of salaries across institutions.
Key Questions Explored
Tennis Matches 2013
Probability that player 1 wins given they win the first set and first game of the second set.
Probability that player 1 wins the match without losing any sets.
Probability that a player who wins the first set goes on to win the match with a first serve percentage of at least 70%.
Probability that the winning player had at least 10 aces, given that the losing player committed exactly 5 double faults.
Probability that the winning player served at least 10 aces and the losing player committed fewer than 25 unforced errors.
Probability of at least 3 aces and no more than 2 double faults.
Probability that N. Djokovic wins a match in straight sets.
Probability that a player wins less than or equal to 50% of the games.
Book Statistics
Number of books published by each author and identification of the author with the maximum books.
Frequency distribution of books and its relation to ratings.
Probability that a book published after 1950 has a high rating.
Year-wise publication trends and identification of the year with the highest publications.
Average book ratings and general insights from the data.
Top ten most rated books.
Faculty Salaries and Statistics
Probability that Type I has higher salaries for associate professors than for full professors.
Probability that more than 50% of professors in Type I institutions are full-time.
Probability that a random college is a Type II institution in California with an average salary over $500,000.
Probability that a college with at least 50 faculty members has higher average salaries for assistant professors than for associate professors.
Probability that a college in California has more associate professors than assistant professors.
Probability that a randomly chosen college is private or public.
Probability that students with SAT scores over 1000 are from the top 25% of their high school class.
Relationship between the number of students applying and those accepted.
Ten colleges with the highest acceptance rates and new enrollments.
Probability that a college in California has an average SAT score of at least 700.
Libraries and Functions Used
Pandas: Data manipulation and analysis (pd.read_csv, df.head(), value_counts(), mean(), max()).
Matplotlib: Data visualization (plot(), show(), title(), xlabel(), ylabel()).
Seaborn: Enhanced data visualization.
Probability Functions: Various probability and statistical methods.
