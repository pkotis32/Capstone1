# Project Proposal

Use this template to help get you started right away! Once the proposal is complete, please let your mentor know that this is ready to be reviewed.

## Get Started

|            | Description                                                                                                                                                                                                                                                                                                                                              | Fill in |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Tech Stack | What tech stack will you use for your final project? It is recommended to use the following technologies in this project: Python/Flask, PostgreSQL, SQLAlchemy, Heroku, Jinja, RESTful APIs, JavaScript, HTML, CSS. Depending on your idea, you might end up using WTForms and other technologies discussed in the course.                               |  Python/Flask, PostgreSQL, SQLAlchemy, Jinja, RESTful APIs, WTForms, Bcrypt, HTML, CSS, Bootstrap       |
| Type       | Will this be a website? A mobile app? Something else?                                                                                                                                                                                                                                                                                                    | Website |
| Goal       | What goal will your project be designed to achieve?                                                                                                                                                                                                                                                                                                      | The goal of this project is to create a website that allows a user to search for recipes based on certain ingredients they are in the mode for eating. This website will hopefully be able to help users overcome the mental frustration of not being able to figure out what to eat, and also explore new recipes that a user has never tried before. The website will also allow a user to pick favorite recipes and save them, along with having the ability to save adjustments to the recipes they saved. Additionally, a user may be able to enter a recipe completely from scratch and be able to save it.       |
| Users      | What kind of users will visit your app? In other words, what is the demographic of your users?                                                                                                                                                                                                                                                           | The demographic for this app can really be anyone as I am pretty sure everyone has tried to cook a meal ato some point in their lives. So whether the user is an avid cook or someone brand new, this website will be helpful for both types of people.         |
| Data       | What data do you plan on using? How are you planning on collecting your data? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain. You are welcome to create your own API and populate it with data. If you are using a Python/Flask stack, you are required to create your own API. | I plan on using a recipe finder api that will allow me to search for recipes based on certain ingredients. I would like to collect data from the api such as the recipe title, ingredients involved, and the recipe instructions, as well as possible some images. I will create my own api as well that will allow me to be able to register and authenticate a user, and allow users to save, add, and edit certain recipes.          |

# Breaking down your project

When planning your project, break down your project into smaller tasks, knowing that you may not know everything in advance and that these details might change later. Some common tasks might include:

- Determining the database schema
- Sourcing your data
- Determining user flow(s)
- Setting up the backend and database
- Setting up the frontend
- What functionality will your app include?
  - User login and sign up
  - Uploading a user profile picture

Here are a few examples to get you started with. During the proposal stage, you just need to create the tasks. Description and details can be edited at a later time. In addition, more tasks can be added in at a later time.

| Task Name                   | Description                                                                                                   | Example                                                           | Actual |
| --------------------------- | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------------------- |
| Design Database schema      | Determine the models and database schema required for your project.                                           | [Link](https://github.com/hatchways/sb-capstone-example/issues/1) | [Schema Link](https://github.com/hatchways-community/capstone-project-one-5993b180a4cf40889048119ea899b4d7/blob/dev/Database%20Schema.drawio.png)
| Source Your Data            | Determine where your data will come from. You may choose to use an existing API or create your own.           | [Link](https://github.com/hatchways/sb-capstone-example/issues/2) | [Api Link](https://developer.edamam.com/edamam-recipe-api)
| User Flows                  | Determine user flow(s) - think about what you want a user’s experience to be like as they navigate your site. | [Link](https://github.com/hatchways/sb-capstone-example/issues/3) | [Link](https://github.com/pkotis32/Capstone1/issues/4)
| Set up backend and database | Configure the environmental variables on your framework of choice for development and set up database.        | [Link](https://github.com/hatchways/sb-capstone-example/issues/4) | [Link](https://github.com/pkotis32/Capstone1/issues/2) [Link](https://github.com/pkotis32/Capstone1/issues/3)
| Set up frontend             | Set up frontend framework of choice and link it to the backend with a simple API call for example.            | [Link](https://github.com/hatchways/sb-capstone-example/issues/5) | [Link](https://github.com/pkotis32/Capstone1/issues/5)
| User Authentication         | Fullstack feature - ability to authenticate (login and sign up) as a user                                     | [Link](https://github.com/hatchways/sb-capstone-example/issues/6) | [Link](https://github.com/pkotis32/Capstone1/issues/1)

## Labeling

Labeling is a great way to separate out your tasks and to track progress. Here’s an [example](https://github.com/hatchways/sb-capstone-example/issues) of a list of issues that have labels associated.

| Label Type    | Description                                                                                                                                                                                                                                                                                                                     | Example                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| Difficulty    | Estimating the difficulty level will be helpful to determine if the project is unique and ready to be showcased as part of your portfolio - having a mix of task difficultlies will be essential.                                                                                                                               | Easy, Medium, Hard           |
| Type          | If a frontend/backend task is large at scale (for example: more than 100 additional lines or changes), it might be a good idea to separate these tasks out into their own individual task. If a feature is smaller at scale (not more than 10 files changed), labeling it as fullstack would be suitable to review all at once. | Frontend, Backend, Fullstack |
| Stretch Goals | You can also label certain tasks as stretch goals - as a nice to have, but not mandatory for completing this project.                                                                                                                                                                                                           | Must Have, Stretch Goal      |
