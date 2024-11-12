## Google Advanced Data Analytics Certification Projects Summary

To fulfill the requirements of the Google Advanced Data Analytics certification program, I completed a series of courses and corresponding projects. These projects demonstrate my practical proficiency in various aspects of data analytics.

### Courses Completed:

**1.Foundations of Data Science**
Gained a solid understanding of the foundational concepts of data science, its history, and how it has evolved to become a critical tool for solving complex business problems. Learned about the impact of data today, how it is utilized in various industries, and the growing demand for data professionals.
Explored the key skills and tools that data professionals use to manage, analyze, and interpret data, as well as how data-driven insights can be used to help organizations make informed decisions. I studied the PACE project workflow (Plan, Analyze, Construct, Execute) and its importance in organizing data projects.

**2.Get Started With Python**
In this course, I gained a solid foundation in Python programming and its application in data analysis. I learned how to write Python scripts and programs to solve data analysis tasks and became familiar with Python's syntax, data structures, and control flow.

I also worked extensively with Jupyter Notebooks for interactive coding, which allowed me to run code and visualize results seamlessly. Through hands-on practice, I gained experience in using variables and data types to store, organize, and manipulate data. I learned essential coding skills, including the use of functions and conditional statements to write clean and reusable code.

Additionally, I explored loops for automating repetitive tasks and worked with string manipulation techniques such as slicing, indexing, and formatting. I investigated core Python data structures like lists, tuples, dictionaries, sets, and arrays, understanding how to use them effectively for data organization and management.

Furthermore, I gained practical experience with popular Python libraries, such as NumPy and Pandas, which are essential for performing data manipulation and analysis. To demonstrate my skills, I completed a final project in which I applied my Python knowledge to solve a business problem using real datasets, drawing meaningful insights from the data.

**3.Go Beyond the Numbers: Translate Data into Insights**
In this course, I developed proficiency in exploratory data analysis (EDA), learning techniques to identify and understand key patterns, trends, and insights within datasets. I gained hands-on experience in cleaning raw data by removing inconsistencies, errors, and outliers, a crucial step for ensuring accurate analysis.

I studied the process of data validation and data joining, ensuring that datasets were complete and accurate for analysis. I also learned how to use Python for performing EDA tasks, including discovering patterns, sculpting data, and preparing it for deeper analysis.

A significant part of the course involved creating data visualizations to present key insights clearly and compellingly. I used tools like Tableau, as well as Python libraries such as Matplotlib and Seaborn, to visualize data and communicate my findings effectively.

Additionally, I focused on ethical and professional data storytelling, ensuring that insights were presented in a way that was both accessible and understandable for stakeholders.

**4.Power of Statistics**
In this course, I acquired foundational knowledge in statistics, learning to distinguish between descriptive and inferential statistics. I developed the ability to summarize datasets using descriptive statistics, measuring central tendency, spread, and the relative position of data.

I gained expertise in probability theory, including Bayes' theorem, and explored various probability distributions, such as binomial, Poisson, and normal distributions. I also studied sampling methods to draw valid conclusions from sample data, minimizing sampling bias, and using sampling distributions to make accurate estimates.

Additionally, I learned how to calculate and interpret confidence intervals, providing a measure of uncertainty in estimates. I also studied hypothesis testing, including t-tests and Chi-squared tests, to assess statistical significance and determine whether results were due to chance.

To apply these statistical techniques, I completed a final project where I analyzed a workplace dataset using the methods learned throughout the course.

**5.Regression Analysis: Simplify Complex Data Relationships**
In this course, I developed a strong understanding of building regression models, including both linear and logistic regression, and how to use them to describe complex data relationships. I learned to build and interpret simple linear regression models, as well as advanced multiple linear regression models, to identify correlations between variables.

I gained insight into key concepts in machine learning, such as overfitting, model selection, and the bias-variance tradeoff, all of which are critical when working with regression models. I also applied statistical tests like Chi-squared and ANOVA (Analysis of Variance) to assess relationships in categorical data. Additionally, I explored binomial logistic regression for classifying data into two categories.

