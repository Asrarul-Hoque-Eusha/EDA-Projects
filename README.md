# Exploratory Data Analysis - Projects
## 1. EDA on Amazon Product Selling Dataset
### Data Cleaning Steps Performed
<ul>
<li>Handling Missing Values: Checked null values in each column and dropped rows with missing values.</li>
<li>Dropping Irrelevant Columns: Removed columns like category, img_link, product_link, and review_id as they were not useful for analysis.</li>
<li>Cleaning Numeric Columns: Used regex to clean actual_price, discounted_price, rating, rating_count, and discount_percentage by removing unwanted characters and converting them to float or integer.</li>
<li>Handling Duplicates: Removed duplicate entries.</li>
</ul>

### Feature Engineering Performed
<ul>
<li>Extracting Product Category & Subcategory: Split the category column into two new columns: Product Category and Sub Category.</li>
<li>Creating Review Count Feature: Extracted and assigned review count as a new feature.</li>
<li>Deriving Discount Percentage: Cleaned and transformed discount percentage into a structured format.</li>
</ul>

### Business Insights Extracted
<ul>
<li>Shown some statistical measurements like min, max, mean, standard deviation, variance, and percentiles for each category.</li>
<li>Identified correlation between discount percentage and sales volume.</li>
<li>Found trends in customer preferences based on product categories.</li>
<li>Determined categories receiving lower ratings.</li>
<li>Identified top 2 mostly saled categories and their rating distributions.</li>
<li>Identified products receiving lowest ratings from each category.</li>
<li>Identified subcategories receiving lowest ratings from all categories.</li>
<li>Identified highest discounted products from each category.</li>
</ul>

### Plots Used
<ul>
<li>Histogram - Used for analyzing price distribution.</li>
<li>Pie Chart - Shown percentage of rated sales and percentage of sales for each category.</li>
<li>Boxplot - Possibly used to detect outliers in price and rating distributions.</li>
<li>Scatter Plot - Examined relationships between price, discount, and sales.</li>
<li>Bar Chart - Showed product sales and mean rating by category.</li>
<li>Heatmap - Displayed correlation between numerical features.</li>
<li>Violinplot - Displayed category wise rating frequency density.</li>
</ul>

## 2. EDA on Student Performance Dataset

Performed data cleaning, basic statistical analysis, and exploratory data analysis on Student Performance dataset. Tasks performed are listed below:
<ul>
  <li>Finding outliers with <b>Inter Quartile Range (IQR)</b>.</li>
  <li>Handling outliers with <b>Capping</b> Method.</li>
  <li>Findout some <b>statistical measurements</b> like standard deviation, variance, min, max, sum, mean etc. for each subject.</li>
  <li>Data visualization with Bar Chart, Histogram, and Scatterplot.</li>
  <li>Identified <b>Gender</b> wise performance in each subject.</li>
  <li>Finding <b>Significant Difference</b> between Male and Female students performing <b>t-test</b>.</li>
</ul>

