# Coffee-Sales-Dashboard
A dashboard to be used by stakeholders to analyse Coffee Sale. 

## Data Gathering: 
The raw data consisted of 3 worksheets; Orders, Customers and Products. To allow for later data aggregation, data was consolidated into one table using the XLOOKUP and INDEX MATCH functions to obtain the key datapoints relating to the customer respective product information for each purchase, such as: 

### - Customer Name
### - Customer Email
### - Customer's Country of purchase
### - Coffee Type 
### - Roast Type
### - Coffee Bag Size 
### - Loyalty Card 

## Data normalisation:
Data was then normalised to allow the data to be more readable/understandable, such as the size of coffee bag purchases being in Kilograms (kg) and applying abbreviation expansion to the Coffee Type and Roast Type using IF functions. 

## Data Aggregation and Visulisation:
Data was then aggregated to create a dashboard that facilitates the analysis of the following: 
## - Time series data with monthly granularity for total coffee sales
