# H1 Indian Food Data Analysis and Visualization
Overview
This project focuses on Exploratory Data Analysis (EDA) and Data Visualization of an Indian food dataset. The dataset provides information on various Indian dishes, including their ingredients, dietary classifications, preparation and cooking times, flavor profiles, and regional details. The analysis uses Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly to explore and visualize the data.

Dataset
The dataset indian_food.csv includes the following columns:

name: Name of the dish.
ingredients: List of ingredients used in the dish.
diet: Dietary classification (e.g., vegetarian).
prep_time: Preparation time in minutes.
cook_time: Cooking time in minutes.
flavor_profile: Flavor profile of the dish (e.g., sweet).
course: Course of the dish (e.g., dessert).
state: State in India where the dish originates.
region: Region in India where the dish originates.
Sample Data:

name	ingredients	diet	prep_time	cook_time	flavor_profile	course	state	region
Balu shahi	Maida flour, yogurt, oil, sugar	vegetarian	45	25	sweet	dessert	West Bengal	East
Boondi	Gram flour, ghee, sugar	vegetarian	80	30	sweet	dessert	Rajasthan	West
Gajar ka halwa	Carrots, milk, sugar, ghee, cashews, raisins	vegetarian	15	60	sweet	dessert	Punjab	North
Ghevar	Flour, ghee, kewra, milk, clarified butter, sugar	vegetarian	15	30	sweet	dessert	Rajasthan	West
Gulab jamun	Milk powder, plain flour, baking powder, ghee, sugar	vegetarian	15	40	sweet	dessert	West Bengal	East
Project Components
Data Loading and Preparation:

Load the dataset from Google Drive.
Clean the data by handling missing values and incorrect entries.
Exploratory Data Analysis (EDA):

Analyze frequency distributions of categorical variables like diet, flavor_profile, course, state, and region.
Explore the distribution and statistics of prep_time and cook_time.
Investigate unique values in categorical columns.
Data Visualization:

Pie Chart: Distribution of different diets.
Bar Charts:
Top 10 dishes with the shortest cooking times.
Top 5 dishes with the longest preparation and cooking times.
Histograms: Distribution of preparation and cooking times.
Cross-Tabulation Bar Plot: Relationship between diet types and flavor profiles.
Word Cloud: Visualization of the most common ingredients.
