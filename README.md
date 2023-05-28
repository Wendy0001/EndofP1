# Unveiling Success Factors in Original Video Content Creation: Insights from Industry Analysis
## Overview 
In my Microsoft project, I am working towards specific objectives that aim to drive strategic decision-making in the realm of original video creation. The primary focus is on utilizing data analysis techniques to gain a comprehensive understanding of the video content landscape and the complexities associated with the industry. By leveraging data, I aim to extract valuable insights that can inform our strategies in entering and thriving in the competitive world of original video creation. Through this project, I seek to identify the production infrastructure, budget efficiency, industry recognition and strategic partnerships. The ultimate goal is to develop a successful video content creation strategy that sets Microsoft apart in the market.
## Business Understanding 
Microsoft's endeavor to enter the original video creation space presents a significant business challenge that requires a comprehensive understanding of the industry landscape. Through meticulous industry market analysis, the primary objective is to align our efforts with stakeholder goals, and capital improvement. To achieve this, I will conduct a thorough assessment of the competitive landscape to gain insights into how other industry players are performing. Furthermore, I will diligently analyze potential risks and develop robust mitigation strategies to safeguard Microsoft's interests in this new business venture. To solidify my approach, a comprehensive financial analysis will be conducted to assess the feasibility and potential return on investment. By quantifying the financial implications, benefits, and risks associated with the project, we will provide a solid foundation for decision-making and demonstrate the viability of our strategic endeavor.
## Stakeholder and Key Business Questions
1) How to gain insights into how other industry players are performing?
2) What are the benefits of industry recognition and the establishment of strategic partnerships?
3) How production budgets are distributed?
## Data Understanding and Analysis 
I will commence the analysis by examining the provided data sets encompassing industry players, industry recognition, strategic partnerships, and production budgets. My initial focus will be on ensuring the data's cleanliness, consistency, and suitability for analysis. Once prepared, I will proceed to calculate descriptive statistics for the pertinent variables and generate insightful visualizations based on the derived variables. Additionally, I will conduct extensive research on the benefits associated with industry recognition and the establishment of strategic partnerships. Incorporating this acquired knowledge, I will enrich my analysis and provide a comprehensive understanding of the advantages and impacts of industry recognition and strategic alliances. Furthermore, I will delve into the distribution of production budgets within the dataset, conducting a budget analysis. This will involve calculating summary statistics such as the mean, median, and standard deviation of the budgets and visualizing the budget distribution using histograms or box plots. Lastly, I will meticulously interpret the findings obtained through data exploration and analysis, extracting key insights and trends related to the performance of industry players, the benefits of industry recognition and strategic partnerships, as well as the distribution of production budgets. These insights will serve as the foundation for addressing the specific questions at hand and formulating actionable recommendations and strategies based on the available data.
## Source of Data 
The data used in this project was retrieved from:
 1) https://www.themoviedb.org/
 2) https://www.boxofficemojo.com/
 3) https://www.imdb.com/
 4) https://www.rottentomatoes.com/
 5) https://www.the-numbers.com/
 ## Description of Data
 i) movie_gross.csv. This file provides valuable insights and information to improve original video content. By analyzing the movie gross file, I can identify movies that have achieved significant box office success depending on production budgets. This information helps us understand the revenue potential of original video content and identify strategies to maximize returns on investments.
ii)movie_budgets.csv. The movie budget file contains data on the production budgets of different movies. By analyzing this data, I am able to gain insights into how budgets are allocated across various components of the production process, such as script development, talent acquisition, production design, visual effects, marketing, and distribution. This information can help us understand the relevance of industry recognition and strategic partnerships.
## Extract Transform Load 
I did a summary run down on my data using the following steps;                                                                                                     
 a) I integrated my dataframes using the concatenation method.                                                                                                     
 b) I displayed the shape and type of my dataframe.                                                                                                               
 c) I dropped columns in this step.                                                                                                                               
 d) I then went ahead and checked for duplicates.                                                                                                                 
 e) I used the keep=False to keep all duplicates and sort_values to put duplicates next to each other.                                                             
 f) Finally, I removed my duplicates.
