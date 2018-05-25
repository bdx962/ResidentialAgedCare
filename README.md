###### The Australian population is living longer due to better living conditions and medical breakthroughs. The Australian bureau of statistics predicted that the Australian population will live past 80 years old. Increased pressure in life hinders family for being physically responsible for their aged. Hence the growth of residential aged care facilities. 
###### This report will be looking at the following: 
  ###### •	Is residential aged care a good business model?
  ###### •	Emotional aspects towards aged care
  ###### •	Government funding influencing factors

###### Reports from the Department of Health – Ageing and Aged Care have stated that the number of current places in a residential aged care will not be able to support the growing population. Therefore, a new residential aged care facility is a good business model in Sydney for the future. With that in mind, the goal is to identify factors impacting a residential aged face facility. 

###### A residential aged care is defined as a special-purpose facility which provides accommodation and other types of support, including assistance with day-to-day living, intensive forms of care, and assistance towards independent living, to frail and aged residents. A residential place is a bed or place where an aged person is accommodated. 

###### For this analysis, a few assumptions were made as follows:
###### •	Future residential beds are based on the level of occupancy against the population of people who are 65 years old and over
###### •	All factors related to the care of the elderly are sufficient and remains constant. An example is the staff to patient ratios. 
###### •	The location of the residential aged care facility may not be the location where a person has lived most of their life. An example would be a person entering residential aged care facility that is located where his/ her children are currently residing. 
###### •	The government funding provided for each residential aged care facility in 2017 does not require adjustment
###### •	The estimated population will have a high fertility rate ie: A_65

###### For relevancy of this analysis, the focus will be on the following:
###### •	State of NSW
###### •	Sydney suburbs
###### •	Population 65 years old and above

###### The limitation of the dataset used is the non-granularity of it. The dataset was obtained from Australian Bureau of Statistics and Department of Health – Ageing and Aged Care where it has been summarized to a reporting level. It is not known what assumptions have already been made and what were the original outliners. 

###### The second limitation is the type of data scrapped from Aged Care Reviews website and Whirlpool Forum to obtain the reviews of residential aged care in general for sentiment analysis. For this phase, there was sufficient reviews to analyze the data. However, the volume of reviews for aged care is not as high as reviews for a popular movie. Therefore, sentiment analysis may not be comprehensive enough. 

###### To identify suitable factors that would impact a residential aged care, the longitude and latitude of each residential aged care facility is used to calculate the distance to the Prince of Wales Hospital and Bondi Beach. These key landmarks are selected as it would be logical to have a residential aged care near to an excellent hospital or a recreational area in Sydney. The other variable identified is the current places for each facility. Using both distances and current places, a prediction is made to determine the level of funding received by the government. The following models were used and their results:

  ###### •	Logistic Regression – 97%
  ###### •	K Nearest Neighbours (KNN) – 65.61%
  ###### •	GridSearch – 97.42%
  ###### •	Support Vector Machine (SVM) – 97.52% 

###### The coefficient is the places in a facility. This suggest that the number of places in a facility has a higher impact than the distance to the hospital and the beach. The coefficient is the places in a facility. This suggest that the number of places in a facility has a higher impact than the distance to the hospital.

###### Based on current information, managing a residential aged care facility could be a lucrative business despite the strict regulations. However, the emotional aspects of entering a residential aged care needs to be considered for sustainability. As a final exercise, reviews were scrapped from Whirlpool regarding persons in residential aged care. From a layman’s perspective, the general sentiment about going into residential aged care is gloomy and disheartening. However, using the Textblob model to perform the sentiment analysis states otherwise. With a silhouette score of above 70%, the positive sentiment was higher than the negative. This suggest that entering a residential aged care is a necessary rather than emotional decision. 

###### Moving forward, the analysis will continue to determine if the government funding provided for each residential aged care facility is dependent on the location affluence. From another perspective, we can analyse if the government funding will influence the private cost of an individual residing in a residential aged care. 
