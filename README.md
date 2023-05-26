# Accenture-North-America-Virtual-Intership-project-Data-Analytics-and-Data-Visualization
This virtual internship is based on analysis about Social Media & content creation company **Social Buzz** .Social Buzz is fast growing technology unicorn that need to adapt quickly to its global scale and we help them in their marketing strategy.

## Tools use in this Social buzz Analysis
* **Excel** for Data cleaning
* **Power Query** for Data Modeling
* **Tableau** for Data Visualization
* **Power Point** for Data Representation

## Datasets use in Social Buzz Analysis
We use three datasets provided by accenture north america in this project
* Reactions
* Content
* Reaction type

## Data Cleaning 
Firstly we clean these three datasets using excel 
#### 1.Reactions 
##### Null  values
Column Name : Type  ( we remove rows having blanks in this column by using filter) 
##### Remove unwanted columns
Column Name : User Id  ( we already have content Id column for user representation so we don't need it for analysis)
##### Check Data types
Column Name     Data Type 
* content type = general
* Reaction Type = text(string)
* Datetime = datetime   
##### Rename Columns 
Column name : Type = Reaction type
####  2.Reaction Type 
##### Check Data types
Column Name     Data Type 
* Sentiment  =  text(string)
* Reaction Type = text(string)
* Score = number 
##### Rename Columns 
Column name : Type = Reaction type
#### 3.Content 
##### Check Data types
Column Name     Data Type 
* content type = general
* content Type = text(string)
* category =   text(string) 
##### Remove unwanted columns
* Column Name : User Id  ( we already have content Id column for user representation so we don't need it for analysis)
* Column Name : URL   (we don't need email id for users in analysis)

## Data Modeling
we combine these three datasets by using merge query in power query editor .
Firstly we merge **Reaction** table by **Content** using **content Id** of **Content** table and **Reaction** table as primary key then we merge **Reaction Type** table to existing table by using **reaction_type** column of **Reaction** and **Reaction Type** Table.

## Data Analysis
we represent our key finding in form of Power Point presentation which is shown in folder and we also make a Tableau dashboard.
Here is the link of final Tableau dashboard.
https://public.tableau.com/app/profile/wajiha.ahmed/viz/SocialBuzzAnalysis_16844149166300/Dashboard1

# Thank You For Reading