To put this knowledge into practice, I completed a final project where I built a regression model to analyze a real-world dataset, drawing actionable insights from the analysis.

**6.The Nuts and Bolts of Machine Learning**
In this course, I gained a solid understanding of machine learning principles and methodologies, focusing on both supervised and unsupervised learning techniques. I learned how to apply various machine learning algorithms to solve real-world problems, including classification, regression, and clustering tasks such as K-means.

I worked with popular machine learning algorithms like decision trees, random forests, XGBoost, gradient boosting, and ensembling techniques, gaining practical experience in training and evaluating these models. The course emphasized model validation and techniques to assess model accuracy, ensuring I could identify and prevent overfitting.

I also learned important data preprocessing techniques, including feature engineering and feature selection, to improve model performance. By the end of the course, I applied the skills I learned to a final project, where I used machine learning models, including K-means clustering, XGBoost, and ensembling methods, to analyze a workplace scenario dataset and provide actionable recommendations.


## Projects main idea:

"At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company and grow your career.

TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently."

*Note: Every project in this portfolio is based on the scenario described above, which is an imaginary one created for educational purposes to complete the Google Advanced Data Analytics certification. Additionally, the same dataset is used for each project.*

### Projects:


**[Project 2: Exploratory Data Analysis (EDA), Data Cleaning, and Visualization]** 
Description: The goal of this project was to prepare the TikTok claims dataset for analysis by gaining an understanding of the data, cleaning it, and performing initial exploratory data analysis (EDA). We began by constructing a dataframe in Python and conducting a cursory inspection of the dataset to compile summary information about its structure and content. We then identified key variables, such as claim_status, and analyzed their distribution. The dataset revealed a balanced number of claims (9,608) and opinions (9,476), which helped us understand the structure of the data. Additionally, we examined viewer engagement, focusing on video duration and view count. Our analysis showed that claims videos had higher mean and median view counts compared to opinions. These initial insights provided the foundation for the next phase of model development, guiding further exploration into variables and preparing us for hypothesis testing and statistical analysis.




**[Project 3: Exploratory Data Analysis (EDA), Data Cleaning, and Visualization Sharing]**
In this project, we continued to explore and clean the TikTok claims dataset, with a focus on understanding the variables and relationships within the data. A key objective was to examine how user engagement metrics, such as video view count, like count, and comment count, influence the classification of videos as claims or opinions. During the exploratory data analysis, we found that the majority of videos had low engagement, with a skewed distribution in both view and like counts. Specifically, more than half of the videos had fewer than 100,000 views, and a similar pattern was observed with likes. Furthermore, the comment count variable was also heavily right-skewed, with most videos receiving fewer than 100 comments.

Additionally, we discovered over 200 null values across seven different columns, which highlighted the need for future analysis to address missing data in model development. These findings, including the imbalance in the number of claims and opinion videos, and the skewed data distribution, were important considerations for the machine learning model. The data's characteristics, including its null values and skewness, will influence model selection and help shape future predictions.

As part of the project, visualizations were created using Python (Matplotlib and Seaborn) and Tableau, showcasing key data insights like the distribution of claims versus opinions, and providing clear visualizations of user engagement metrics. These visualizations are intended to support the TikTok team’s decision-making and guide the next steps in model development.



**[Project 4: Data Exploration and Hypothesis Testing]**
In this project, the TikTok data team focused on hypothesis testing to analyze the relationship between verified account status and video view count. The goal was to determine if there were significant differences in video engagement based on account verification status.

The analysis began by calculating the mean video view counts for verified and unverified accounts, revealing a substantial difference: unverified accounts had an average of 265,663 views compared to 91,439 views for verified accounts. To further validate these findings, a two-sample hypothesis test was conducted. This test confirmed that the observed differences in video views between the two groups were statistically significant and reflected real differences in the broader population.

