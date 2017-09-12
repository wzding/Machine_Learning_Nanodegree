# Machine Learning Engineer Nanodegree
## Capstone Proposal  
Wenzhe(Emma) Ding

September 12th, 2017

## Proposal
_(approx. 2-3 pages)_

### Domain Background
_(approx. 1-2 paragraphs)_

There are currently over 13,000 licensed taxicabs and over 50,000 taxicab drivers providing transportation for passengers in New York City via street hails. The New York City Taxi & Limousine Commission (TLC) has released data with detailed information of each taxi trip from January 2009 through December 2016. To understand taxi trip patterns and answer questions such as what is the rush hour of NYC taxi trips, how are daily commute trips affect the volumn of taxi trip, what features are relevant to predict taxi trip duration, etc. we need to investigate such data sets. In fact, many data scientists as well as researchers have donen analyzsis using such public taxi data, some are listed below.
* http://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/.
* https://www.kaggle.com/headsortails/nyc-taxi-eda-update-the-fast-the-curious
* https://www.kaggle.com/gaborfodor/from-eda-to-the-top-lb-0-367

Additionally, being a transportation engineering major, I am especially interested in investigating publich trasportation data to study people's travel behavior. 

### Problem Statement
_(approx. 1 paragraph)_
The New York City Taxi & Limousine Commission hosts a kaggle competition (https://www.kaggle.com/c/nyc-taxi-trip-duration) to challenge data scientists to build a model that predicts the total ride duration of taxi trips in New York City, which also serves as the goal of this project. Available features include pickup time, geo-coordinates, number of passengers, and several others. The evaluation metric for this project is Root Mean Squared Logarithmic Error. In addition, we will conduct comprehensive Exploratory Data Analysis before building model for prediction as the insights may be valuable for the community. 

### Datasets and Inputs
_(approx. 2-3 paragraphs)_
Both the train data and test data are provided by the competition, which is under the folder "data" and title as "train.csv" and "test.csv" respectively. The training set contains 1458644 trip records and the testing set contains 625134 trip records. Detailed explanation of data fields are shown below, which is also available at the "Data" section of the competition (https://www.kaggle.com/c/nyc-taxi-trip-duration/data). 

id - a unique identifier for each trip
vendor_id - a code indicating the provider associated with the trip record
pickup_datetime - date and time when the meter was engaged
dropoff_datetime - date and time when the meter was disengaged
passenger_count - the number of passengers in the vehicle (driver entered value)
pickup_longitude - the longitude where the meter was engaged
pickup_latitude - the latitude where the meter was engaged
dropoff_longitude - the longitude where the meter was disengaged
dropoff_latitude - the latitude where the meter was disengaged
store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
trip_duration - duration of the trip in seconds

### Solution Statement
_(approx. 1 paragraph)_

In this section, clearly describe a solution to the problem. The solution should be applicable to the project domain and appropriate for the dataset(s) or input(s) given. Additionally, describe the solution thoroughly such that it is clear that the solution is quantifiable (the solution can be expressed in mathematical or logical terms) , measurable (the solution can be measured by some metric and clearly observed), and replicable (the solution can be reproduced and occurs more than once).

### Benchmark Model
_(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
