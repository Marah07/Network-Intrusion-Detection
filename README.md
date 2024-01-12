# Network-Intrusion-Detection
The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
• Normal
• Anomalous

here's a brief enumeration of the steps you performed during the Exploratory Data Analysis (EDA):

1) Data Understanding:

Description: The dataset represents simulated intrusions in a military network environment, capturing raw TCP/IP dump data. It includes connections, each labeled as either 'Normal' or a specific 'Attack Type.' The features encompass both quantitative and qualitative attributes, providing a detailed view of network activity.

2) Visualizations:

- Univariate Analysis: 
--> Explored individual features to understand their distributions and characteristics.
--> Utilized histograms, kernel density plots, and box plots to visualize the spread and central tendency of quantitative variables.
--> Examined the frequency distribution of qualitative variables.

- Bivariate Analysis:
--> Investigated relationships between pairs of variables, especially focusing on potential correlations or patterns.
--> Employed scatter plots, correlation matrices, and other visualizations to understand connections between features.

- Multivariate Analysis:
--> Explored interactions between multiple variables simultaneously.
--> Utilized techniques such as heatmaps, pair plots, and parallel coordinates plots to reveal complex relationships.

3) Sampling:

- Explored different sampling techniques, such as random sampling or stratified sampling, to create representative subsets of the data.
- Evaluated the impact of sampling on data distribution and characteristics.
- 
4) Hypothesis Testing:

- Description: Applied hypothesis testing to validate assumptions or explore significant differences in the dataset.
- Steps:
--> Identified relevant hypotheses related to the dataset, such as differences in means or distributions.
--> Chose appropriate statistical tests (e.g., t-tests, Mann-Whitney U test) based on the nature of the hypotheses and data distribution.
--> Conducted hypothesis tests to determine the statistical significance of observed differences.

5) Data Preprocessing
   
Removing Null Values (if exists)
Encoding Categorical Data
Scaling Data

6) Modeling
   
1. Supervised Learning
   
a. Feature Selection
b. Dataset Partition
c. Fitting Models

3. Unsupervised Learning
   
a. Clustering
b. Anomaly Detection
c. Dimensionality Reduction

5. Deep Learning
   
7) Model Evaluation
