## Dataset Description

This dataset contains information about direct marketing campaigns (phone calls) conducted by a Portuguese banking institution to promote term deposits among its customers. The campaigns were carried out between May 2008 and November 2010. The dataset aims to analyze customer behavior and preferences to improve future marketing strategies.

### Content

The dataset includes the following information:

- **Customer Information**: Demographic and socio-economic attributes of the customers contacted.
  
- **Campaign Details**: Information about the calls made during the campaigns, including the number of contacts made to each customer, the timing of the calls, and the outcome of each call.
  
- **Response Variables**: Binary indicators showing whether the customer subscribed to a term deposit following the campaign.

### Domain: 

Finance/Banking

### Data Summary

| **Attribute**  | **Description**                                                                 | **Data Type** |
|----------------|---------------------------------------------------------------------------------|---------------|
| Age            | Age of the customer                                                             | Numeric       |
| Job            | Type of job                                                                     | Categorical   |
| Marital        | Marital status                                                                  | Categorical   |
| Education      | Level of education                                                              | Categorical   |
| Default        | Has credit in default?                                                          | Binary        |
| Housing        | Has housing loan?                                                               | Binary        |
| Loan           | Has personal loan?                                                              | Binary        |
| Contact        | Contact communication type                                                      | Categorical   |
| Month          | Last contact month of the year                                                  | Categorical   |
| Day_of_week    | Last contact day of the week                                                    | Categorical   |
| Duration       | Last contact duration in seconds                                                | Numeric       |
| Campaign       | Number of contacts performed during this campaign for this client               | Numeric       |
| Pdays          | Number of days passed after the client was last contacted from a previous campaign| Numeric    |
| Previous       | Number of contacts performed before this campaign for this client               | Numeric       |
| Poutcome       | Outcome of the previous marketing campaign                                      | Categorical   |
| Y (target)     | Has the client subscribed to a term deposit?                                    | Binary        |

### Source

The dataset is sourced from the UCI Machine Learning Repository:
[Bank Marketing Data Set](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1000-ProtugeseBank.zip)

### Citation

If you use this dataset in your research or analysis, please cite it as:

Moro, S., Cortez, P., & Rita, P. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, 62, 22-31.

### Acknowledgments

We acknowledge the original contributors of the dataset from the UCI Machine Learning Repository and the authors of the associated research paper for making this valuable data available for analysis and research purposes.