# My Artificially Intelligent Agenda (MAIA) v0.0
#### Created by [Amy Qin](https://github.com/amyhxqin), © January 2019 
#### This first version of MAIA is for Hackatown 2019 by Polyhx. It is not for commercial use. All scraped data belong to their rightful owners.

#### Hackatown 2019 Finalist

#### THIS IS THE README.md of MAIA v0.0, RECENTLY MADE PRIVATE. MAIA (v0.0 and upcoming version(s)) is now subject to copyright. The partial or full reproduction of any version of MAIA may lead to legal actions being taken. Please contact me at amy.huaxuan.qin@gmail.com (new email) for more information.

#### What if your agenda can complete the tasks in it for you by itself? What if it can plan all your travel trips by itself, from booking the plane tickets to making a personalized reservation for a different restaurant for each meal?

## MAIA
My Artificially Intelligent Agenda (MAIA) is an intelligent React-Flask agenda that completes recorded tasks by itself through content mining, data analysis, and speech recognition and generation based on a customized dictionary. It can not only complete simple tasks, but can also plan a series of task, such as a trip. It reads in input from the agenda, extracts keywords, mines for data from online to generate the best solution, and executes the tasks based on the solution. 

It is able to hold conversations with a human to complete its tasks, such as placing an order. It identifies the intent of the human by analyzing the syntax and the vocabulary. Thanks to a series of randomized responses, MAIA can answer questions with spontaneity, making the answers seem natural.

## Why MAIA?

#### Powerful: less time, better results

MAIA saves all the time you spend planning and researching for your tasks.

MAIA can scrape through thousands of datasets to identify the best solution based on your interests and on public opinions. It can also plan a series of tasks, such as a travel trip that includes booking plane tickets, booking a hotel room, and reserving restaurants for each meal.

#### Intuitive

MAIA can understand human language, whether it is written or spoken. MAIA accounts for different writing styles. MAIA can understand sentences with syntax or grammar errors. It can also understand numbers whether they are written in digits or in letters.

#### Personalized

MAIA makes the choices based on your preferences. MAIA not only takes into account the preferences you told it, but also analyzes your past interactions with it to provide a fully personalized service.

## User Interface

#### Log In Page

![UI for Log In](https://raw.githubusercontent.com/amyhxqin/MAIA_For_Hackatown19_Public/master/images/ui-login.png)

#### Agenda: add, delete, edit tasks!

![UI for Agenda](https://raw.githubusercontent.com/amyhxqin/MAIA_For_Hackatown19_Public/master/images/ui-agenda.png)

## Backend

#### MAIA can plan a whole travel trip for you!

![Backend: MAIA can plan a whole travel trip for you!](https://raw.githubusercontent.com/amyhxqin/MAIA_For_Hackatown19_Public/master/images/backend-dataProcessing.png)

## Important Files (Now made private. Please contact me.)
[A commented walk-through of the back-end in jupyter notebook](https://github.com/amyhxqin/MAIA_For_Hackatown19/blob/master/notebooks/maia_notebook.ipynb)

[React Agenda Component](https://github.com/amyhxqin/MAIA_For_Hackatown19/blob/master/app/http/app/src/Agenda/agenda.js)

[Flask App](https://github.com/amyhxqin/MAIA_For_Hackatown19/blob/master/app/http/api/app.py)

[Data Processing Function](https://github.com/amyhxqin/MAIA_For_Hackatown19/blob/master/app/http/api/maia_process.py)

[Task Execution Function](https://github.com/amyhxqin/MAIA_For_Hackatown19/blob/master/app/http/api/maia_call.py)
