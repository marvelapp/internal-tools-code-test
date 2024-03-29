# Internal Tools Code Test
The task is to write a simple ETL script in Python.

It should take around 2-3 hours so please don't spend excessive amounts of time on it.

The aim is to combine two data sources into some useful output, and is representative of a common use case in our data warehouse.

Data source #1 is a Google Sheet containing lists of ingredients for each day of the week, representing what might be in one's fridge on the given day.

Data source #2 is the food2fork Recipe API, with a simple search endpoint.

For each day, you should find suitable recipes to fit the ingredients available, and store them in a database.

## Data sources
food2fork API key: `401483f2bac6d57611efec1e5eeea03b`

food2fork API docs: https://www.food2fork.com/about/api

Google Sheet with ingredients: https://docs.google.com/spreadsheets/d/1HkFNskCmDsnU-7il2-M4vMXPv9fneOh-02hsMA-5_SA/edit?usp=sharing

## Implementation
The only stipulation is that you build the script using Python. Beyond that, you are free to use any library you need.

To submit your solution either send us a link to a code repo or send us a zip file. Please provide simple instructions on how to run your app.

## What we're looking for
By giving you this test we're looking to judge your coding ability, and the relative ease with which you can plug different sources of data together.

Things to keep in mind:
- Could another engineer read this code and know its function with minimal overhead?
- Could yourself, or another engineer easily maintain this code?
- Is the code structured efficiently?
- If the code fails, how will you know about it?
- Does your solution come with any limitations? If so, what are they?
- If you were to spend more time on this solution, what would you do and why?
