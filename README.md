# Individual Portfolio
As I last said, I'm taking this course to practice my data processing skills and want to get acquainted with basic knowledge of machine learning. I have previously worked with Python and ArcGIS, and I am eager to expand my familiarity with their data processing functions. My background is in environmental science, but more within the realm of natural science, where my understanding of data science and its practical applications is limited. I want to explore how Python and ArcGIS can be leveraged for enhanced data processing within the context of an environment-topic project. 

For the methodology, our project was divided into three parts :
Data Wrangling: Compiling the dataset with features such as county name, consumption pattern, production pattern, and installed capacity of solar panels by merging client, train and county name json files.

Exploratory Data Analysis: Analysing the data through visualization in Seaborn, Matplotlib and ArcGIS
Total Production and Consumption Pattern Over the years
Installed Capacity, Production and Consumption per County
Installed Capacity, Production and Consumption per Year
Consumption and Energy Prices over 2021 - 2023
Mean Solar Radiation, Mean Installed Capacity and Mean Production

Feature Engineering and Machine Learning: Predicting the production and consumption per hour of a day in the future using historical data. 
Separating consumption and production patterns for prediction
Separating the train set, test set and validation set
Getting Hyperparameter
Training mean consumption and mean production using LightGBM, CatBoost and Ensembled Model of the two.

Evaluation
Mean Absolute Error (MAE) calculation
Access to our raw data is via this link: https://wageningenur4.sharepoint.com/:f:/r/sites/course239381/Gedeelde%20documenten/Group%204/Data?csf=1&web=1&e=s6zTE2

My experience with machine learning has been a bit limited, primarily due to time constraints for the course and the difficulty associated with learning all the codes for machine learning manipulation. However, by helping my colleague summarize all the steps and analyze output, I have managed to understand the foundational workflow and the key functionalities of each machine learning tool we used. While I have not had the opportunity to apply these techniques, I am looking forward to potentially diving deeper into machine learning in the future for my thesis if possible. For now, I have developed a general picture in assessing different methods based on specific project requirements, such as time limitations, model running speed, and the required precision of results, thereby helping me to make better-informed decisions regarding each software’s applicability for different contexts.

In the project, I dedicated myself to improve abilities in data wrangling and visualization, specifically by practicing and mastering the intricacies of plotting data and their trends through trials of different code structures. The practical application of these skills significantly contributed to our project's success in visualization. Although we encountered difficulties such as memory errors, compatibility issues with JSON files, and challenges related to graph labelling, our team successfully sought out and found effective strategies to overcome these challenges. This learning process has not only broadened my skill set in problem-solving and effective searching for error-handling information, but has also built me a sense of accomplishment, making me realize the importance of perseverance in data analysis.
The detailed codes are shown in Jupyter Notebook, where part 1 is the code I wrote for data wrangling, part 2 is for visualization, and part 3 is the wrangling step before importing data into ArcGIS.
The result of my visualization is shown in the file named “Figures_Yalin”.

As we mentioned, we are working on a real-world project set up by Kaggle to solve the energy imbalance issue in Estonia. Currently, we stand at the 321st place out of 2732 participants. I find this result satisfying as our prediction demonstrates a high level of accuracy in forecasting the energy consumption patterns of prosumers, proved by the low mean absolute error we have calculated.
While the outcome of our prediction may not be considered during the final round of this competition, the project provided us with invaluable insights into exploring the relationships between energy usage, environmental conditions, and economic background. Working on this real-world example has been a profoundly meaningful and interesting experience. Despite the unavoidable deficiencies in such a short period, the knowledge gained and understanding achieved are rewarding and would definitely benefit my future learning journey. 

Last but not least, I gained ample useful knowledge on how to carefully deal with data in a safe and ethically sound way and reflected on the ethical deficiencies in our project. The utilization of data and algorithms, as well as data usage regarding governance, have raised many ethical issues related to important things like security, human rights, and societal values. The understanding of these factors makes me more sensitive about proper data usage and raises responsibility in integrating this knowledge into my future endeavors, particularly in the process that could affect decision-making.

In conclusion, throughout the project, I learned new codes and techniques for visualization that revealed the relationship between energy usage and other related factors. We successfully attained an optimal prediction model that is capable of estimating the energy production and consumption of Estonian prosumers with the maximum accuracy we can reach. Although the result is not top-ranked, the learning process provided valuable insights to explore a real-world scenario. The learning of ethical considerations also benefits my understanding of correct data usage in different contexts. 
In the end, I would thank my colleague for contributing so much to the machine learning stuff, which the rest of the group is not familiar with at all. Due to time constraints, I was unable to work closely with my colleague to learn about machine learning, but I did gain a general understanding of its functioning and the associated pros and cons. I now have a grasp of the key concepts and methods in machine learning, including its ability to improve over time, identify trends and patterns, and its susceptibility to errors and lack of transparency. This foundational knowledge will be valuable in my field in the future.
