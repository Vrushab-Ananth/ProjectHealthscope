# Project Healthscope

## DATA:

Ambulance Victoria LGA Response Time Performance. 
Originally extracted from https://discover.data.vic.gov.au/dataset/ambulance-victoria-lga-response-time-performance and stored here as "AmbulanceData".

Columns:
  1. LGA Name                : Names of Victorian Local Government Areas.
  2. C1 Final Dispatch Code  : Dispatch code "Code 1".
  4. %<=15mins               : Percentage of C1 responses that took less than 15 minutes.
  5. C1 AVG RT - Seconds     : Average Response Times for Code 1 type emergency calls in LGAs across Victoria.
  6. C1 Total Number         : Number of Code 1 type emergency calls that were attended to.
  7. C2 Final Dispatch Code  : Dispatch code "Code 2".
  8. C2 AVG RT - Seconds     : Average Response Times for Code 2 type emergency valls in LGAs across Victoria.
  9. C2 Total Number         : Number of Code 2 type emergency calls that were attended to.

Rows:
  There are 79 rows of data. A row of data for each LGA.

## POWER BI REPORT:   "Healthscope.pbix"

### HOME PAGE:
  
  1. Explains what code 1 and coe 2 types of calls are.
  2. Displays averages across Victoria.
  3. Displays a map which can be explored.

### CODE 1 Page:

  1. Displays a map with LGAs that have Healthscope hospitals. This map can be explored for Code 1 related data.
  2. Displays a barchart comparing different averages related to Code 1.
  3. Displays a 100% column chart that visualises the correlation between the response time and the number of calls, with the correlation  coefficient displayed on one side.

### CODE 2 Page:

  1. Displays a map with LGAs that have Healthscope hospitals. This map can be explored for Code 2 related data.
  2. Displays a barchart comparing different averages related to Code 2.
  3. Displays a 100% column chart that visualises the correlation between the response time and the number of calls, with the correlation  coefficient displayed on one side.

### Summary Page:

  1. An observation is stated.
  2. A business opportunity is explored.






