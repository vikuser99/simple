---
permalink: /ai_ds/
title: "AI and Data Science"
author_profile: true
redirect_from: 
  - /ai_ds.html
---


For this project, I used an NBA dataset to explore different questions about player performance. I came up with around 10 questions and used data analysis to find patterns and relationships in the data.

I used Python along with libraries like pandas, numpy, and matplotlib to clean the data and create different types of graphs. These included scatter plots, bar charts, and trend comparisons to help visualize relationships between stats like age, height, scoring, usage, and efficiency.

The goal of the project was to understand what actually affects player performance. For example, I looked at how age impacts scoring and assists, how height affects rebounding, and how usage rate and efficiency relate to scoring output.

After creating the visualizations, I wrote short analysis notes for each section explaining what the graphs showed and what conclusions could be made from the data. I also compared different player types like stars, role players, shooters, and rebounders to see what separates them statistically.

In the end, I put everything together into a presentation that summarized the main findings. The project helped me get more comfortable using Python for data analysis and showed me how data can be used to answer real questions in basketball.

## Some plots 
How Does Age Affect Player Impact?

Net Rating measures the point differential per 100 possessions while a player is on the court. A higher Net Rating generally indicates a greater positive impact on team performance.

Conclusion: Net Rating generally improves as players gain experience and approach their prime years. The upper quartile (Q3) remains high into the early 30s, suggesting that elite players are often able to maintain their impact longer than the average player.

![Police Pic](/simple/images/box1.png){:width="100%"}

Rebounds per game measure how many missed shots a player recovers during a game. Rebounding is important because it creates extra possessions and limits second-chance opportunities for opponents. To explore this relationship, I compared player age and rebounds per game across multiple NBA seasons.

Conclusion: Rebounding is usually strongest during a player's prime years. While younger and older players can still be effective rebounders, the highest concentration of strong rebounding seasons occurs between the mid-20s and early-30s.

![Police Pic](/simple/images/histo1.png){:width="100%"}

True Shooting Percentage (TS%) is a measure of scoring efficiency that accounts for field goals, three-pointers, and free throws. It provides a more complete measure of efficiency than field goal percentage alone. The graph below shows how scoring efficiency changes across different age groups using the lower quartile (Q1), median, mean, and upper quartile (Q3).

Conclusion: Scoring efficiency increases with age and experience before leveling off later in a player's career. The steady increase across all quartiles suggests that players often become more efficient as they develop.

![Police Pic](/simple/images/line1.png){:width="100%"}

<h3>NBA Analytics Presentation</h3>

<p>
This presentation summarizes the questions, analysis, visualizations, and conclusions from my NBA data analytics project.
</p>

<div style="text-align:center;">
  <iframe
    src="https://docs.google.com/presentation/d/e/2PACX-1vSylg866to2cwAGAWI0EtfyCDihtMOgYxYQgHhv3hMkdjG7jQAzndYtmhLmz6JDAz38WA9Thd5RSYF3/pubembed?start=false&loop=false&delayms=3000"
    frameborder="0"
    width="960"
    height="569"
    allowfullscreen="true"
    mozallowfullscreen="true"
    webkitallowfullscreen="true">
  </iframe>
</div>


