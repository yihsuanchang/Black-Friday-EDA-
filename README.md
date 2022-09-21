# NTNU-Python Final project
## BlackFriday EDA
### Data Preparation

i.	Change Data type 

Turn columns that mixes with strings and numbers to numeric data: Age -> Age_group 


### Analyze Data
#### Data Description
i.	537,577 transactions, 13 variables

ii.	There are no null values in the dataset except product_catergory2 has 166,986 null values and product_catergory3 has 373,299 null values.

iii.	There is no duplicated data in this dataset.

####  **User’s**  data analysis: retrieve distinct UserID, and analyze each variable to prevent the same User from adding up data.

i. There are **5891 users** in this dataset

ii. There are **4225 male** users and **1666 female** users, **Male users** are more than female
 
iii. Most Users’ age is around **26-35 years old (group3) 
 
iv. Most Users’ occupation is categorized in **No.4, and No.8 is the less**
 
v. Most Users live in **City C**
 
vi. Most users stay in their current city for **one year**
 
vii. **Not married users** are more than married user

viii. Rank of **User’s Purchase amount**         
| UserID  |Total Purchase Amount | Purchase count | Average Purchase amount |
|:-------:|:--------------------:|:--------------:|:-----------------------:|
| 1004277	|10536783	             | 978	          | 10773.80675             |
| 1001680	| 8699232	             | 1025	          | 8487.05561              |
| 1002909	|	7577505	             | 718	          | 10553.62813             |
| 1001941	|	6817493	             | 898	          | 7591.863029             |  
| 1000424	| 6573609	             | 695	          | 9458.430216             |
| 1001181 | 6387899              | 861	          | 7419.162602             |
| 1000889	|5499812	             | 822	          | 6690.768856             |

Rank of **User’s Average Purchase amount**
|UserID	|Average Purchase amount | Purchase count |
|:-----:|:----------------------:|:--------------:|
|1005069|	19278.375000 |	16 |
|1003902|	18777.247312 |	93 |
|1005999|	18345.944444 |	18 |
|1001349|	18162.739130 |	23 |
|1000101|	17511.369231 |	65 |

According to the tables above, the user who has the highest purchase amount is not the one who spends the most at one time but the one who **frequently purchases**.

#### Overall Transaction Data Analysis
i. Rank of **Product’s sales**
|ProductID|sales|
|:-------:|:---:|
|P00265242|	1858|
|P00110742|	1591|
|P00025442|	1586|
|P00112142|	1539|
|P00057642|	1430|

ii.	There are **3623 products**

iii.	**Males’ transactions** are more than female’s
 
iv. **Ages 26-35** have the most transaction
 
v. **City B** has the most transaction
 
vi.	**Not married user’s transactions** are more than married user’s
 
vii. **Male users’ average purchase amount** is more than female users’
 
viii.	There is **no significant difference** in the purchase amount between each age group
 
ix.	Users who live in **City C** have the highest purchase amount at one time 
 
###  Correlation between variables
i.	Product categories have a high correlation with each other, product category 2 has the most correlation with 1 and 3.

ii.	Age has a positive correlation with Marital Status

iii.	Age has a relatively positive correlation with occupation, marital status, and product category 

iv.	The user’s purchase amount has a negative correlation with product category 1
 


Data Source : https://www.kaggle.com/datasets/sdolezel/black-friday
