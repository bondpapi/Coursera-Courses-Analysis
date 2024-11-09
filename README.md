# Coursera Courses Analysis
This project analyzes the Coursera Courses dataset, providing insights into course popularity, ratings, enrollments, difficulty levels, and certification types. The notebook explores patterns and trends in the data to better understand user preferences and the diversity of courses offered on Coursera.

## Dataset

The dataset contains various attributes for each course, including:

- Course Title: Name of the course.

- Organization: Institution or organization offering the course.

- Difficulty Level: Categorized as Beginner, Intermediate, Mixed, or Advanced.

- Enrollments: Number of students enrolled in the course.

- Rating: Average rating of the course (out of 5).
Certificate Type: Type of certificate offered (e.g., Course, Specialization, Professional Certificate).

## Analysis Overview

The notebook is organized as follows:

1. Data Cleaning and Preparation
    - Handles missing values, standardizes data types, and prepares columns for analysis.

2. Exploratory Data Analysis (EDA)
    - Visualizes key metrics to uncover patterns in enrollments, ratings, and course difficulty distribution.

3. Top-Rated Courses
    - Examines courses with ratings of 4.9 and above to understand characteristics of highly-rated content.

4. Popular Courses by Enrollments
    - Identifies the most popular courses based on enrollment numbers, focusing on trends in course topics and difficulty levels.

5. Course Difficulty Level Distribution
    - Analyzes the distribution of courses across different difficulty levels, showing the balance between accessibility and advanced content.

6. Distribution of Certificate Types
    - Highlights the prevalence of different certification types and how they correspond to course enrollments.

7. Correlation Analysis
    - Investigates relationships between numerical attributes, such as enrollments and ratings, using a correlation matrix.

## Key Insights

**Popularity vs. Quality**: High enrollments do not necessarily correlate with high ratings, suggesting that factors beyond course quality influence popularity.

**Course Accessibility**: Most courses are beginner-level, reflecting a focus on introductory content suitable for a wide audience.

**Certification Preferences**: Individual courses are more common than bundled certifications, indicating a preference for shorter, focused learning experiences.

**Weak Correlations**: The weak correlations between numerical features highlight that multiple factors, such as topic and marketing, may drive enrollment.

## Visualizations

The notebook includes the following visualizations:

**Histograms** to explore the distribution of ratings.

**Boxplots** to examine the spread of enrollments by course difficulty.

**Scatter Plots** to visualize the relationship between enrollments and ratings.

**Heatmap Correlation Matrix** to show the correlation between numerical attributes.

## Tools and Libraries

The analysis is conducted using:

- **Pandas** for data manipulation

- **Matplotlib** and **Seaborn** for data visualization

- **Plotly** for interactive charts

## Running the Notebook

1. Clone the repository or download the notebook.

2. Install the required libraries (if not already installed):
```bash
pip install pandas matplotlib seaborn plotly
```
3. Open the notebook in Jupyter or VS Code and run each cell sequentially.

## Future Improvements

- **Time-Series Analysis**: Analyze trends over time, such as enrollments or ratings over specific periods.

- **Topic Modeling**: Use NLP techniques to identify popular themes and topics among course titles.

- **Sentiment Analysis**: If data on course reviews were available, sentiment analysis could provide deeper insights into course ratings.

## License

This project is licensed under the MIT License.