## Data Preparation
The initial step is to ensure the cleanliness, consistency, and analysis readiness of the data. This involves addressing any inconsistencies in data, missing values, misspelled text data, outliers, imbalanced data, and invalid data. Furthermore, I will thoroughly examine the data for any inconsistencies or discrepancies, resolving them through appropriate data transformation or cleaning methods. If required, I will also consider converting data types to their appropriate formats for accurate analysis. Additionally, I will create new variables that can provide further insights and enhance my analytical capabilities.
## Data Analysis and Visualization
1) Financial Feasibility: Based on my analysis, I discovered a positive correlation between the production budget of a movie and its resulting profits. The data suggests that investing more in the production budget tends to yield better financial outcomes. 
![for readme, visualizations](https://github.com/Wendy0001/EndofP1/assets/132939772/c2580d84-bdd5-46ad-8b47-dc7e69fd46ea)
2) Production Infrastructure: A robust production infrastructure allows studios to handle large-scale productions with complex logistical requirements. It enables the management of multiple film projects simultaneously, facilitates the coordination of large production crews, and accommodates extensive post-production activities. The ability to handle ambitious projects expands the creative possibilities for studios and positions them to take on diverse and ambitious film ventures. The top 5 studios in the world right now are IFC, Uni, WB, Fox, Magn and we can infer that these studios are successful because of their infrastructural capacity and marketing and distribution channels. To go a step further I was able to illustrate that Fox studio had the highest figure in movies produced.
![for readme, visualizations2](https://github.com/Wendy0001/EndofP1/assets/132939772/7842589c-a103-4a27-b088-1c14609fdbd6)
3) Industry Recognition and Partnerships: In the data analysis subsection of the project, I investigate the advantages of strategic partnerships between renowned studios in the movie industry and other established and previously successful individuals. Specifically, I focus on examining the top 10 highest budgeted movies and highlight how these films benefited from strategic collaborations with industry-recognized producers, writers, actors, directors, and other creative professionals. By analyzing these examples, I aim to shed light on the positive outcomes and potential value generated through such strategic partnerships and high investment on the production budget.
![for readme, visualizations3](https://github.com/Wendy0001/EndofP1/assets/132939772/8458fb42-e922-4e84-9634-13bf6884f1b4)
4) Correlation Analysis: A correlation coefficient of -0.79 suggests a strong negative correlation between the 'count' and 'year' variables in the given dataset. The negative sign indicates that as the value of one variable 'year' increases, the value of the other variable 'count' tends to decrease. In my analysis, this correlation implies that over the years, there has been a decreasing trend in the counts of movies produced by the top studios. As the years progress, the counts of movies produced by the top studios tend to decrease. It's important to note that correlation does not imply causation, and further analysis is required to understand the underlying factors influencing this negative correlation.
![for readme, visualizations4](https://github.com/Wendy0001/EndofP1/assets/132939772/0d4f2d5d-a297-4445-b28f-de4f84453e5c)
## Conclusion
Firstly, I conducted a thorough analysis of the potential return on investment by comparing the projected revenue against the estimated production budget. The findings revealed a positive correlation between the production budget and the resulting profits. This suggests that investing more in the production budget tends to lead to better financial outcomes.
Secondly, I explored the importance of a robust production infrastructure for studios. A robust infrastructure enables studios to handle large-scale productions, manage multiple projects simultaneously, coordinate large production crews, and facilitate extensive post-production activities. This infrastructure expands creative possibilities and allows studios to undertake ambitious film ventures.
Lastly, I delved into the advantages of strategic partnerships within the movie industry. By analyzing the top 10 highest budgeted movies, I showcased how these films benefited from collaborations with renowned industry professionals, including producers, writers, actors, directors, and other creative individuals. This analysis highlighted the positive outcomes and value generated through such strategic partnerships and emphasized the importance of high investments in the production budget.
Overall, this project has provided a comprehensive understanding of the industry landscape, financial considerations, production infrastructure, and the benefits of strategic collaborations. These insights can guide Microsoft in making informed decisions and developing effective strategies as they venture into original video content creation.
