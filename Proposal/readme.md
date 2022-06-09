## Title: 

This circumstance involves legal violations and the aspects associated with citations in court from various places for various persons.
![image](https://user-images.githubusercontent.com/106714178/172522403-3cee930b-ff80-49b5-a09f-754aae722fa3.png)

 
**Background information:**

As the advancements and improvements in the technological sector, the world is witnessing the never seen progress. So, the environment is also playing a crucial role in impacting the lives of human. So, I believe it's essential to focus on the current environmental citations on various organizations and understand the trend for minimizing the impact of environment on the quality of the individuals.
##Severity of the issue##:
When there is a violation of the law, the authorities usually settle it by filing charges. Occasionally, persons are accused without having committed any violations, or they reject the charges for an acceptable reason.
![image](https://user-images.githubusercontent.com/106714178/172522488-d8bb45b4-8bdd-4ec2-8eae-0266a222d4f0.png)

 
**Existing problems with environmental violations and citations:**

Environmental restrictions, on the other hand, typically need a large rise in corporate expense. Some firms will refuse to meet the requirements in order to avoid incurring more fees. Businesses will sometimes publicly refuse to comply, preferring to pay governmental penalties rather than the compliance expenses, which sometimes outweigh the fines' overall costs. Other companies, on the other hand, will try and hide their noncompliance by dumping hazardous waste into rivers, streams, seas, or other remote locations rather of paying to have it transported to a chemical treatment plant. Littering, incorrect waste disposal, agricultural use of unlawful pesticides. manipulating lab data relevant to environmental standards; bringing illicit chemicals into the nation; and environmental fraud.
##Goals of the project##:
So, for a citation, we're going to see if a hearing status has been issued or not, which means we're attempting to figure out how citation features influence those who have a hearing status and people who don't. 
![image](https://user-images.githubusercontent.com/106714178/172522328-9a892a13-e357-49d2-ab64-609432cfb358.png)

 
This allows us to have a better understanding of people's present mindsets and mistakes, as well as providing an analysis for jurisdiction to facilitate the flow of their work.

**Dataset description:**

[CitationNo]: citation number of a given case		
 <br /> [LienCode]:		gives lien code for the case
 <br /> [ViolationDate]: date on which the violation took place		
 <br /> [DueDate]: due date on which the amount is to be paid		
 <br /> [Agency]: department in which the violation took place.		
 <br /> [FineAmount]: fine amount to be paid		
 <br /> [Description]: description of the violation		
 <br /> [Balance]:balance amount to be paid		
 <br /> [LastPaidDate]: last date of fine paid for violation.		
 <br /> [LastPaidAmount]: the last paid fine amount		
 <br /> [HearingDate]: date on which court hears the case.		
 <br /> [HearingRequestReceivedDate]: date on which hearing request is received		
 <br /> [CitationStatus]: shows the status of the citation		
 <br /> [ViolationCodeArticle]: code article		
 <br /> [ViolationCodeSection]: code section		
 <br /> [ViolationLocation]:violation location			
 <br /> [OfficerID]: the id of the officer		
 <br /> [OfficerPresenceRequested]: if the presence of the officer is required.		
 <br /> [HearingStatus]: status of the hearing.		
 <br /> [HearTime]: hearing time		
 <br /> [TotalPaid]: total amount paid for violations		
 <br /> [TotalAbated]: total amount being abated		
 <br /> [TotalVoided]: total amount being voided		
 <br /> [Neighborhood]: neighborhood area		
 <br /> [PoliceDistrict]: police district of the violation		
 <br /> [CouncilDistrict]: council district of the violation		
 <br /> [Location]:location in which the violation took place.
 Name	Type	Action
CitationNo
Text
LienCode
Text
ViolationDate
Date or Time
DueDate
Date or Time
Agency
Text
FineAmount
Number
Description
Text
Balance
Number
LastPaidDate
Date or Time
LastPaidAmount
Number
HearingDate
Date or Time
HearingRequestReceivedDate
Date or Time
CitationStatus
Text
ViolationCodeArticle
Text
ViolationCodeSection
Text
ViolationLocation
Text
Block
Text
Lot
Text
OfficerID
Text
OfficerPresenceRequested
Text
HearingStatus
Text
HearTime
Text
TotalPaid
Number
TotalAbated
Number
TotalVoided
Number
Neighborhood
Text
PoliceDistrict
Text
CouncilDistrict
Text
Location
Text

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
