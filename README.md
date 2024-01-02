# Capstone Proposal(Ventures Vision )

## Group Members:

- Rana AlHababi
- Nour AlDahan
- Khawlah AlHadlaq

## Objectives:
The main goal of this project is to develop a predictive model that can assess the likelihood of success in opening a cafe or restaurant based on the location. The primary objective is to provide potential entrepreneurs and investors with valuable insights that can inform their decision-making process and increase the chances of a successful venture.

## Dataset Description:
#### We used six different dataset:
##### Frist dataset: Cafes and restaurant of Riyadh ( data was collected through data scraping from google map API )
- The number of rows: 2000
- The number of columns: 21
- Data Description (meaning):
Cafes and restaurant of Riyadh based on neighhood location lat and lng of radias of 1500 meter, it have information like rating and number of people who rated, number of officces and compaines and hotels nearby.
- The number of Missing values: Zero 

##### Second dataset:data was collected through data scraping from google map API
- The number of rows: 37,000
- The number of columns: 3
- Data Description (meaning):
reviews of Cafes and restaurant of Riyadh collected with a max of 10 for each place with the rating the user give.
- The number of Missing values:while extracting the data the was empty returens which was few therefore we dropped these values.

##### Third dataset:Open Saudi data (Riyadh Population neighhood)
- The number of rows:163
- The number of columns:5
- Data Description (meaning):
the dataset give the population for each neighhood in riyadh 
- The number of Missing values:Zero

##### Fourth dataset:Open Saudi data (Saudi  Population by age group )
- The number of rows:56,000
- The number of columns:7
- Data Description (meaning):
the dataset give the population for each age group 0 to 100 years old , it was used after driving the ratio for each group 
- The number of Missing values:Zero 

##### Fifth dataset:Open Saudi data (labour force rate)
- The number of rows:15
- The number of columns:28
- Data Description (meaning):
the data gives the rates for labers by age group and gender 
- The number of Missing values:Zero 

##### Sixth dataset:Github(Riyadh  neighhoods)
- The number of rows:167
- The number of columns:5
- Data Description (meaning):
the data containes riyadh neighhoods neames in arabic and english and the geo points of neighhood border 
- The number of Missing values:Zero 


##### Seventh dataset:Kaggle (Store for Rate)
- The number of rows:10,000
- The number of columns:19
- Data Description (meaning):
the data contains information about places open for rent with price and space and other info for saudi, it was filtered to have only stores in riyadh. 
- The number of Missing values:Yes, we didn't handle the missing values because we didn't use the columns that have missing values



## Dataset :
The dataset encompasses diverse information pertaining to Riyadh's cafes and restaurants, organized by neighborhood with corresponding latitude and longitude coordinates within a 1500-meter radius. Details include ratings, the number of ratings received, and the proximity of offices, companies, and hotels in the vicinity. Additionally, the dataset incorporates user reviews for each establishment, limited to a maximum of 10 reviews per place, along with the associated user ratings. Demographic insights are provided, featuring neighborhood-wise population figures and age distribution statistics, segmented into groups ranging from 0 to 100 years. Further demographic nuances include labor rates categorized by age group and gender. The dataset also comprises the names of Riyadh's neighborhoods in both Arabic and English, accompanied by geographic coordinates outlining neighborhood borders. Notably, information about available rental spaces in Riyadh is included, specifically focusing on stores, with details such as price, space, and relevant attributes for the Saudi context. It is worth noting that the dataset was meticulously filtered to exclusively include stores located within Riyadh.
 ## Algorithms:
We used:
 * DNN for sentiment analysis with accurcy of 85%.
 * K-mean for success clustering (unsupervised).
 * DNN for location effect on success with accurcy of 80%.

## Dashboard : 

https://github.com/013nour/Location-effect-on-business-success/assets/50384785/a549f7ef-5659-402c-8e36-2da2c173e8d0

