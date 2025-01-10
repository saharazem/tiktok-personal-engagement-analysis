# TikTok Engagement Analysis vs Personal Posting Behavior

## Overview
This project explores the relationship between my TikTok engagement habits—such as browsing, liking videos, saving sounds, and following trends—and my personal posting behavior on the platform. The goal is to analyze patterns in engagement and posting to uncover correlations and insights into how social media influences creative output.

## Hypothesis
The hypothesis of this project is that my engagement habits on TikTok directly influence the themes, styles, and creative decisions in my personal posts.

## Scope of the Project
- **Data Overview:**
  - The dataset includes my TikTok activity data, such as browsing history, liked videos, favorite sounds, personal posts, and profile information.
- **Analysis:**
  - Focused on trends in posting behavior, engagement data, and the relationship between them.
  - Explored how browsing habits and saved sounds influence posting patterns.
- **Visualization:**
  - Created graphs and charts to present insights into posting trends, sound usage, and engagement patterns.
- **Hypothesis Testing:**
  - Statistical tests (e.g., Chi-square) were used to evaluate correlations between engagement habits and posting behavior.

---

## Directory Guide
Here’s where to find the relevant files and folders in this repository:

- **TikTokData/**  
  Contains all original TikTok data files that were exported directly from TikTok. These files were ignored in the analysis for privacy reasons but include:
  - `Browsing History.txt`
  - `Favorite Sounds.txt`
  - `Follower.txt`
  - `Following.txt`
  - `Like List.txt`
  - `Post.txt`

- **extracteddata/**  
  Includes manually extracted and processed data used for the analysis:
  - `manual_liked_videos_updated.csv`: Contains manually extracted data for liked videos.
  - `manual_posted_videos.xlsx`: Contains manually extracted data for posted videos.

- **.gitignore**  
  This file excludes the `TikTokData/` folder from version control to ensure the privacy of original TikTok data.

- **DSA210 ProjectReport.pdf**  
  The full project report detailing the analysis, results, and conclusions.

- **DSA210ProjeFinal.ipynb**  
  A Jupyter Notebook with all the Python code I used for data cleaning, visualization, and analysis for this project.


---

## Tools and Techniques
- **Python:** Used for data cleaning, analysis, and visualization.
- **Jupyter Notebook:** For organizing code and generating graphs.
- **Google Docs:** Used for the creation of the final report.

---

## Deliverables
- **Full Report:** See [DSA210 ProjectReport.pdf](./DSA210_ProjectReport.pdf) for detailed analysis and findings.
- **Code and Visualizations:** See [DSA210ProjeFinal.ipynb](./DSA210ProjeFinal.ipynb) for Python code and generated graphs.

---
## Conclusion
This project highlights how my TikTok engagement habits influence my creative output. While the results fail to reject aspects of the hypothesis, they also reveal additional factors influencing my posting behavior, including trends, seasonality, spontaneous posting, and personal preferences. These insights demonstrate that creative decisions on TikTok are shaped by a combination of engagement patterns and external influences.

---

## Limitations
- **API Restrictions:** Due to TikTok API limitations, manual data extraction was required for some categories, such as hashtags and favorite sounds.
- **Content Matching:** Hashtag and theme analysis relied on general trends, which may not perfectly reflect video content.
- **Future Work:** Automated data collection methods and extended datasets could enhance the accuracy and scope of the analysis.
