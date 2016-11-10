# About GIVEasia
GIVEasia is a crowdfunding platform for people to raise money online. It offers services similar to [GoFundMe](https://www.gofundme.com/). Instead of charging transaction fees, it relies on optional "tips" from users to cover operational expenses. For example, use can donate $100 to a campaign and pay an optional $10 tip to GIVEasia. 


# The Problem
Since GIVEasia was founded, thousands of transactions have been recorded in the database. When a user makes a donation on GIVEasia, a new row of the transaction record is created. Typically I have to manually go to the backend, hit a button and export the monthly transaction CSV file in the following format:

Column| Field (String) | Example 
------|-------|--------
Date | Timestamp of donation | 1 Jun 2017 06:33:40 +0800
Name | Username | LukeHC or Anonymous
E-mail | email | Test@gmail.com
Charity |	organization who receives the money | RED CROSS TAIWAN
Movement | which fundraising campaign | Help Typhoon Victims
Amount | donation amount | SGD 20.00
Net Amount | donation amount without payment processing fee	| SGD 19.60

Things that need to be fixed:

1. Some fields are messed up with redundant text. For example "SGD" (which stands for Singapore Dollar)
2. Data types
3. Special or test fundraising campaigns are also included 

# First solution with EXCEL 

Excel was the only data analysis tool I knew so it's obviously my only choice then. I needed to perform the following steps just to get basic descriptive statistic.

1. Manually merge all monthly transaction files
2. Remove redudent text
3. Summarize data with complex array functions

Performance soon became a major headache and I would literally spend the entire afternoon just to upadte the file. I tried to learn VBA to automate the process but it didn't take long for me to realize that I need a different approach.

PLACEHOLDER : add sample Excel syntax

# Searching for a better solution - SQL

I took the free courses on Khan Academy - Hour of SQL - https://www.khanacademy.org/computing/hour-of-code/hour-of-sql


#  Correcting formats


# Summarize data

# Conclusion
What the current state of the project and want can ben built further 
