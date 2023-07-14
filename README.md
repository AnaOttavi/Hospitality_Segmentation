# Data Mining Project in Hospitality Segmentation

This repository contains:
- dataset
- report
- jupyter notebook
- presentation


**BACKGROUND**
Hotel H belongs to an independent Hotel Chain C, located in Lisbon, Portugal. Hotel Chain C operated 4 hotels until 2015 and has been acquiring new ones since then. Furthermore, the Hotel Chain C created a marketing department and a new marketing manager position as part of its efforts to grow in the Hospitality market.
The Hotel Chain C knows that understanding current customers allows organizations to identify groups of customers that have different characteristics and behaviors. Understanding them is vital in every industry once the process of finding new customers begins by learning as much as possible from the existing ones.
The current Hotel Chain C actual segmentation is based on the origin of the sales and is done according to the hospitality standard market segmentation. The new marketing manager A considers that the segmentation does not fulfill the current needs and does not allow the organization to make better strategic choices about opportunities, product definition, positioning, promotions, pricing and target marketing, once it only reflects one of the customers’ characteristics.
A new customer segmentation would allow the board and the marketing manager, A, to create and drive strategic options to improve the perceived value to the customers, market value proposal and profits.

**BUSINESS OBJECTIVES**

The main business objectives of our project are:
● Identify the characteristics and behaviors that should be used to segment the customers;
● Provide a segmentation solution and profile in terms of characteristics and behaviors;
● Suggest business insights to find and retain customers;
● Provide operational process suggestions to improve data quality;
● Provide updated and transparent data periodically to the marketing department. 

**MODELING**

In order to begin our modeling step based on CRISP-DM methodology, we performed the K-Means algorithm as a modeling technique, which is an algorithm that partitions a dataset into k clusters based on similarity between data points in order to predict the customer segmentations and provide this analysis to the marketing department work in the new strategy.
<img width="232" alt="Screen Shot 2023-07-14 at 18 12 13" src="https://github.com/AnaOttavi/Hospitality_Segmentation/assets/86486485/2dea0e43-f658-441f-9176-8171eb344857">

**RESULTS EVALUATION**
The assessment of the model was performed using the R2 score, which represents the proportion of variance in the cluster labels. The final R2 score for the K-Means clustering solution was 0.6413, indicating that the clustering solution explains about 64% of the variance in the data.


**Evaluation Clusters**

<img width="431" alt="Screen Shot 2023-07-14 at 18 07 56" src="https://github.com/AnaOttavi/Hospitality_Segmentation/assets/86486485/c5b14a61-385c-4ae4-8641-e96041d88d07">
<img width="436" alt="Screen Shot 2023-07-14 at 18 08 07" src="https://github.com/AnaOttavi/Hospitality_Segmentation/assets/86486485/e006d6b9-aaaf-4fc9-9142-43467bde2f63">

**Cluster 0: Younger people with more wealth:**
The main characteristic of this cluster is the age. These clients are young and have no troubles with the noise once they present the lowest value for SRQuietRoom. Usually they travel alone or in couples and don't book in advance, once the cluster presents the lowest value on AverageLeadTime. These customers are the most valuable once they spend more money per year and per booking than any other.
**Suggestions:**
● Through young social media influencers promote the hotel accommodation, services and experience to the younger people with acquisitive power worldwide and specifically on the French market as well.
● Create a specific and exclusive offer in terms of accommodation, service and experience to be promoted through the Travel agent/operator distribution channel worldwide, but focusing on the French market.
 
**Cluster 1: Portuguese Clients:**
The main characteristic of this cluster is to have a strong presence of Portuguese. Furthermore, these customers prefer to book directly with the hotel, without intermediaries, and are the most loyal ones to our hotels once they book frequently.
**Suggestions:**
● Create a media plan to the Portuguese market involving television and radios to promote the brand and increase notoriety.
● Recognize their frequent presence through some surprises and gentle offers during their stayings at the hotel.

**Cluster 2: Potencial and Mature Clients:**
The main characteristic of this cluster is the highest value of SRQuietRoom. So, these clients require a calm environment. The age of these customers is majorly between 51-60 and they present a high acquisitive power once they are the second highest value for revenue. They also make their reservations with time in advance.
**Suggestions:**
● Create a loyalty program with focused and tailored offers in order to promote loyalty and retain the customers;
● Design a tailored offer in terms of accommodation, service and experience in order to be promoted through the channels GDS Systems and Travel Agent/Operator.

**Cluster 3: Advanced Booking Customers:**
The main characteristic of this cluster is that the clients book with the larger antecedence compared with the other customers. German is the predominant nationality and Age_gap 60. Another characteristic is age, most likely they are retired customers. They may already have a financial reserve which contributes to early bookings.
**Suggestions:**
● Create a partnership with travel agencies in order to organize trips to aged customers with tailored experiences and activities;
● Design a campaign to aged customers promoting opportunities to travel with buddies.

**Cluster 4: Low cost travel:**
This cluster includes customers with ages between 31 and 40 from everywhere in the world, the ones with the lowest acquisition power.
**Suggestions:**
● Promote offers with discounts to middle age people in the less booked period of the year throughout the main distribution channels;
● Create a tailored offer for customers in middle age and sensible to prices.
