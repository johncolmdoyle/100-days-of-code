# 100 Days Of Code - Log


### [Day 12](#day12): August 22, 2020

**Today's Progress:** Spent a large portion of the day in @cfregly and @anbarth's workshop on #Kubeflow + #BERT + #GPU + #TensorFlow + #Keras + #SageMaker!

**Thoughts:** This was the second time I've taken the course, the quantity of information thrown at you is so intense. Made it a lot further - though still haven't achieved the whole 8 hours.

**Link to work:** [datascienceonaws.com](https://github.com/johncolmdoyle/workshop)

### [Day 11](#day11): August 20, 2020

**Today's Progress:** Got the RDS backup successfully migrated over to CDK!

**Thoughts:** Wow, installing postgresql 11.6 on amazon linux 2 is a massive pain...

**Link to work:** [aws-rds-nightly-backup](https://github.com/johncolmdoyle/aws-rds-nightly-backup)

### [Day 10](#day10): August 19, 2020

**Today's Progress:** A little bit more work on the kubeconvibes - going to track popularity over time. Started another mini project from within Silbo - migrating the setup to AWS CDK how we automate some of our nightly SQL statements.

**Thoughts:** Pulling the hair out trying to figure out why in a new AWS CDK project I couldn't even create buckets - apparently I installed my dependencies just as 1.60.0 was released fo @aws-cdk/s3, so was out of sync with core...

**Link to work:** [aws-rds-nightly-backup](https://github.com/johncolmdoyle/aws-rds-nightly-backup) and [kubecon vibes](https://github.com/johncolmdoyle/kubecon-eu-popular-sessions)

### [Day 9](#day9): August 18, 2020

**Today's Progress:** Wonderful progress, banged out a quick project to like KubeCon EU sessions based on their popularity

**Thoughts:** Enjoyed working on AWS CDK again - been some fantastic updates since it first got released!

**Link to work:**  [github repo](https://github.com/johncolmdoyle/kubecon-eu-popular-sessions)

### [Day 8](#day8): August 12, 2020

**Today's Progress:** Eh, questionable in terms of the code, spent the evening with Virtualbox and k3sup, got everything working and networked properly!

**Thoughts:** It is good to setup VirtualBox again, have a proper master with workers setup.

**Link to work:**  [blog post](https://gizmo.codes/k3sup-on-macos-catalina/)

### [Day 7](#day7): August 12, 2020

**Today's Progress:** Learning about k3sup and focused on installing and configuring Ubuntu via Virtualbox for testing Kubernetes.

**Thoughts:** I need to write up a post, as it has been way too long since I last stood up Ubuntu in VB, setting up SSH keys etc...


### [Day 6](#day6): August 11, 2020

**Today's Progress:** Got the blog post up and all the code fixed with Honeycode! Had messed around with roost.io over the weekend, but no actual code written so guess can't count those :(

**Thoughts:** Just dumped everything into a single blog post, with no true planning.. pretty much a mess, but just want to move on from it already!

**Link to work:**  [blog post](https://gizmo.codes/postgresql-to-honeycode-pipeline/) and [code](https://github.com/johncolmdoyle/aws-rds-to-honeycode)


### [Day 5](#day5): August 5, 2020
**Today's Progress:** Right, it appears that I've got the end to end flow working successfully! Update a db table, see the trigger output in the Honeycode table!

**Thoughts:** Now, time to write up a blog post on it and go a video tutorial of the poc.

**Link to work:** [query-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode)

### [Day 4](#day4): August 4, 2020
**Today's Progress:** Great progress, was able to get the script to output Honeycode's workbook and table arns. Pulling together the whole piece by setting up the DB, and working on a very basic CRUD lambda to test the end to end workflow with.

**Thoughts:** Skipping a lot of best practices for this demo... wonder if I should go back to clean everything up.. but these are not meant to be finished products and simply proof of ideas..

**Link to work:** [query-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode/tree/master/query-honeycode)

### [Day 3](#day3): August 4, 2020
**Today's Progress:** Made a good bit of progress in getting a script to spit out the workbooks and their UUIDs. Struggling with the table names now...

**Thoughts:** Yikes, I'm going down an ugly rabbit hole with this solution.. 

### [Day 2](#day2): August 3, 2020
**Today's Progress:** Was able to get a lambda to connect and update a table within Honeycode, without the other tables formulas being ruined!

**Thoughts:** The Honeycode setup is, yet, clunky.. I don't see a nice way to pull the UUIDs of the workbook and tables without providing some script to login.. query it all.. and provide the user with the list... 

**Link to work:** [aws-rds-to-honeycode](https://github.com/johncolmdoyle/aws-rds-to-honeycode)

### [Day 1](#day1): August 2, 2020
**Today's Progress:** Started working on AWS Honeycode, found a resouce that demonstrates importing and overwriting a table via AWS Lambda. Started the scaffolding of the Honeycode app, understanding how to relate to a table that will be getting overwritten and built logic around the UI to account for this.

**Thoughts:** The formulas are a lot more clunky than expected. Data import into Honeycode is a huge pain. Another thought being, does working on Honeycode count towards #100DaysOfCode ¯\\\_(ツ)\_/¯¯ 
