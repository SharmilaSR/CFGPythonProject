CFGPythonProject
This is the final project that has been done as part of CFG's 8 week Intro to Python & Apps course.

Python IDE used: Pycharm

Project Overview: In this project I created a program to search for recipes based on an ingredient. The standard project uses the Edamam Recipe API.

Required Tasks for the project was as follows: These are the required tasks for this project. You should aim to complete these tasks before adding your own ideas to the project.

1.Read the Edamam API documentation ★ https://developer.edamam.com/edamam-docs-recipe-api
2.Ask the user to enter an ingredient that they want to search for
3.Create a function that makes a request to the Edamam API with the required ingredient as part of the search query (also included your Application ID and Application Key
4.Get the returned recipes from the API response
5.Display the recipes for each search result
6.Save the results to a file
7.Order the results by weight or another piece of data
8.Ask the user additional questions to decide which recipe they should choose
9.Cross-reference the ingredient against the Edamam nutrition analysis API

Initial setup to access the Edamam API is as follows:

To use the Edamam API you will need to register for an account. In your Edamam account dashboard you can find an Application ID and Application Key, which you will need to make requests to the API. To make a request to the Edamam API use the following URL: https://api.edamam.com/search?q={INGREDIENT}&app_id={YOUR_APP_KEY}&app_key={YOUR_ APP_KEY} For example, if the App ID and App Key for me account were “ch37j44” and “a58hia” I wanted to search for “cheese”, the url would look like this: https://api.edamam.com/search?q=cheese&app_id=ch37j44&app_key=a58hia

**Additional feature added to print the output in the Pycharm console in a tabular format using the Tabulate module.
