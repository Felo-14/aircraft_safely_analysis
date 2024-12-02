# Aircraft Safety Analysis

You've made it all the way through the first phase of this course - take a minute to celebrate your awesomeness!

Now you will put your new skills to use with a large end-of-Phase project!

In this project description, we will cover:

* [***Getting Started:***](#getting-started) guidance for how to begin your first project

## Project Overview

This project aims at;

* Identifying potential risks of aircraft.

* Determining aircraft with lowest risk for a company.

* Giving insights on purchasing and operating commercial and private enterprises, for a company aspiring to expand into the aviation industry.


### Business Understanding

Our company seeks to expand into the aviation industry, and I am tasked to ensure a successful entry by identifying the lowest-risk aircraft options for both commercial and private operations.
 
I need to delve into and analyze the potential risks associated with aircraft ownership and operation, and provide actionable insights to guide the head of the new aviation division in making informed decisions about aircraft purchases.


### Data Understanding

The data being used is from the National Transportation Safety Board (NTSB) aviation accident database.

In the `data` folder is a [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses), containing information from 1962 to 2023 about civil aviation accidents within the United States, its territories and possessions, and in international waters. 

The key variable used include:
1. Make (Aircraft)
2. Total Fatal Injuries
3. Number of Engines

### Data Analysis

The visualization shows the number of fatal injuries suffered per aircraft make
![Visualization for Fatal Injuries By Make](/images/Fatal%20Injuries%20by%20Make.png)

The visualization shows the number of fatal injuries suffered per year
![Visualization for Fatal Injuries per Year](/images/Fata%20Injuries%20Per%20Year.png)

The visualization shows the number of fatal injuries suffered per the number of engines in an aircraft
![Visualization for Fatal Injuries By Number of Engines](/images/Fatal%20Injuries%20by%20Number%20of%20Engines.png)

A professional GitHub repository has:

1. `README.md`
    * A file called `README.md` at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
    * This file contains these sections:
       * Overview
       * Business Understanding
          * Include stakeholder and key business questions
       * Data Understanding and Analysis
          * Source of data
          * Description of data
          * Three visualizations (the same visualizations presented in the slides and notebook)
       * Conclusion
          * Summary of conclusions including three relevant findings

### Interactive Dashboard

The interactive dashboard is a collection of views that allows the viewer to change the views to understand different features in the data. This dashboard will be linked within your GitHub repository README.md file so that users can explore your analysis. Make sure you follow visual best practices that you have learned in this course. Below is an example of what you could produce for this assignment.
![tableau dashboard for aviation accidents](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v3/master/example_dashboard.png)

### Recommendations

Here are the key recommendations for the company based on the analysis made:

* The company should consider purchasing aircrafts manufactured by Embraer because they were not involved in as many fatal injuries in accidents compared to other aircraft makes.Additionally, they are fuel-efficient, versatile, and well-suited for regional and short-haul operations.

* The company should also consider purchasing aircrafts manufactured by Airbus as they did not suffered fewer accidents leading to fatal injuries compared to other aircraft makes.
Moreover, they are renowned for reliability, fuel-efficiency, and short-haul commercial flights.

* The company should consider purchasing twin-engine or quad-engine aircraft as they did not suffer as many accidents as single-engine aircraft, and they are commonly used today.

* The company should also consider selecting aircraft models with proven reliability and strong manufacturer support.

## Summary
This project will give you a valuable opportunity to develop your data science skills using real-world data. The end-of-phase projects are a critical part of the program because they give you a chance to bring together all the skills you've learned, apply them to realistic projects for a business stakeholder, practice communication skills, and get feedback to help you improve. You've got this!