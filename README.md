# Explanatory-Data-Analysis-Challenge-Olympic-Games-

### Data Import

#### Import the Datasets Summer (summer.csv), Winter (winter.csv) and dictionary (dictionary.csv) and Inspect!

### Merging and Concatenating

#### 1.	Merge Summer and Winter (one row for each Medal awarded in any Olympic Games) and save the merged DataFrame in olympics.

#### 2.	An additional column (e.g. "Edition") shall indicate the Edition -> Summer or Winter.

#### 3.	Add the full Country name from dictionary to olympics (e.g. France for FRA).

### Data Cleaning

#### 1.	If you haven´t done it yet: Assign appropriate Column Headers to Country Codes (e.g. "Code") and full Country Names (e.g. "Country").

#### 2.	Remove Spaces from column headers in olympics and dictionary.

#### 3.	For some Country Codes, there is no corresponding full Country Name available (e.g. for "URS") -> missing values in olympics. Identify these Country Codes and search the Web for the full Country Names. Replace missing values! (Alternatively, you can find a Solution for this at the end of this Notebook!)

#### 4.	Remove rows from olympics where the Country code is unknown. (Make sure you reset the Index -> RangeIndex)

#### 5.	Convert the column Medal into an ordered Categorical column ("Bronze" < "Silver" < "Gold")

### most successful countries of allFor the next questions, use Seaborn plots.

#### 1.	What are the Top 10 Countries by total medals?

#### 2.	Split the total medals of Top 10 Countries into Summer / Winter. Are there typical Summer/Winter Games Countries?

#### 3.	Split the total medals of Top 10 Countries into Gold, Silver, Bronze.

 ### GDP, Population and Politics matter
 
#### 1.	Create the following aggregated and merged DataFrame with Top 50 Countries (you can see an excerpt with the first 12 Countries). The Column Total_Games shows the number of Participations (as an approximation: determine the number of Editions where Countries have won at least one medal).

#### 2.	Convert the absolute values in the DataFrame into ranks and save the ranks DataFrame in new variable (see screenshot). Ranks are more meaningful than absolute numbers.

### Statistical Analysis and Hypothesis Testing with scipy

#### In the follwing work with Ranks! Check whether GDP (Standard of Living), Total_Games (Political Stability measure) and Population (Size) have an effect on Total Medals. (hint: work with spearman correlation, not with pearson correlation)

### Aggregating and Ranking

#### Create the following Seaborn Heatmap with Medal Ranks for Top 50 Countries (Total Medals, Summer Games Medals, Winter Games Medals, Men, Women).

### Summer Games vs. Winter Games - does Geographical Location matter

#### Identify Countries that are

#### 1.	equally successful in Summer and Winter Games

#### 2.	more successful in Summer Games

#### 3.	more successful in Winter Games

### Men vs. Women - does Culture & Religion matter

#### Identify Countries where

#### 1.	Men and Women are equally successful

#### 2.	Men are more successful

#### 3.	Women are more successful

### Traditions matter

#### Create the following Seaborn Heatmap that shows the Ranks of Top 50 Countries by Sports.

#### Identify traditional Sports / National Sports for e.g. UK and China!
