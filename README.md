# *Capstone Data Science 690 (Draft Proposal)*

*Proposal By :*

  Sharath Srinivas
  
  Chetan B Desai 
  
  Saideep Malgireddy
  
# COVID-19 patient details Vaccine and side effects Analysis
 
### What is your issue of interest (provide sufficient background information)?
VAERS: Vaccine Adverse Event Reporting System
This method is used to gather information about the type of vaccine administered, the duration of vaccination, the onset of the adverse condition, current diseases or medications, prior history of adverse effects, and demographic information if an individual has an adverse reaction to a vaccine. Any health complications after a vaccine are administered expected by statute to be reported to VAERS by all healthcare providers.

### Why is this issue important to you and/or to others?
Anyone who has received a vaccine and had an adverse reaction should file a VAERS report online, even though they are unsure that the vaccine is to blame. So we don't know the overall number of vaccinated people. Over 259 million doses of COVID-19 vaccines were administered in the United States from December 14, 2020, through May 10, 2021. During this time, VAERS received 4,434 reports of death (0.0017%) among people who received a COVID-19 vaccine [1]
It is important to analysis the data during this pandemic and be aware of the information regarding the vaccination 


### What questions do you have in mind and would like to answer?
1. This study exhibits people’s predilection toward the COVID-19 vaccine and its results based on the reviews.
2. Predicting the mortality of the patient based on the covid vaccination symptoms.
3. Predicting reeffecting rate of the covid-19 in the patients who have vaccinated with different manufacturers

### Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?

Data Source: https://vaers.hhs.gov/data/datasets.html
Data Guide: https://vaers.hhs.gov/docs/VAERSDataUseGuide_November2020.pdf

The VAERS data can be accessed by downloading raw data in comma-separated value (CSV) files. The public will not be able to access information supplied to VAERS that identifies a person who received the vaccine or vaccines. VAERS data that has been de-identified is available 4-6 weeks after the report is received. Because VAERS data changes when new reports are received, our results may differ if we run the same search again at a later time.

### What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
Random forest (RF), a support vector machine (SVM), decision tree (DT), K-nearest neighbor (KNN), and an artificial neural network (ANN), will be used for forecasting the overall predilection toward the COVID-19 vaccine. Natural Processing Language (NLP) will be used to extract symtoms and other data from the text.

### How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
A voting classifier and Bossting will be used to determine the accuracy of all the classifiers.

### What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?
COVID-19 has rapidly spread around the world. In this pandemic, the COVID-19 immunization can be regarded as a safe haven for saving a human life and avoiding COVID-19 deaths and illnesses. Since the introduction of the COVID-19 immunization, various studies have been conducted. Different strategies, with different approaches, may be useful for future prediction of the consequences of this immunization. The purpose of this study is to forecast people's attitudes on COVID-19 vaccinations, as well as other myths and side effects of vaccination on health.

# References
[1] https://www.cdc.gov/coronavirus/2019-ncov/vaccines/safety/adverse-events.html
