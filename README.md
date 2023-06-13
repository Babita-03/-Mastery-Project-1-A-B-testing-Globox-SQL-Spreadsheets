# A-B-testing-Globox-
- An A/B test is an experimentation technique used by businesses to compare two versions of a webpage, advertisement, or product feature to determine which one performs better

- By randomly assigning customers or users to either the A or B version, the business can determine which version is more effective at achieving a particular goal.

### GloBox is primarily known amongst its customer base for boutique fashion items and high-end decor products. However, their food and drink offerings have grown tremendously in the last few months, and the company wants to bring awareness to this product category to increase revenue.The Growth team decides to run an A/B test that highlights key products in the food and drink category as a banner at the top of the website.

You can find a description of each table and its columns below:

**users: user demographic information**

- id: the user ID
- country: ISO 3166 alpha-3 country code
- gender: the user's gender (M = male, F = female, O = other)

**groups:user A/B test group assignment**
- uid: the user ID
- group: the user’s test group
- join_dt: the date the user joined the test (visited the page)
- device: the device the user visited the page on (I = iOS, A = android)

**activity:user purchase activity, containing 1 row per day that a user made a purchase**
- uid: the user ID
- dt: date of purchase activity
- device: the device type the user purchased on (I = iOS, A = android)
- spent: the purchase amount in USD

### Project Logistics
The project features three parts:

1.Review inferential statistics and create  analysis plan

2.Analyze the A/B test results to determine whether or not the experiment was successful

3.Record a presentation of the A/B test results and create a written report

