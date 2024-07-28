# **Analysis and Mitigation of Delays in Animation Production**

[Back to Portfolio](https://github.com/diamond-one/Data-Analytics-Portfolio)

### **Introduction**

This project explored analyzing delays in the animation production process across three studios—StudioA, StudioB, and StudioC. My primary goal was to leverage data-driven insights to identify patterns, understand potential delays, and suggest strategies to enhance scheduling accuracy and overall production efficiency. The project focused on using data analysis to identify potential delays and develop mitigation strategies to minimize their impact, thereby enhancing scheduling accuracy and overall production efficiency.

### **Data Collection and Methodology**

**Data Sources and Tools:**
- I collected detailed episode-level metrics from the studios, including:
  - **Time Scheduled:** Initial estimates of time required for each phase.
  - **Time Actually Spent:** Actual time taken to complete each phase.
  - **Time Spent on Revisions:** Duration spent on rounds of revisions and adjustments.
  - **Time Spent on Each Phase:** Breakdown of time allocation across various phases such as blocking and spline.
  - **Team Headcount:** Accounting for fluctuations due to sick days, vacations, and other factors affecting availability.
  - **Episode Complexity:** Assessment of the complexity level of each episode, including factors like the number of characters, scene intricacy, and special effects.

Data processing and analysis were carried out using Python’s pandas library, with visualizations created using Matplotlib and Seaborn. These tools enabled the analysis of trends and patterns critical for identifying delays and the factors contributing to scheduling discrepancies.

**Analytical Techniques:**
- **Descriptive Statistics:** I used measures such as mean, median, and standard deviation to summarize central tendencies, dispersion, and the shape of data distributions.
- **Trend Analysis:** I applied fundamental analytical techniques to discern trends and patterns within the production schedules.

**Timeframe and Scope:**
- The analysis covered an 18-month period, offering a comprehensive view of scheduling practices and their impact on production timelines.

### **Key Analytical Steps**

1. **Exploratory Data Analysis (EDA):**
   - I conducted EDA to assess data quality, identify outliers (e.g., episodes with significantly longer production times), and understand correlations between key variables. This included visualizing the distributions of estimated, scheduled, and actual times to uncover discrepancies. This step was crucial for understanding the baseline patterns and identifying potential areas for developing mitigation strategies.

2. **Delay Pattern Identification:**
   - Historical data were analyzed to pinpoint common patterns and causes of delays during the blocking and spline stages. I evaluated the consistency and accuracy of initial estimates against actual outcomes, highlighting areas for improvement. This analysis provided critical insights into recurrent delay patterns, which were instrumental in formulating effective mitigation strategies.

### **Findings and Solutions**

**Data Insight:**
The analysis revealed systematic discrepancies in scheduling, with frequent overestimations (e.g., underestimating the time required for complex scenes) and underestimations during the blocking and spline stages. These inaccuracies were linked to factors such as team size, episode complexity, and team capacity variations due to sick days and vacations. These discrepancies were key to understanding the factors contributing to delays, enabling the development of targeted mitigation strategies.

**Solution:**
- **Enhanced Scheduling Techniques:** I refined the scheduling methods to better anticipate potential delays using straightforward analytical techniques.
- **Dynamic Buffer Implementation:** I introduced a dynamic buffer system based on historical data, such as adding an additional 10-20% time buffer to tasks prone to delays, providing more flexibility and responsiveness in scheduling.
- **Production Efficiency Calculator:** I designed a tool for producers to input key variables like episode complexity, headcount, and specific animator skills. This calculator generated timelines for episode completion, offering detailed breakdowns for each phase, helping set realistic expectations and plan resources more effectively.

**Visualization:**
![5481035b-8b50-48bb-8e29-1df8600ceb82](https://github.com/user-attachments/assets/31c929df-c018-4576-8c9e-7a9980813422)

his visualization illustrates the discrepancies between estimated and actual times, highlighting patterns that were crucial in implementing dynamic buffers and refining scheduling practices.

### **Key Insights and Recommendations**

- **Recognizing Trends in Scheduling:** Using trend analysis and descriptive statistics helped identify potential delays, leading to more precise scheduling and resource allocation. These insights were crucial in formulating proactive mitigation strategies, such as dynamic buffer implementation.
- **Adaptive Scheduling:** I recommended adopting adaptive scheduling practices that adjust buffers in real-time based on insights from the data, such as dynamically adjusting team sizes or extending deadlines to minimize the impact of delays.

### **Conclusion**

This analysis provided a focused examination of trends related to delays in animation production, particularly during the blocking and spline stages. By using basic analytical techniques like trend analysis and conducting thorough Exploratory Data Analysis (EDA), I identified discrepancies in scheduling that could be mitigated by implementing buffer times. The introduction of tools like the Production Efficiency Calculator empowered producers to plan timelines more accurately, optimize resource allocation, and reduce delays.

The adoption of adaptive scheduling practices and dynamic buffers ensured that production schedules could respond effectively to real-time data. Additionally, standardizing data entry and providing training in effective scheduling techniques enhanced data consistency and schedule reliability.

These strategies were expected to significantly improve scheduling accuracy and production efficiency, leading to better project management and reduced costs over time. The methodologies and tools developed through this project set a new standard for data-driven decision-making in animation production, offering a scalable framework that can be adapted across various production environments.

[Back to Portfolio](https://github.com/diamond-one/Data-Analytics-Portfolio)
