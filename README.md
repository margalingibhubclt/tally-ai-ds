﻿
🚫 Note: All lines that start with 🚫 are instructions and should be deleted before this is posted to your portfolio. This is intended to be a guideline. Feel free to add your own flare to it.

🚫 The numbers 1️⃣ through 5️⃣ next to each item represent the week that part of the docs needs to be comepleted by.  Make sure to delete the numbers by the end of Labs.

🚫 Each student has a required minimum number of meaningful PRs each week per the rubric.  Contributing to docs does NOT count as a PR to meet your weekly requirements.

# 1️⃣ Title of project goes here

You can find the project at [🚫URL NAME GOES HERE](🚫copy and paste URL here).

## 5️⃣ Contributors

🚫Add contributor info below, make sure add images and edit the social links for each member. Add to or delete these place-holders as needed

|                                       [Student 1](https://github.com/Nov05)                                        |                                       [Student 2](https://github.com/LilySu)                                        |                                       [Student 3](https://github.com/)                                        |                                       [Student 4](https://github.com/)                                        |                                       [Student 5](https://github.com/)                                        |
| :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
|                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-female.png" width = "200" />](https://github.com/)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-female.png" width = "200" />](https://github.com/)                       |                      [<img src="https://www.dalesjewelers.com/wp-content/uploads/2018/10/placeholder-silhouette-male.png" width = "200" />](https://github.com/)                       |
|                 [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/)                 |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/honda0306)             |           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/Mister-Corn)            |          [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/NandoTheessen)           |            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/wvandolah)             |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/) |



🚫 5️⃣ Optional examples of using images with links for your tech stack, make sure to change these to fit your project

![MIT](https://img.shields.io/packagist/l/doctrine/orm.svg)
![Typescript](https://img.shields.io/npm/types/typescript.svg?style=flat)
[![Netlify Status](https://api.netlify.com/api/v1/badges/b5c4db1c-b10d-42c3-b157-3746edd9e81d/deploy-status)](netlify link goes in these parenthesis)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

🚫 more info on using badges [here](https://github.com/badges/shields)

## Project Overview


1️⃣ [Trello Board](https://trello.com/b/chjNoXqZ/labs19-tallyai

1️⃣ [Product Canvas](https://www.notion.so/Tally-AI-1cfa6653c8de4baf883f80ab9696d45e)

1️⃣ [Deployed Front End](🚫add link to deployed app here)

### Tech Stack

Python, Django, Postgres, AWS

### 2️⃣ Predictions

Spacy, Facebook Fasttext, Scattertext, Textrank

### 2️⃣ Explanatory Variables

-   Explanatory Variable 1
-   Explanatory Variable 2
-   Explanatory Variable 3
-   Explanatory Variable 4

### Data Sources

-   [Yelp Dataset] (https://drive.google.com/open?id=1FSXRxviyGPRJ-soUitha8Npa69jbYDvH)

### Python Notebooks

🚫  Add to or delete python notebook links as needed for your project

[Python Notebook 1](🚫add link to python notebook here)

[Python Notebook 2](🚫add link to python notebook here)

[Python Notebook 3](🚫add link to python notebook here)

### 3️⃣ How to connect to the web API

🚫 List directions on how to connect to the API here

### 3️⃣ How to connect to the data API  

Web Scraped Endpoints
1. Returns 10 positive and 10 negative word phrases associated with a business
2. Cumulative average of  review star ratings for the past 8 weeks  vs the average rating  per  week .
timespan 8 weeks
e.g.
8 weeks ago: 1,1,1,1,1, weekly_avg_rating=1, cumulative_avg_rating=1
7 weeks ago: 2,2,2,2,2, weekly_avg_rating=2, cumulative_avg_rating=1.5
6 weeks ago: 3,3,3,3,3, weekly_avg_rating=3, cumulative_avg_rating=2
http://django-tally-dev.n9ntucwqks.us-west-2.elasticbeanstalk.com/yelp/jga_2HO_j4I7tSYf5cCEnQ?viztype=0
Returns:

```
[
   {
     date: '2020-01-10’, 
     cumulative_avg_rating: 3, 
     weekly_avg_rating: 2
   },
   {
     date: 'Date 2', 
     cumulative_avg_rating: 4,
     weekly_avg_rating: 3
   }
]
```

Endpoints Looking Through Yelp Dataset
Returns “Trending” word phrases and their comparative fluctuations over segments of time. 
http://django-tally-dev.n9ntucwqks.us-west-2.elasticbeanstalk.com/yelp/jga_2HO_j4I7tSYf5cCEnQ?viztype=1
Returns:

```
[
   {
       date: 'string with date',
       data: [ { phrase: "phrase 1", rank: 1}, 
               { phrase: "phrase 2", rank: 1}, 
               { phrase: "phrase 3", rank: 1} ]
   },
   {
       date: 'string with date',
       data: [ { phrase: "phrase 1", rank: 2}, 
               { phrase: "phrase 2", rank: 2}, 
               { phrase: "phrase 3", rank: 1.5} ]
   },
   {
       date: 'string with date',
       data: [ { phrase: "phrase 1", rank: 2}, 
               { phrase: "phrase 2", rank: 4}, 
               { phrase: "phrase 3", rank: 2} ]
   },
]
```

Review frequency - shows change in number of reviews over time
http://django-tally-dev.n9ntucwqks.us-west-2.elasticbeanstalk.com/yelp/jga_2HO_j4I7tSYf5cCEnQ?viztype=2
Returns:

```
[{"date": "2017-8-31", "reviews": 4}, {"date": "2017-12-31", "reviews": 2}, 
{"date": "2018-1-31", "reviews": 1}, {"date": "2018-2-28", "reviews": 2}, 
{"date": "2018-3-31", "reviews": 1}, {"date": "2018-4-30", "reviews": 4}, 
{"date": "2018-5-31", "reviews": 2}, {"date": "2018-6-30", "reviews": 1}, 
{"date": "2018-7-31", "reviews": 3}, {"date": "2018-8-31", "reviews": 1}, 
{"date": "2018-9-30", "reviews": 1}, {"date": "2018-11-30", "reviews": 1}]
```

[【Testing URLs】](https://drive.google.com/file/d/1ziicAiUIfa8dI-qtMs8WJQN_5zbr2l0o/)    
[【Testing data documents】](https://drive.google.com/open?id=1EKPZh1e88_jnXafk7OJ_euSB54ilmFdJ)  
[【Testing script Colab】](https://colab.research.google.com/drive/1Gzo2lFj1cEj72mkVoko5rAo-OXaeLwot)  

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./code_of_conduct.md.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

 **If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**
 - Check first to see if your issue has already been reported.
 - Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
 - Create a live example of the problem.
 - Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes,  where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Backend Documentation](_link to your backend readme here_) for details on the backend of our project.

See [Front End Documentation](_link to your front end readme here_) for details on the front end of our project.

