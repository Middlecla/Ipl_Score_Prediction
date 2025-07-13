# Ipl_Score_Prediction
In today’s world of cricket every run and decision can turn the game around. Using Deep Learning to predict IPL scores during live matches is becoming a game changer. This article shows how advanced algorithms help us to forecast scores with impressive accuracy, giving fans and analysts valuable insights in real time.
#Table of content
1. Installing Libraries
We are importing all necessary Python libraries such as NumPy, Pandas, Scikit-learn, Matplotlib, Keras and Seaborn required for data handling, visualization, preprocessing and building deep learning models.
2. Loading the Dataset
The dataset can be downloaded from here. It contains data from 2008 to 2017 and contains features like venue, date, batting and bowling team, names of batsman and bowler, wickets and more. We will load the IPL cricket data from CSV files into pandas DataFrames to explore and prepare for modeling.
3. Exploratory Data Analysis
We will do Exploratory Data Analysis (EDA) to analyze how many unique matches have been played at each venue by counting distinct match IDs for every venue. Then, we’ll visualize this data using a horizontal bar chart to see which venues host the most matches.
4. Performing Label Encoding
We will convert categorical text data into numeric labels using Label Encoding because ML models work with numbers.

LabelEncoder() converts text labels into integers.
fit_transform() learns encoding and applies it.
copy() : creates a duplicate of the DataFrame to avoid changing the original data
5. Performing Feature Selection
drop() : removes specified columns from the DataFrame
corr() : computes pairwise correlations between numerical features
sns.heatmap() : creates a colored matrix to visualize correlations with values
plt.show() : displays the plot on screen
6. Splitting the Dataset into Training and Testing
DataFrame indexing (data_encoded[feature_cols]) : selects specified columns as features
train_test_split() : splits features and target into training and test subsets
test_size=0.3 : assigns 30% of data for testing
random_state=42 : ensures reproducible splits by fixing the random seed
7. Performing Feature Scaling
8. Building the Neural Network
9. Training the Model
10. Evaluating the Model
11. Creating an Interactive Widget for Score Prediction