These findings suggest that verified and unverified accounts exhibit different patterns of user engagement. The team speculated that unverified accounts might either post more engaging content or be associated with spam bots that artificially inflate view counts.

Based on these insights, the team recommended proceeding with the development of a regression model that incorporates verified status to further investigate user behavior. This analysis will inform the design of the claim classification model by considering how verified status impacts video engagement.



**[Project 5: Regression Model Building for Claims Classification]**
In this project, the TikTok data team aimed to build a logistic regression model to predict a user's verified status, as verified users are more likely to post opinion videos. This model serves as a precursor to a claims vs. opinion classification model, helping the team better understand how video characteristics correlate with verified users.

The logistic regression model was constructed using various video features, and the results showed that video length was significantly associated with the likelihood of a user being verified, with longer videos correlating to higher odds of a user being verified. Other video features, such as likes, views, and comments, showed a weak association with verified status. The model achieved a precision of 69%, a recall of 66%, and an F1 accuracy of 66%, which indicates a moderately good ability to predict verified status.

Based on these findings, the team recommends using video length as a key predictor in future classification models. The next step involves using the insights gained from this regression model to build a classification model to distinguish between claim and opinion videos, ultimately assisting TikTok in more efficiently managing user submissions.



**[Project 6: Model Building, Evaluation, and Findings Summary]**
In this project, the TikTok data team aimed to build a machine learning model to assist in the classification of videos as either claims or opinions. The goal of the model is to predict whether a TikTok video presents a claim or an opinion, which will help reduce the backlog of user reports and prioritize them more efficiently.

To achieve this, the team built two tree-based classification models: Random Forest (RF) and XGBoost. Both models were used to predict the outcome on a held-out validation dataset, and the model with the best recall score was selected. The final model was then used to score a test dataset to estimate future performance.

Both the RF and XGBoost models performed exceptionally well, with the RF model achieving a recall score of 0.995. The model showed only five misclassified samples out of 3,817 in the test dataset, indicating excellent performance. The primary predictors for the model were related to video engagement levels, such as video view count, like count, share count, and download count. These features accounted for nearly all the predictive signal in the data, with higher engagement levels being strongly associated with claim videos. In fact, no opinion video had more than 10,000 views.

The model performed exceptionally well, and before deployment, the team recommends further evaluation using additional subsets of user data to ensure its robustness. They also suggest monitoring the distributions of video engagement levels to ensure that the model remains effective despite fluctuations in its most predictive features.



### Data Dictionary:

The dataset contains 19,383 rows and 12 columns:

| Column Name             | Type   | Description                                                                                     |
|-------------------------|--------|-------------------------------------------------------------------------------------------------|
| #                       | int    | TikTok assigned number for video with claim/opinion.                                             |
| claim_status            | obj    | Whether the published video has been identified as an "opinion" or a "claim."                    |
| video_id                | int    | Random identifying number assigned to video upon publication on TikTok.                           |
| video_duration_sec      | int    | How long the published video is measured in seconds.                                             |
| video_transcription_text| obj    | Transcribed text of the words spoken in the published video.                                      |
| verified_status         | obj    | Indicates the status of the TikTok user who published the video in terms of their verification.   |
| author_ban_status       | obj    | Indicates the status of the TikTok user who published the video in terms of their permissions.    |
| video_view_count        | float  | The total number of times the published video has been viewed.                                    |
| video_like_count        | float  | The total number of times the published video has been liked by other users.                      |
| video_share_count       | float  | The total number of times the published video has been shared by other users.                     |
| video_download_count    | float  | The total number of times the published video has been downloaded by other users.                 |
| video_comment_count     | float  | The total number of comments on the published video.                                             |

### How to Use:

1. Clone this repository to your local machine.
2. Navigate to the project directory of interest.
3. Follow the instructions in the project's README file to reproduce the analysis or view the results.








