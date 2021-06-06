# amazon-ml-challange


## Problem

Companies are expected to be equal opportunity employers. Their recruitment and selection process is expected to provide equal opportunity irrespective of gender identity or expression, religion, color, sex, age, physical or mental disability, sexual orientation, or any other basis covered by local law. Removal of bias and providing equal opportunity to all applicants promotes access to the widest pool of talent.

XyX corporation recruits employees for fixed Job Codes every year. Basis the applications received last year for each job code profile, a ‘fitment %’ percentage was determined based on selections made. XyX followed a fair and equitable approach by personally looking at all parameters and determining the right fit. This year the number of applicants has multiplied and they are looking at an ML model to predict the ‘fitment %’ for the applications received maintaining a fair and equitable approach.

Task
Build a model that calculates the ‘fitment %’ & detects the factor that influences relevancy and making sure that factor does not introduce inequality and/or bias in the’ fitment %’ by appropriate feature re-engineering.

Submit a presentation explaining how your model’s predictions will be used by business leaders to analyse and enable an equal-opportunity and bias-free recruitment process.

Data Set

Train.csv: 13645 x 22

Test.csv: 8745 x 20

Submission.csv: 8745 x 3

Columns	Description

Candidate ID	ID of candidate

Gender	Gender of candidate

JobProfileIDApplyingFor	External job posting under consideration

HighestDegree	Highest educational degree received

DegreeBranch	Branch/Specialization of the degree

LatestDegreeCGPA	CGPA obtained for the latest degree

YearsOfExperience	Number of years of relevant industry experience

GraduationYear	Year of graduation

Graduating Institute	Tier of Institution

Language of Communication	Preferred language of communication

Age	Age of employee

CurrentCTC	Compensation received by current employer

ExpectedCTC	Expected compensation

MartialStatus	Marital status of candidate

EmpScore	Score / Rating given by recommenders to the employee (out of 5)

CurrentDesignation	Current designation of candidate


Fitment %	% fitment of a candidate to the job profile ID basis their background and other factors [Target]

Bias influential factor	Factor / Feature that introduces the most bias on the fitment %

Instructions 

Download the dataset using 'Download Dataset' button

Solve the problem in your local environment using train.csv to train your model and test.csv to apply the model and generate predictions

Save the predictions in a .csv file matching the format shared in 'sample submission.csv' file

Upload the predictions .csv file under 'Upload File'

Click on 'Submit & Evaluate' to assess your model's performance

Upload the .ipynb file or notebook file along with the presentation file under 'Upload Source code'
