# Analyzing-Ad-Campaigns-A-B-Test-with-Python
Analyzing Ad Campaigns A/B Test with Python

### Background
The company has been experimenting with changing the format of their advertisements and has been showing the new version (version B) to a subset of users across various social media platforms. The objective is to analyze whether the new ad version B is outperforming the original ad version A. This type of analysis, known as an A/B Test, helps in determining the effectiveness of different marketing strategies.

### Executive Summary
This project focuses on analyzing the effectiveness of two different ad versions (A and B) using Python and pandas. By merging multiple datasets and performing aggregations, we calculated the click-through rates (CTR) for each ad version, analyzed the performance across different social media platforms, and compared the effectiveness on various devices. The results suggest that ad version B consistently outperforms ad version A.

### Goals of Analysis
Calculate the click-through rate (CTR) for each ad version.
Determine if the effectiveness of ads varies across social media platforms.
Identify whether mobile, PC, or tablet users should be more heavily targeted in future campaigns.

### The dataset at a glance 
The image below shows the number of views recorded for both versions of the ad and the newer version which is the version B has the highest views of 7270.



### Methodology
- Data Import and Exploration: Imported and explored the datasets for users and advertisements.
- Data Merging: Merged the datasets on user_id and timestamp to create a comprehensive view of the user sessions.
- Aggregations: Performed aggregations to calculate CTR for each ad version and analyzed performance across different platforms and devices.
- Detailed Analysis: Conducted further analysis by breaking down the results by weekdays vs. weekends.

### Key Insights
- Ad Version Performance: Ad version B consistently outperformed ad version A across all metrics, including overall click-through rates and performance on different social media platforms and devices.
- Social Media Platforms: TikTok showed the highest click-through rates for ad version B, suggesting it is particularly effective for younger demographics.
- Device Types: Ad version B was most effective on mobile devices, indicating that mobile users are more responsive to the new ad format.
- Weekday vs. Weekend: There was no significant difference in views between weekdays and weekends, but ad version B maintained its higher performance throughout the week.

### Recommendation
- Ad Version: Continue using ad version B as it has consistently shown higher effectiveness compared to ad version A.
- Target Platforms: Focus on advertising on TikTok and other social media platforms where ad version B performed best.
- Device Targeting: Prioritize mobile users in future ad campaigns, as they showed the highest responsiveness to ad version B.
