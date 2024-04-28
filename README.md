Win-Prediction-Analysis


In the fast-paced world of IT consulting, winning lucrative deals is a game-changer. This project embarks on a data-driven journey to not only predict the probability of winning deals but also to discover the winning combinations of Bid Managers and SBU (Strategic Business Unit) Heads. The insights gleaned from this endeavor will empower the IT consulting company to strategically allocate resources, prioritize opportunities, and, ultimately, meet ambitious growth targets.

Market Outlook:
The IT industry thrives on securing substantial projects by offering tailored solutions to clients across diverse sectors. These projects vary in terms of client industries, solution requirements, technology stacks, and project scopes. With deal values often soaring into the millions, the competition is fierce. Even a slight improvement in the win rate can translate into significant revenue gains for IT firms.

By accurately predicting the probability of winning each deal, engagement teams can effectively manage their opportunity pipelines. Armed with this foresight, deal engagement managers can assign resources judiciously to the most promising deals, ensuring that the company thrives in the highly competitive landscape.

Overview of the Problem:
Your organization invests significant effort into preparing bids, but the challenge lies in knowing which opportunities are worth pursuing. With multiple bid managers and SBU Heads vying for each opportunity, it becomes a complex task for management to match the right bid manager with the right SBU Head. Your role is to assist the organization in identifying the optimal bid manager-SBU Head pairings that can convert opportunities into wins, leveraging the provided data.

##Project Objectives:

Objective 1:
Predictive Analytics - Develop a machine learning model to forecast the probability of winning or losing in bidding activities for potential clients.

Objective 2:
Prescriptive Analytics - Identify the variables most likely to influence the conversion of an opportunity into a successful win.

Tools and Libraries Used:
Python in a Jupyter Notebook environment for data analysis, preprocessing, and model development. Tableau for data visualization and insights.

Libraries Utilized:
Pandas for data manipulation. Numpy for numerical operations. Matplotlib and Seaborn for data visualization. Roadmap to the Project:

Exploratory Data Analysis:
Conduct a multivariate analysis to gain insights into win-loss counts and percentages using tables created with PrettyTable library.

Data Preprocessing:
Handle missing values by replacing them with the mode. Address zero values in the Deal Cost column by replacing them with the mean and apply logarithmic transformation to balance skewed data. Manage outliers by capping extremes using the 3rd Interquartile Formula. Implement Target Encoding for independent categorical variables and Label Encoding for dependent variables. Perform feature selection via a HeatMap analysis.

Model Building:
Split the data into training and testing sets with a 70:30 ratio and scale the data. Utilize various machine learning models; however, the Random Forest Classifier stands out as robust to outliers, resistant to overfitting, and delivering the highest accuracy.

Model Accuracy & Performance:
Achieve an impressive 84% accuracy with the Random Forest Classifier.
