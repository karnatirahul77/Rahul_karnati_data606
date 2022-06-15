## Title: 

This circumstance involves legal violations and the aspects associated with citations in court from various places for various persons.
![image](https://user-images.githubusercontent.com/106714178/172522403-3cee930b-ff80-49b5-a09f-754aae722fa3.png)

 
**Background information:**

As the advancements and improvements in the technological sector, the world is witnessing the never seen progress. So, the environment is also playing a crucial role in impacting the lives of human. So, I believe it's essential to focus on the current environmental citations on various organizations and understand the trend for minimizing the impact of environment on the quality of the individuals.

**Severity of the issue**:
When there is a violation of the law, the authorities usually settle it by filing charges. Occasionally, persons are accused without having committed any violations, or they reject the charges for an acceptable reason.
![image](https://user-images.githubusercontent.com/106714178/172522488-d8bb45b4-8bdd-4ec2-8eae-0266a222d4f0.png)

 
**Existing problems with environmental violations and citations:**

Environmental restrictions, on the other hand, typically need a large rise in corporate expense. Some firms will refuse to meet the requirements in order to avoid incurring more fees. Businesses will sometimes publicly refuse to comply, preferring to pay governmental penalties rather than the compliance expenses, which sometimes outweigh the fines' overall costs. Other companies, on the other hand, will try and hide their noncompliance by dumping hazardous waste into rivers, streams, seas, or other remote locations rather of paying to have it transported to a chemical treatment plant. Littering, incorrect waste disposal, agricultural use of unlawful pesticides. manipulating lab data relevant to environmental standards; bringing illicit chemicals into the nation; and environmental fraud.


**Goals of the project**:
So, for a citation, i going to see if a hearing status has been issued or not, which means i attempting to figure out how citation features influence those who have a hearing status and people who don't. 
![image](https://user-images.githubusercontent.com/106714178/172522328-9a892a13-e357-49d2-ab64-609432cfb358.png)

 
This allows us to have a better understanding of people's present mindsets and mistakes, as well as providing an analysis for jurisdiction to facilitate the flow of their work.

**Dataset description:**
                                                                                    
1) **CitationNo**: citation number of a given case, Data Type: Text

2)**LienCode**:		gives lien code for the case, Data type: numerical

3)**ViolationDate**: date on which the violation took place, Data type:numerical

4)**DueDate**: due date on which the amount is to be paid, Data type:numerical

5)**Agency**: department in which the violation took place, Data type:categorical (health,police,public)

6)**FineAmount**: fine amount to be paid, Data type: numerical

7)**Description**: description of the violation, Data type: text

8)**Balance**:balance amount to be paid		  , Data type: numerical

9)**LastPaidDate**: last date of fine paid for violation.	, Data type:numerical

10)**LastPaidAmount**: the last paid fine amount		 , Data type:  numerical 

11)**HearingDate**: date on which court hears the case.	, Data type:numerical

12)**HearingRequestReceivedDate**: date on which hearing request is received	 , Data type:numerical

13)**CitationStatus**: shows the status of the citation		, Data type:  text

14)**ViolationCodeArticle**: code article		  , Data type:  text

15)**ViolationCodeSection**: code section		, Data type:  text

16)**ViolationLocation**:violation location	, Data type:   text

17)**OfficerID**: the id of the officer		 , Data type:   text

18)**OfficerPresenceRequested**: if the presence of the officer is required.	, Data type:   text

19)**HearingStatus**: status of the hearing.		, Data type:  text

20)**HearTime**: hearing time		        , Data type:  text

21)**TotalPaid**: total amount paid for violations  , Data type:numerical

22)**TotalAbated**: total amount being abated	,Data type:  numerical

23)**TotalVoided**: total amount being voided, Data type:numerical

24)**Neighborhood**: neighborhood area, Data type: text

25)**PoliceDistrict**: police district of the violation, Data type:categorical (east,west,north,south)

26)**CouncilDistrict**: council district of the violation, Data type:numerical

27)**Location**:location in which the violation took place, Data type: text


**Data source:**

https://data.baltimorecity.gov/datasets/environmental-citations/explore.
Unit of analysis: Hearing status
<br/>Number of observations to be Analysed: 204161
<br/>Output variable: lien code



**Models which are to be used:**

1)Decision tree classifier
<br/>2)Random forest classifier
<br/>3)Support vector machine
<br/>4)Grid search random forest
<br/>5)Logistic regression

**Evaluation metrics to be used:**

I am planning to evaluate the metrics such as<br/> Accuracy Score, <br/>Precision Score, <br/>Recall,<br/>f1-Score,<br/>Confusion Matrix,<br/> ROC curve after figuring out the metric to evaluate the model with the help understanding the domain of data, later I will determine ways to improve the performance of the model.

**Expected results:**

1. I will determine which metric best helped me to know the model better.
2. I am going to determine performance of the model.
3. Application of various machine learning models to classify the outcomes.
4. To use grid search validations.
5. Analyzing and visualizing the data.
6. To learn how to handle outliers.
7. To learn data partitioning and data-preprocessing.
8. To learn the importance of statical analysis and understand various functions.
