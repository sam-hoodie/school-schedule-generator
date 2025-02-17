# Project Overview
This project is a web application that allows you to create a school-wide schedule based on
available courses, student requests, and available teachers.

## Features
- Sign Up/Sign In including handiling duplicate and invalid credentials
- Courses, requests, and teachers are fully customizable
- Configurable schedule format (block/traditional, number of periods)
- Schedule can be viewed grouped by classroom or student
- Fully dynamic HTML/CSS web pages optimized for desktop screens
- All data is stored in a database

## Initial Setup
1. Clone this Repository to your machine.
2. Open the project in any IDE, preferably Intellij IDEA.

## How to Interact With the Web App
1. Open the ```src/main/kotlin/org/appchallenge2024/schedule/Application.kt``` file
2. Run the ```main()``` function by clicking the green arrow next to it
3. Open any browser and navigate to [http://127.0.0.1:8080/](http://127.0.0.1:8080/)

From the landing page, you can register your school, and you will be guided through
schedule creation process.

## Dependency Credits
* [Ktor](https://ktor.io/)
* [SQLDelight](https://github.com/cashapp/sqldelight)