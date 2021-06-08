# Federal Election Commission Data Warehouse Design
## Dataset Description
Data souce from Campaign finance data where we can see how candidates and committees raise and spend money in federal elections. This financial data helps voters make informed decisions. Only the following data were used.
- all candidate (https://www.fec.gov/campaign-finance-data/all-candidates-file-description/)
- Candidate Master (https://www.fec.gov/campaign-finance-data/candidate-master-file-description/)
- committee master (https://www.fec.gov/campaign-finance-data/committee-master-file-description/)
- Candidate-committee linkage (https://www.fec.gov/campaign-finance-data/candidate-committee-linkage-file-description/)
- contribution by individual (https://www.fec.gov/campaign-finance-data/contributions-individuals-file-description/)

## Problem of Interest
The problem only related to Candidate and Contribute tables.
- Which 5 states have the most candidates' offices in 2016 and 2020? 
- Contribution by individual and committee breakdown by States in 2016 and 2020.
- Contribution comparison by Trump, Biden and Clinton in 2016 and 2020.
- Individual contribution for both parties based on occupation.

## Methodology
1. All coding works implement on AWS EC2 and S3 bucket.
2. Design Dimension and fact schema.
3. Create table and insert data using Spark SQL.
