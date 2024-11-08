# Academic Projects 

# Fraud Detection Performance Testing of Pick-and-Choose Graph Neural Network (PC-GNN)
•	Fraud Detection – Graph Neural Network Analysis

This project aimed to understand the mechanism of a cutting-edge graph neural network model, the Pick-and-Choose GNN (PC-GNN), and evaluate its effectiveness in fraud detection. We collected several fraud detection datasets with different relational characteristics to test the model's performance. Our findings showed that PC-GNN efficiently and accurately identified fraud when interactions between entities were dense. However, when entities were connected primarily through similarity-based relationships, the model struggled to effectively learn data features, significantly reducing its fraud detection capability. Therefore, the effectiveness of this model in fraud detection relies heavily on the user's understanding of the relationships between entities and the ability to construct a meaningful relational data structure.

[Fraud Detection Performance Testing of PC-GNN (code and report)](https://github.com/YahanCong/data586_pcgnn.git)

# Spatial Analysis and Predictive Modeling of Coyote Distribution in British Columbia     
•	Spatial Statistical Analysis of Coyote

This project aimed to explore the spatial distribution of coyotes in British Columbia and identify key environmental factors influencing their distribution. For this project, I collected geographic distribution data on coyotes in BC and conducted exploratory data analysis using tools such as heatmaps and pair correlation functions (PCF) to gain initial insights into distribution patterns and clustering. Next, to investigate the primary factors affecting coyote distribution, I applied spatial modeling and developed a Generalized Additive Model (GAM) based on environmental variables. The analysis revealed that the most influential factors were water distance and the Human Footprint Index. Additionally, the model achieved a high level of accuracy in predicting coyote distribution patterns.

[Spatial Analysis of Coyote Report](https://github.com/YahanCong/data589project/blob/main/DATA589_Project_Spatial_Analysis_of_Coyotes.pdf)

# Real Estate Dashboard Development for NYC Investors and Homebuyers

This project aimed to design an intuitive and comprehensive dashboard to display real estate information for New York City. To provide users with a clear understanding of properties currently on the market, we developed an interactive map of New York City. By clicking on property icons, users can easily view details such as location, price, and type of property. We also integrated Google API functionality into the map, enabling users to explore the surrounding area, including the distribution of amenities like shopping centers and parks.

To give users a broader perspective on city-wide housing prices, we created charts displaying price distributions by region and property type, allowing users to quickly understand the typical price range for properties they are interested in. Additionally, we included information on major real estate agencies in each area to help users connect with local experts. The final dashboard provides users with a convenient, comprehensive view of essential information for purchasing a home, from property details and neighborhood planning to price distributions and buying channels, supporting informed and rational investment decisions.

[NYC housing price dashboard introduction](https://github.com/erinkhc/NYC-housing-price)

[Heroku link for NYC housing price dashboard](https://nyc-b429e9209531.herokuapp.com/)

# Seoul Bike-Sharing System Demand Forecasting and Operational Status Prediction

This project aimed to understand how factors such as weather, seasons, and holidays influence the operational status and rental demand of Seoul's bike-sharing system. To gain an initial understanding, we conducted exploratory data analysis (EDA) to observe trends in system availability and rental demand under different weather conditions and on weekdays versus holidays. Additionally, we performed a time series analysis on bike rentals to assess the presence of strong seasonal or daily cycles.

Next, we developed predictive models for both system availability and bike rental demand. For predicting system operational status, we built a Gradient Boosting classification model, which successfully forecasted whether the bike-sharing system would be open or closed. Observing a strong daily cycle in demand from our EDA, we constructed a Long Short-Term Memory (LSTM) Neural Network model to forecast hourly bike demand. Our LSTM model accurately predicted bike demand based on current weather conditions and rental data from the previous day.

[Seoul Bike-Sharing System Analysis](https://github.com/Isawsomethingb4/Seoul-Bike-Sharing-Demand-Analysis.git)

# Python Package for Orchard Inventory and Financial Management

This project involves developing an Orchard Management Package in Python to streamline various aspects of orchard business operations, including fruit production, inventory, and sales. The package comprises two main components: a Production module and a Management module. The Production module stores crop information, calculates fruit prices, and manages planting areas. The Management module facilitates inventory tracking, sales order storage, and financial information management, with automatic time series chart generation for historical inventory data using matplotlib. Data manipulation within the package is handled by the pandas library.

The project is managed on GitHub with continuous integration and testing conducted through Travis CI.

[Orchard Package (GitHub)](https://github.com/YahanCong/data533_project3.git)

[Pypi Package Link](https://pypi.org/project/orchardmanagementCL/)

# Life-expectacy-Research

•	Life expectancy – Regression Analysis


This project aimed to explore the difference of best predictors for life expectancy in developed and developing countries. In this project, we collected nearly 200 countries' life expectancy data and trained them with linear regression. In order to optimize the linear regression model and verify the interchangeability of the linear model for developed, developing countries and worldwide, we utilized the best regression subsets and model accuracy metrics, such as Cp, AIC, and adjusted R^2. We have found that the best predictor for developing and developed countries is very different. Thinness is the best predictor for developed countries, and Schooling, HIV and AIDS are the most influential factors for developing countries. We also found that the linear model for developing countries is near to the worldwide linear model.

[Life-expectacy-Research-Report](https://github.com/YahanCong/Life-expectacy-Research/blob/7fc8dc2b411a7fbdbfff55b4fe4b644ab127cd2d/Final%20report,%20STAT306.pdf)


# Data Science Job Salaries Analysis

•	Data Science Job Salaries Analysis

This project aimed to explore data scientists' salaries increasing/decreasing trend, salaries distribution and the most influential factors for data scientists' salary levels. In this project, I collected data scientists' salaries dataset from 2020 to 2022, and made exploratory data analysis for it, including but not limited to analyzing and virtualizing salary increasing trends and salaries' distribution depending on working years, working experience, working region and working competence. And depending on global scientists' salary distribution, I divided data scientists' wages into three levels, and used classification models including logistical regression, random forest and neural network to explore the relationship between data scientists' salary level and the possible covariates. I have found out that the best model for salary level classification is random forest, and the most effective factors are job title, employee residence and company location. 

[Data-science-job-salaries-analysis](https://github.com/YahanCong/Life-expectacy-Research/blob/0bb9592f6a93f4be3205fe0cd986c022ce639b2a/econ%20323%20final%20project.ipynb)


#	Vancouver Tour Advice

•	Vancouver Tour Advice

This project aimed to investigate Vancouver's best daily trip schedule for fresh UBC students. We collected data of Great Vancouver's tour attractions, selected the 12 most visited attractions and tried to design a "best" tour plan with the most attractions visited by combinatorial optimization tools. In order to shorten the visiting time most, we transformed the one-day tour question as a Travelling Salesman Problem(TSP), and utilized heuristic method and programming tools to solve the integer regression problem for attractions selection. And to reduce the time cost while planning and make our trip schedule more flexible, we optimized the Vancouver attractions selection by transforming it as a 0/1 Knapsack problem, and solved it by dynamic programming.

•	Report for Vancouver Tour Advice

[Best_Vancouver_Daily_Tour_Report](https://github.com/YahanCong/Research_experience/blob/5d648bf061e739b3e98b08db75dfaf5e1155ecba/Best_Vancouver_Daily_Tour.pdf)

•	Code for Vancouver Tour Advice

[Vancouver_Tour_advice_TSP](https://github.com/YahanCong/Research_experience/blob/a4a1431e4eae5503903475fb8a8eaa58c89d3718/Best_vancouver_tour_TSP.ipynb)

[Vancouver_Tour_advice_knapsack](https://github.com/YahanCong/Research_experience/blob/bd4d4f3ccea5c548939840662bb0373ac65f1140/Best_vancouver_tour_knapsack.ipynb)

# Simulation of the background ticket system

•	Simulation of the background ticket system

This project aimed to simulate the ticket system's background by Java. You can enter the simulated system as an administrator, reset identification information, and work as a ticketing staff: store new tickets' information from the back-end panel, including ticket's starting point, destination, ticket type, and check any ticket's information. 

[ticket_system_code_java](https://github.com/YahanCong/Simulation-of-the-background-ticket-system.git)
