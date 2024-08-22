# Prime Video Data Dashboard

This repository contains a Power BI dashboard visualizing various statistics and data points related to shows available on Prime Video. The dashboard offers insights into the distribution of shows by ratings, genres, release years, and geographical locations.

## Dashboard Overview

![Dashboard Overview](/assets/dashboard.png)

### Key Features:
- **Total Shows:** Displays the total number of shows available.
- **Total Rating Types:** Shows the count of different rating types across the shows.
- **Total Genres:** Indicates the diversity of genres available.
- **Total Directors:** Provides the total number of unique directors contributing to the shows.
- **Release Year of Earliest Show:** Indicates the release year of the oldest show available.
- **Release Year of Latest Show:** Indicates the release year of the newest show available.
- **Rating by Total Shows:** A bar chart showing the distribution of shows by their ratings.
- **Genres by Total Shows:** A bar chart displaying the most popular genres.
- **Total Shows by Country:** A world map visualization showing the distribution of shows across different countries.
- **Movies and TV Shows:** A pie chart indicating the proportion of movies to TV shows.
- **Total Shows by Release Year:** A line chart showing the number of shows released per year.

### How to Use

1. **Download the Dashboard:** Clone or download this repository to your local machine.
2. **Open in Power BI:** Open the `.pbix` file in Power BI to explore the data and visuals.
3. **Explore the Data:** Use the filters and interactive features to gain insights into the Prime Video content library.

### File Structure

- **/amazon_prime_titles/**: Contains the data in csv format
- **/dashboard_prime_video/**: Contains the Power BI dashboard file.
- **/assets/**: Contains images used in this repository.
- **README.md**: This file, providing an overview of the project.

### CSV Metadata

**File Name:** `amazon_prime_titles.csv`

**Description:**
This CSV file contains data on movies and TV shows available on Amazon Prime, including detailed metadata such as genres, ratings, release years, and production countries. The dataset provides a comprehensive overview of Amazon Prime's content library up until the point of data collection.

**Columns:**

- `show_id` (string): Unique identifier for each show or movie in the dataset.
- `title` (string): The title of the movie or TV show.
- `type` (string): Type of content (`Movie` or `TV Show`).
- `director` (string): Name of the director(s) of the content. This field may be blank for some entries.
- `cast` (string): Comma-separated list of main actors. This field may be blank for some entries.
- `country` (string): Country where the content was produced. Some entries may have multiple countries or be blank.
- `date_added` (date): The date the content was added to Amazon Prime's library.
- `release_year` (integer): The year the movie or TV show was originally released.
- `rating` (string): The content rating (e.g., `PG`, `R`, `TV-14`). Some entries may be blank.
- `duration` (string): The duration of the content (e.g., "90 min" for movies or "3 Seasons" for TV shows).
- `listed_in` (string): Comma-separated list of genres or categories the content belongs to.
- `description` (string): A brief summary or description of the content.

**Size and Record Count:**
- **Rows:** 9,655
- **Columns:** 12
- **File Size:** Approximately 2 MB

**Usage Notes:**
- **Missing Values:** The `director`, `cast`, `country`, and `rating` columns have some missing values.
- **Date Formatting:** The `date_added` column is in the format `MM-DD-YYYY`.

**Source:**
This dataset was compiled and provided by [Shivam Bansal on Kaggle](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows), and includes data from Amazon Prime’s publicly available content library.

### Contact

For any questions or feedback, please contact [Eshwanth](mailto:your.eshwanthj@gmail.com).

### Author
 _Eshwanth_

