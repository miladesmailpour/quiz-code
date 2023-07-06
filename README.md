# Code Quiz

## Description

- It is one of the needs for developers to test their knowledge at some point

- Helping the developers to practice their skills and be prepared for the interview

- A web application that takes quizzes in a user-friendly environment on the web

- Javascript, CSS, HTML

## Table of Contents

- [How To Use](#how-to-use)
- [Acceptance_Criteria](#acceptance-criteria)
- [How to Contribute](#how-to-contribute)

## How To Use

[Link to the website, deploy on GitHub](https://miladesmailpour.github.io/quiz-code/)
![Alt text](./assets/images/Screenshot1.png "User Name Input")
![Alt text](./assets/images/Screenshot2.png "Quiz Question")
![Alt text](./assets/images/Screenshot3.png "High Score")

## User Story

```md
AS A coding boot camp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers
```

## Acceptance Criteria

```md
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
```

## How to Contribute

This is an open source project which has Licensed by MIT which allow you to contribute and used open source codes used in this repo (All Branches).
More info: https://g.co/kgs/QWcHhF

- Branches are named as module[n] and each one of them its unique challenge.
- Master Branch contain the last solved challenge. (the read me your are reading trough, it is a defult guid when NO challage availabel to help you do a pre-setup.)

# how to use the module and deploy

- Clone the repo and make it own

  # Https url :

        git clone https://github.com/miladesmailpour/quiz-code

  # ssh url :

        git clone https://github.com/miladesmailpour/quiz-code

  # Checking the fetch/pull and push url :

        git remote -v

  # Modifing origin url :

        git remote add origin [https/ssh url of you repo] https://docs.github.com/en/get-started/quickstart/create-a-repo

  # Verifing the fetch/pull and push url :

        git remote -v https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories

  # Chacking the status of local :

        git status

        "if local NOT updated"
        git add .
        git commit -m "[your comment]"
        git push origin master/main

- Checkout to the module (the challenge you want to used and deploy)
  # Checkout to the disred challage :
       git checkout module[n]
  # Verifing :
       git status
  # [Make the change you wish to have]
       What do you think needed to improve?
  # Commiting to local and updating the GitHub repo:
         git add .
         git commit -m "[your comment]"
         git push origin [your module name]
- Moving Modules to Master Branch and deploy :
  # Creating a pull request to update the master/main :
       https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request
  # Deploy through the GitHub :
       https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
