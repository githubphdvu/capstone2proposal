# Project Proposal
|             | Description                                                                                                                                                                                                                                                                                                                                              | Fill in |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| Tech Stack  | What tech stack will you use for your final project?                                                                                                          |    React/Express/PostgreSQL     |
| Stack Focus | Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application?                                                                                                                                                                                                 |    It's an evenly focused full-stack      |
| Type        | Will this be a website? A mobile app? Something else?                                                                                                                                                                                                                                   |  It's a website                                                                       |
| Goal        | What goal will your project be designed to achieve?                                                                                                                                                                                                                            | Provide a platform for gaming enthusiasts to discover, explore games across various genres.                                                                            |
| Users       | What kind of users will visit your app? In other words, what is the demographic of your users?                                                                                                                                          | Users will primarily be individuals interested in discovering and engaging with games, exploring different genres, and interacting within a gaming community.                                                                                                                         |
| Data        | What data do you plan on using? How are you planning on collecting your data? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain. You are welcome to create your own API and populate it with data. If you are using a Python/Flask stack, you are required to create your own API. | It utilizes PostgreSQL to store and manage the following types of data:Users: User profiles, authentication details, preferences.Games: Details such as title, description, genre, images.Genres: Categories to classify games.User-Game Interactions: Data reflecting user likes/unlikes for games.Data will be collected and managed through RESTful APIs developed in Node.js, allowing for CRUD operations to manage users, games, genres, and user interactions securely        |

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

| Task Name                   | Description                                                                                                   | Example                                                           |
| --------------------------- | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Design Database schema      | Q.Determine the models and database schema required for your project.                 A.Genres and Games: One-to-many relationship where each game is associated with exactly one genre. The genre_handle in Games references the handle in Genres.Users and Likes: One-to-many relationship where each user can have multiple likes (interests, liked, accepted, rejected) for multiple games.Likes references Users and Games tables through foreign key constraints.                          | [Link](https://github.com/hatchways/sb-capstone-example/issues/1) |
| Source Your Data            | Q.Determine where your data will come from. You may choose to use an existing API or create your own.A.from own PostgreSQL database           | [Link](https://github.com/hatchways/sb-capstone-example/issues/2) |
| User Flows                  | Determine user flow(s) - think about what you want a user’s experience to be like as they navigate your site. | [Link](https://github.com/hatchways/sb-capstone-example/issues/3) |
| Set up backend and database | Configure the environmental variables on your framework of choice for development and set up database.        | [Link](https://github.com/hatchways/sb-capstone-example/issues/4) |
| Set up frontend             | Set up frontend framework of choice and link it to the backend with a simple API call for example.            | [Link](https://github.com/hatchways/sb-capstone-example/issues/5) |
| User Authentication         | Fullstack feature - ability to authenticate (login and sign up) as a user                                     | [Link](https://github.com/hatchways/sb-capstone-example/issues/6) |

## Labeling

Labeling is a great way to separate out your tasks and to track progress. Here’s an [example](https://github.com/hatchways/sb-capstone-example/issues) of a list of issues that have labels associated.

| Label Type    | Description                                                                                                                                                                                                                                                                                                                     | Example                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| Difficulty    | Estimating the difficulty level will be helpful to determine if the project is unique and ready to be showcased as part of your portfolio - having a mix of task difficultlies will be essential.                                                                                                                               | Easy, Medium, Hard           |
| Type          | If a frontend/backend task is large at scale (for example: more than 100 additional lines or changes), it might be a good idea to separate these tasks out into their own individual task. If a feature is smaller at scale (not more than 10 files changed), labeling it as fullstack would be suitable to review all at once. | Frontend, Backend, Fullstack |
| Stretch Goals | You can also label certain tasks as stretch goals - as a nice to have, but not mandatory for completing this project.                                                                                                                                                                                                           | Must Have, Stretch Goal      |
