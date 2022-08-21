# Data_606_TEAM_D
## UMBC DATA606 Data Science Capstone Project ##

## SMART FARMING - O My Natural ##

![image](https://user-images.githubusercontent.com/78180757/173258582-eb2cce29-6e5e-4c9f-9ce6-e7a4016a17c6.png)


# “We turn fertile lands into deserts by using ineffective farming technologies. There is no future until we return to effective farming and save the soil.” 

Under the guidance: Prof. Wang, Chaojie

Presented By :

Samyuktha Guda

Nikitha Alla

Samyuktha Jalagam


## Team: Roles and Responsibilities ##

In this project, we will be presenting a website in which the following applications would be implemented; Crop recommendation, Fertilizer recommendation, and Plant disease prediction, respectively.

### Samyuktha Guda ###

**Crop recommendation application** - Data cleaning, Visualization, Decision tree, Naive Bayes, SVM, Logistic regression, XG-boost

### Samyuktha Jalagam ###

**Fertilizer recommendation application** – Data Visualization using Matplotlib, Decision tree, Naive Bayes, SVM, Logistic regression, XG-boost

### Nikhitha Alla ###

**Plant disease prediction application** - Image pre-processing, ResNet 50 classification, Feature extraction

### ABSTRACT ###

Agriculture is an integral part of India's socioeconomic fabric. Farmers' failure to choose the best crop for the land using non-scientific and traditional methods is a severe problem in a country where farming employs approximately 58 percent of the population. Farmers have occasionally failed to select suitable crops based on the condition of the soil, sowing season, and geographic location. As a result, people commit suicide, leave agriculture, and seek employment in cities. To address the problem mentioned above, this study proposed a system to assist farmers in crop selection by considering all the factors such as sowing season, soil condition, and geographic location. Precision agriculture is also being implemented with modern agricultural technology and is evolving. This paper uses machine learning approaches like Random Forest and Decision Tree to predict which crop is best for which soil type based on the data sets. According to previous studies, 42 percent of agricultural production is lost, and this is due solely to the rising rate of plant leaf disease losses. This plant leaf disease detection technique can be used to detect a disease from the input images to solve this significant problem. Image pre-processing, image segmentation, and feature extraction were all part of this process. On the results of these three stages, the ResNet 50 classification is applied. Plant leaf diseases were predicted with 98.56 percent accuracy using the proposed implementation.

### INTRODUCTION ###

Farming is one of the major sectors that influences a country’s economic growth. In a country like India, the majority of the population is dependent on agriculture for their livelihood. Agriculture is becoming more prominent as new technologies emerge, as it is used not only to feed a large population but also in various applications. Plants are significant in our lives because they provide energy and help to combat global warming. Many diseases affect plants today, causing devastating economic, social, and ecological losses, among other things. As a result of it, it is critical to identify plant diseases accurately and quickly. 
Furthermore, 48% of farmers do not want their children to be involved in agriculture and instead prefer to live in cities. This is because farmers frequently make poor crop selection decisions, such as choosing a crop that will not yield much for the soil, planting in the wrong season, etc. The farmer may have purchased the land from others, so the decision was made without prior experience. A reduced yield will always come from poor crop selection. It is challenging to survive if the family relies entirely on this income. To address all these issues, with the resources at our disposal, we would like to present a system to solve by providing predictive insight and guidance on crop sustainability based on machine learning models trained using critical environmental and economic parameters.
The used method employs digital image processing tools to achieve the desired result. Because the symptoms are subjective, the human eye cannot accurately determine the extent of the disease. Observations made with the naked eye are commonly used to assess the severity of conditions in the production area. In the field of agriculture, image processing has made a significant contribution. Several neural network techniques, such as Back Propagation and Principal Component Analysis, were used to identify the fungi disease(PCA). To improve the required rate in the classification technique to detect plant leaf disease. Until now, linear SVM, a multi-class classification that only classifies data into two classes, has been used. The fundamental goal of this
project was to investigate and analyze different techniques for detecting plant leaf disease using image processing techniques and propose improvements in existing classification techniques for plant leaf disease detection using machine learning. Furthermore, 48% of farmers do not want their children
to be involved in agriculture and instead prefer to live in cities. This is because farmers frequently make poor crop selection decisions, such as choosing a crop that will not yield much for the soil, planting in the wrong season, etc. The farmer may have purchased the land from others, so the
decision was made without prior experience. A reduced yield will always come from poor crop selection. It is challenging to survive if the family relies entirely on this income.Potential researchers are discouraged from working on developing country case studies due to a lack of accurate and current information. With the resources at our disposal, a system has been presented to solve by providing predictive insight and guidance on crop sustainability based on machine learning models trained using critical environmental and economic parameters. To recommend a suitable crop to the user, the proposed
system considers environmental factors such as rainfall, temperature, and geographical location in terms of the stateand soil characteristics such as soil type, pH value, and nutrient concentration. Moreover, if the farmer chooses the right crop, they will receive a yield prediction

### What questions do you have in mind and would like to answer? ###

How to safeguard the soil from losing its fertility owing to poor farming techniques?

How to treat crop disease organically rather than using heavy fertilizers?

How to Cultivate the right crop in the right soil to reduce the risk of soil property degradation?

### Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.) ###

Here, we will be considering datasets for exploring and analyzing the suitable crop data from various trustworthy sources, including data.gov.in and kaggle.com. 
The data sets are for the states of Maharashtra and Karnataka. State, district, year, season, type of crop, the area under cultivation, production, and so on are all included in the data. Other datasets with state and district specifications include the soil type as an attribute. This soil type column is extracted from the primary data set and merged. 

Data:
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into an 80/20 ratio of training and validation sets preserving the directory structure. A new directory containing 33 test images is created later for prediction purposes.

### What will be your unit of analysis (for example, patient, organization, or country)? ###

In this project, we are going to analyze the crop that is suitable for a particular location based on input details. The unit of analysis here is the yield of a particular country and my unit of observation is crop selection. And my unit of observation for the second part would be fertilizer selection.

### What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)? ###

We will be using state, district, crop, area, and temperature in our analysis.

### What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)? ###

In this project, we are planning to use machine learning approaches like Random Forest and Decision Tree to predict the crop based on soil type. We are also planning to use neural network techniques, such as Back Propagation and Principal Component Analysis, to identify the fungi disease (PCA). Before cultivation, the crops will be ranked using Decision Tree Learning. An Artificial Neural Network will be implemented to predict crop disease and recommend measures to treat the crop organically. The random forest algorithm would be implemented to analyze crop features. Finally, we are planning on deploying our project in an AWS EC2 instance. We are also using image processing techniques.
 ![image](https://user-images.githubusercontent.com/78180757/173258426-c6f6f81c-f06e-4b0a-8832-1b1046492440.png)


### How do you plan to develop/apply ML and how do you evaluate/compare the performance of the models? ###

In our project we are using the following ML algorithms:
* Decision Tree
* Naive Bayes
* Logistic Regression
* Random Forest 
* XG Boost
 
### What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practical applications, etc)? ###

The fundamental goal of this project is to investigate and analyze different techniques for detecting plant leaf disease using image processing techniques and propose improvements in existing classification techniques for plant leaf disease detection using machine learning. The proposed system assists farmers in selecting the appropriate crop by delivering information that regular farmers are unaware of, reducing crop failure and improving output. It also helps them avoid losing money.
Despite the many solutions that have recently been suggested, there are still open challenges in developing a user-friendly crop recommendation application. The proposed solution aims to address these limitations by creating a user-friendly application that considers rainfall, temperature, soil type, and other factors that directly affect cultivation. The main goal is to increase the number of crops grown throughout the season.

### References: ###
[1]. https://www.cdc.gov/coronavirus/2019-ncov/vaccines/safety/adverse-events.html

[2]. https://pubmed.ncbi.nlm.nih.gov/15071280/

[3].https://www.cdc.gov

[4].https://www.ema.europa.eu/documents/other/meddra-important-medical-event-terms-list-version-250_en.xlsx

[5].https://plotly.com/python/

[6].https://www.historyofvaccines.org/content/articles/vaccine-side-effects-and-adverse-events

[7].https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6518966/

[8].https://www.medscape.com/viewarticle/950781?reg=1

### YOUTUBE LINK ###

###PPT LINK###

Data_606_Final_presentation.pdf
