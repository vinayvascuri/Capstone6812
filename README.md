
# Home Credit Default Risk Analysis : Project Overview
![OIP (1)](https://github.com/vinayvascuri/Capstone6812/assets/121827398/b39e0c16-5d2e-45d5-a14f-4f1076daee62)

# Introduction:

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.

# Business Problem:
The business problem for the Home Loan Credit Risk analysis project is to build a predictive model that can assess the credit risk of individuals applying for home loans. Home Credit wants to minimize its risk exposure by identifying potential borrowers who are likely to default on its home loans. By analyzing historical loan data and borrower information, the goal is to create a model that accurately predicts whether a loan applicant is likely to default or not.

# Project Objective:
The project's objective is to develop a machine learning model that can effectively predict the creditworthiness of loan applicants for home mortgages. The model will be trained on historical loan data containing various attributes such as income, marital status,employment history, loan amount, and other relevant features. By using this historical data, the model will learn to recognize patterns and correlations that are indicative of a high or low credit risk.

# Your group's solution to the business problem.

Our group's solution to the Home Credit Risk Analysis involved building a predictive model using machine learning techniques. Out of all the models employed, the Light Gradient Boosting (LGB) model followed by Random forest model turned out to be best models in assessing the creditworthiness of potential borrowers, particularly those with limited credit histories. The above two models received the best Kaggle score of .671 and .662 respectively.In this case, to address class imbalance in the dataset, we have used Upsampling and downsampling techniques. Ultimately, our solution contributed to Home Credit's mission of broadening financial inclusion and providing a positive borrowing experience for the unbanked population.

# Your contribution to the project

In the Home Credit Risk Analysis project, my primary contribution was to lead the data preprocessing and feature engineering stages. I collaborated with the team in brainstorming sessions we had on weekly basis in understanding of the dataset to understand the alternative data sources, including telco and transactional information, and integrated this data with the existing client attributes to create a comprehensive dataset. Through careful analysis and transformation of the data, I engineered meaningful features that captured crucial insights into borrowers' repayment abilities. Additionally, I played a key role in addressing class imbalance by applying a combination of upsampling and downsampling techniques to ensure a balanced training dataset for the predictive models. My efforts in optimizing the data representation and handling class imbalance significantly improved the model's performance in accurately predicting credit risk for the unbanked population. Throughout the project, I actively participated in EDA, Data cleaning, Model selection, evaluation, and interpretation, providing valuable insights and recommendations to enhance the model's transparency and fairness. Ultimately, my contributions contributed to Home Credit's mission of expanding financial inclusion and empowering clients with a positive and safe borrowing experience.

# The business value of the solution.

# Difficulties that your group encountered along the way.

Throughout the Home Credit Risk Analysis project, our group encountered several challenges that required careful consideration and problem-solving. The significant difference in the number of loan defaulters and non-defaulters made it challenging to build a model that could accurately predict both classes. One of the main difficulties was dealing with the class imbalance in the dataset. We had to experiment with various upsampling and downsampling techniques to strike the right balance between the classes without introducing bias or overfitting.

Moreover, interpreting and explaining the model's predictions was a significant challenge. As we used machine learning algorithms, understanding the decision-making process and providing transparent explanations for model predictions were not straightforward tasks. We dedicated considerable effort to employ model interpretability techniques and feature importance analysis to gain insights into the factors influencing credit risk predictions.

Additionally, the project had strict timelines and limited resources, which added pressure to meet deadlines and efficiently allocate tasks among team members. All the team members are either in Full-time job roles or in Internships at various organizations. Regular communication and collaboration were essential to overcome these time constraints and ensure the project's progress remained on track.

Overall, the difficulties we encountered in dealing with class imbalance, handling complex alternative data, interpreting model predictions, and managing project constraints were valuable learning experiences. By working collaboratively, seeking innovative solutions, and adapting our approaches, we successfully navigated these challenges and delivered a robust credit risk prediction model for Home Credit.

# What you learned in the project.

The Home Credit Risk Analysis project provided me with invaluable learning experiences across various aspects of data science and machine learning. Firstly, it is my first project deploying various machine learning models into a dataset which resulted in a good idea of how various machine learning models work. Also, I gained a deeper understanding of the challenges associated with imbalanced datasets and the importance of handling class imbalance effectively. 

The project also taught me the value of effective collaboration and communication within a team setting. Regular meetings, clear task allocation, and leveraging each team member's expertise were crucial for project success, particularly given the project's strict timelines and limited resources.

Overall, the Home Credit Risk Analysis project deepened my understanding of data science methodologies and their application in real-world scenarios. It enriched my skill set in handling imbalanced data, integrating diverse data sources, and interpreting complex machine learning models. The project's challenges and learning experiences have further motivated me to continue honing my data science expertise and contributing to impactful solutions in the field.











