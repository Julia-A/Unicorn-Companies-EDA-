# Unicorn-Companies....An EDA
An exploratory descriptive analysis on unicorn companies 

# Objective
- To know the top ranking billion dollar companies.
- To know the average number of years it takes to become a Unicorn.
- To find out the trending industry hub.
- The year in which many companies reached the billion dollar mark.

# Data Sourcing
I merged 2 datasets. I extracted the first dataset from the web using excel "from web" feature. The website is https://www.cbinsights.com/research-unicorn-companies. I got the second dataset from kaggle.

# Transformation (steps I took to clean the dataset)
- I checked for duplicate and blank rows.
- There were certain rows in the kaggle dataset where the values of the investor column is 'None'. The 'city', 'industry', and 'investors' values are shifted for such rows. I filtered the none values and fixed them manually.
- Removed the dollar signs and other special chracters and converted to currency in dollars. 
- Used excel's IF, ISTEXT, XLLOOKUP, RIGHT & LEFT functions to remove the special characters.
- A lot of blanks were present in financial stage column so I dropped the column.
- I manually inputed the founding year rows that wee blank since the blanks weren't up to 30.
