# Cyclistic Bike Share Analysis

## 📊 Case Study Overview
This is a data analysis case study for the Google Data Analytics Professional Certificate. The analysis explores Cyclistic trip data to understand the behavioral differences between casual riders and annual members.

## 🎯 Business Task
Analyze historical bike trip data to identify how casual riders and annual members use the service differently. The goal is to provide data-driven recommendations for a marketing strategy aimed at converting casual riders into annual members.

## 🔍 Key Findings
**Usage Patterns**: Casual rider usage peaks strongly on weekends (leisure), while members use the service consistently throughout the work week (commuting).

- **Trip Duration**: Casual riders take significantly longer trips (more than double the average) than members.

- **Bike Preference**: Casual riders show a strong preference for electric bikes, indicating a focus on convenience and fun.

- **Geography**: The most popular stations for casual riders are located near tourist attractions and parks.

## 💡 Recommendations
1. **"Weekend Fun" or E-Bike Membership Tier**: Launch a new, more affordable membership level that targets recreational weekend riders and offers incentives for e-bike usage.
2. **Geo-Targeted Marketing**: Deploy digital and physical advertising at "hotspots" frequented by casual riders (parks, museums) with messaging focused on leisure rather than commuting.
3. **In-App Conversion Prompts**: Use push notifications after a long casual ride, showing the user the potential savings they would have achieved with a membership.

## 🛠️ Technical Skills Demonstrated
- **Data Cleaning & Transformation** with `dplyr` and `tidyr`.
- **Exploratory Data Analysis** and date manipulation with `lubridate`.
- **Data Visualization** with `ggplot2`.
- **Large File Management** with Git LFS.
- **Reproducible Reporting** with R Markdown.
- **Business Storytelling** and strategic recommendations.

## 📁 Project Structure
- `bike_share_analysis.Rmd` - Complete R Markdown analysis file.
- `index.html` - Rendered HTML report, hosted on GitHub Pages.
- `data/` - Folder containing the source CSV file (managed with Git LFS).
- `README.md` - This project summary.

## 🎯 Live Demo
**View the full interactive HTML report:**  
📊 [https://NicolayF.github.io/bike-share-case-study](https://NicolayF.github.io/bike-share-case-study)

## 🚀 How to Run This Analysis

1. Install **R**, **RStudio**, and **Git LFS** (as the data file is large).

2. Clone the Repository and then run git lfs pull in your terminal to download the actual CSV data file.

3. **Install Packages** (first time only)
   - Open RStudio
   - Copy and paste this into the console:
   ```r
   packages <- c("tidyverse", "lubridate", "knitr", "kableExtra", "ggplot2", "scales")install.packages(packages)
   ```

4. **Load Analysis**
   - Open **bike_share_analysis.Rmd** in RStudio.
   - Run All (Ctrl + Alt + R)
   - Press the "**Knit**" button to generate a report.
