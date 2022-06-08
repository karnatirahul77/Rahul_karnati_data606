## Title: 

This circumstance involves legal violations and the aspects associated with citations in court from various places for various persons.
 
**Background information:**

As the advancements and improvements in the technological sector, the world is witnessing the never seen progress. So, the environment is also playing a crucial role in impacting the lives of human. So, I believe it's essential to focus on the current environmental citations on various organizations and understand the trend for minimizing the impact of environment on the quality of the individuals.
Severity of the issue: When there is a violation of the law, the authorities usually settle it by filing charges. Occasionally, persons are accused without having committed any violations, or they reject the charges for an acceptable reason.
 
**Existing problems with environmental violations and citations:**

Environmental restrictions, on the other hand, typically need a large rise in corporate expense. Some firms will refuse to meet the requirements in order to avoid incurring more fees. Businesses will sometimes publicly refuse to comply, preferring to pay governmental penalties rather than the compliance expenses, which sometimes outweigh the fines' overall costs. Other companies, on the other hand, will try and hide their noncompliance by dumping hazardous waste into rivers, streams, seas, or other remote locations rather of paying to have it transported to a chemical treatment plant. Littering, incorrect waste disposal, agricultural use of unlawful pesticides. manipulating lab data relevant to environmental standards; bringing illicit chemicals into the nation; and environmental fraud.
Goals of the project: So, for a citation, we're going to see if a hearing status has been issued or not, which means we're attempting to figure out how citation features influence those who have a hearing status and people who don't. 
 
This allows us to have a better understanding of people's present mindsets and mistakes, as well as providing an analysis for jurisdiction to facilitate the flow of their work.

**Dataset description:**

CitationNo: citation number of a given case		
LienCode:		
ViolationDate: date on which the violation took place		
DueDate: due date on which the amount is to be paid		
Agency: department in which the violation took place.		
FineAmount: fine amount to be paid		
Description: description of the violation		
Balance:balance amount to be paid		
LastPaidDate: last date of fine paid for violation.		
LastPaidAmount: the last paid fine amount		
HearingDate: date on which court hears the case.		
HearingRequestReceivedDate: date on which hearing request is received		
CitationStatus: shows the status of the citation		
ViolationCodeArticle: code article		
ViolationCodeSection: code section		
ViolationLocation:violation location			
OfficerID: the id of the officer		
OfficerPresenceRequested: if the presence of the officer is required.		
HearingStatus: status of the hearing.		
HearTime: hearing time		
TotalPaid: total amount paid for violations		
TotalAbated: total amount being abated		
TotalVoided: total amount being voided		
Neighborhood: neighborhood area		
PoliceDistrict: police district of the violation		
CouncilDistrict: council district of the violation		
Location:location in which the violation took place.

**Data source:**

https://data.baltimorecity.gov/datasets/environmental-citations/explore.
Unit of analysis: Hearing status
Number of observations to be Analysed: 204161
Output variable: lien code

**Models which are to be used:**

Decision tree classifier
Random forest classifier
Support vector machine
Grid search random forest
Logistic regression

**Evaluation metrics to be used:**

I am planning to evaluate the metrics such as Accuracy Score, Precision Score, Recall,f1-Score,Confusion Matrix, ROC curve after figuring out the metric to evaluate the model with the help understanding the domain of data, later I will determine ways to improve the performance of the model.

**Expected results:**

1. I will determine which metric best helped me to know the model better.
2. I am going to determine performance of the model.
3. Application of various machine learning models to classify the outcomes.
4. To use grid search validations.
5. Analyzing and visualizing the data.
6. To learn how to handle outliers.
7. To learn data partitioning and data-preprocessing.
8. To learn the importance of statical analysis and understand various functions.
