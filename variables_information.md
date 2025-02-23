# Description of the variables used in the analysis

**work_year:** The year the salary was paid.

**experience_level:**   The experience level in the job during the year with the following possible values (value when variable transformed to experience_encoded):
  - **EN** Entry-level / Junior (0)
  - **MI** Mid-level / Intermediate (1)
  - **SE** Senior-level / Expert (2)
  - **EX** Executive-level / Director (3)
    
**employment_type:** The type of employement for the role:
  - **PT** Part-time
  - **FT** Full-time
  - **CT** Contract
  - **FL** Freelance
    
**job_title:** The role worked in during the year.

**salary:** The total gross salary amount paid.

**salary_currency:** The currency of the salary paid as an ISO 4217 currency code.

**salary_in_usd:** The salary in USD (FX rate divided by avg. USD rate of respective year) via statistical data from the BIS and central banks.

**employee_residence:** Employee's primary country of residence in during the work year as an ISO 3166 country code.

**remote_ratio:** The overall amount of work done remotely, possible values are as follows:
  - **0** No remote work (less than 20%)
  - **50** Partially remote/hybird
  - **100** Fully remote (more than 80%)

**company_location:** The country of the employer's main office or contracting branch as an ISO 3166 country code.

**company_size:** The average number of people that worked for the company during the year (value when variable transformed to company_size_encoded):
  - **S** less than 50 employees (small) (0)
  - **M** 50 to 250 employees (medium) (1)
  - **L** more than 250 employees (large) (2)
