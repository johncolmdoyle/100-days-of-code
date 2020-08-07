# 100 Days Of Code - Log


### [Day 5](#day5): August 5, 2020
**Today's Progress**: Right, it appears that I've got the end to end flow working successfully! Update a db table, see the trigger output in the Honeycode table!

**Thoughts:** Now, time to write up a blog post on it and go a video tutorial of the poc.

**Link to work:** [query-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode)

### [Day 4](#day4): August 4, 2020
**Today's Progress**: Great progress, was able to get the script to output Honeycode's workbook and table arns. Pulling together the whole piece by setting up the DB, and working on a very basic CRUD lambda to test the end to end workflow with.

**Thoughts:** Skipping a lot of best practices for this demo... wonder if I should go back to clean everything up.. but these are not meant to be finished products and simply proof of ideas..

**Link to work:** [query-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode/tree/master/query-honeycode)

### [Day 3](#day3): August 4, 2020
**Today's Progress**: Made a good bit of progress in getting a script to spit out the workbooks and their UUIDs. Struggling with the table names now...

**Thoughts:** Yikes, I'm going down an ugly rabbit hole with this solution.. 

### [Day 2](#day2): August 3, 2020
**Today's Progress**: Was able to get a lambda to connect and update a table within Honeycode, without the other tables formulas being ruined!

**Thoughts:** The Honeycode setup is, yet, clunky.. I don't see a nice way to pull the UUIDs of the workbook and tables without providing some script to login.. query it all.. and provide the user with the list... 

**Link to work:** [aws-rds-to-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode)

### [Day 1](#day1): August 2, 2020
**Today's Progress**: Started working on AWS Honeycode, found a resouce that demonstrates importing and overwriting a table via AWS Lambda. Started the scaffolding of the Honeycode app, understanding how to relate to a table that will be getting overwritten and built logic around the UI to account for this.

**Thoughts:** The formulas are a lot more clunky than expected. Data import into Honeycode is a huge pain. Another thought being, does working on Honeycode count towards #100DaysOfCode ¯\\\_(ツ)\_/¯¯ 
