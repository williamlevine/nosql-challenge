# NoSQL Challenge - Module 12
This repository contains my code for Module 12's NoSQL Challenge. The completed notebooks for this project are jupyter files titled `NoSQL_setup.ipynb` and `NoSQL_analysis.ipynb`.

The `Resources` folder contains the file `establishments.json`. This file must be put into a MongoDB database using the code `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json` before this code can be run.

This code was based on the two files in the `Starter_Code` folder, `NoSQL_setup_starter.ipynb` and `NoSQL_analysis_starter.ipynb`. Additional code was written by referencing the in-class activities from Module 12, such as Activity 08 from Day 2 which shows how to query for particular values and phrases, and Activities 04 and 05 from Day 3 which demonstrate how to construct a pipeline.

Something to note in my code which strays a bit from the starter is that, in each section where a DataFrame is made from a query, the query code is repeated. I was having issues with making the DataFrame if the variables were not set in the same cell, and, although clunky-looking, re-running the query before making the DataFrame seemed to be necessary to get it to work.