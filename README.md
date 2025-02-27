# QuizGame
My first get-to-know Angular project. 

Back-end uses C#, Entity Framework and MSSQL.

[Watch this demo](https://www.youtube.com/watch?v=KGTbahGczSw)

# Given Requirements
- [x] This is an application where you will create and play quiz games.
- [x] You should create two projects: A .NET WebApi and an Angular app.
- [x] You can choose whatever database solution you want: Sqlite, SQL server or whatever you're comfortable with.
- [x] You can choose only use Entity Framework, no other ORM is allowed.
- [x] Your database should have three tables: Question, Quiz, Game.
- [x] A question needs to have a Quiz associated with it, hence a foreign key is needed.
- [x] A game needs to have a Quiz associated with it, hence a foreign key is needed.
- [x] If a quiz is deleted, all questions and games associated with it need to be deleted.
- [x] You need to use pagination, which means you can't show any lists or tables longer than the height of the screen.
- [x] You need to use Angular Material

# Features
- MSSQL database connection
- Angular Material based components for UI
- Confirmation if your answer is correct or wrong on answering
- Confirmation of your total score in the end
- Submitting your total score will save the game in the DB, and display it when "Scores history" is clicked
- Back-end to add a new Quiz is ready, front-end needs to be finished

# Challenges
- Flexbox/ grid and CSS in general
- Getting familiar with Angular framework (pages setup, imports, syntax, ..)
- Angular documentation seems to be all over the place and is quite a hassle to navigate through
- Design planning should have been better, for example, the display of quizzes should have been relative instead of absolute to start with

# Lessons learned
- Planning your project matters, the display of quizzes should be relative to the amount of quizzes in the database, as for now it is absolute, simply because I did not think about the necessity beforehand
- Angular data binding
- A lot of exposure to HTML/ CSS
- Angular syntax and functionality in general

# Areas to improve
- Front-end in general, more specifically a firm grasp on flexbox/ grid
- Project planning
