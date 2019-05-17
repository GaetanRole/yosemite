# YoShip

YoShip is a cool project with a JS back and front app.
- Front : https://github.com/GaetanRole/yoship-front
- Back : https://github.com/GaetanRole/yoship-back

This project is for Wild Code School students in Paris and it is made in Javascript (React / NodeJS).
It aims to promote a new way of delivery (like Chronopost) but mainly for luxury brands.

## Instructions

### Project requirements for front app

- [TO BE REPLACED BY STUDENTS]

### Suggested requirements (for Mac)

- [TO BE REPLACED BY STUDENTS]

### Suggested requirements (for Windows)

- [TO BE REPLACED BY STUDENTS]

### Project contents

```
config/
models/
public/
routes/
tests/
README.md
```
## Application Structure

- `app.js` - The entry point to our application. This file defines our express server and connects it to MongoDB using mongoose. It also requires the routes and models we'll be using in the application.
- `config/` - This folder contains configuration for passport as well as a central location for configuration/environment variables.
- `routes/` - This folder contains the route definitions for our API.
- `models/` - This folder contains the schema definitions for our Mongoose models.

## Suggested Dependencies

- [expressjs](https://github.com/expressjs/express) - The server for handling and routing HTTP requests
- [express-jwt](https://github.com/auth0/express-jwt) - Middleware for validating JWTs for authentication
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - For generating JWTs used by authentication
- [mongoose](https://github.com/Automattic/mongoose) - For modeling and mapping MongoDB data to javascript 
- [mongoose-unique-validator](https://github.com/blakehaswell/mongoose-unique-validator) - For handling unique validation errors in Mongoose. Mongoose only handles validation at the document level, so a unique index across a collection will throw an exception at the driver level. The `mongoose-unique-validator` plugin helps us by formatting the error like a normal mongoose `ValidationError`.
- [passport](https://github.com/jaredhanson/passport) - For handling user authentication
- [slug](https://github.com/dodo/node-slug) - For encoding titles into a URL-friendly format

## Workflow

**YoShip works with SCRUM method**.

It means that you need to make sprints, SCRUM rituals and so on according to your trainer at the Wild Code School.
You have to create a complete Backlog Product dispatched on your Github dashboard with some issues sorted by labels such as feature types, priorities, sprints number, the workflow process...

Before each sprint, you have to organize your issues with weight and priority. You can see that with your "Product Owner" (who is Cedric Hidot, Gaëtan Rolé and other YoShip members).

During each sprint, push on your new branch with **clear and english commit messages**.
When you are ready, write a **complete pull request** with all your modification int it. **This one has to be very clear and detailed**. 
When pull request is okay, **you can squash all your commits into one** (do not hesitate to fixup some useless messages) and rebase your branch.
Do not forget to move your issues (or by commits / PR) on your project dashboard.

At the end of the sprint, **you need to present your sprint work to your client** with a structured presentation like a Google doc with a summary.
Once you sprint is validated, you can share your feedback with your Product Owner and close for good your sprint issues.

## SCRUM - Definition of done

Each SCRUM team has its own DoD or acceptance criteria for User Stories. **For this project, you have to respect those ones**:
- Documented code (and markdown when it's necessary),
- Commit for each step of the User Story,
- Feature done like it has been described,
- JS Linter,
- Code merged into develop and then preprod.

## Usage

- 1/ **Clone this repository by SSH**.
- 2/ Create your **new branch** with a correct name according to your first issue available on your project dashboard. **The branch naming convention is: ``[branch-type]/[issue-number][sort-issue-title]``**.
     According to the Git flow, branch types are usually : feature, hotfix, release... E.g : ``feature/02-connect-authentification``, ``feature/12-yoship-client-dashboard``.
- 3/ `npm install` to install all required dependencies.
- 4/ Install MongoDB Community Edition ([instructions](https://docs.mongodb.com/manual/installation/#tutorials)) and run it by executing `mongod`.
- 5/ `npm run dev` to start the local server.

## Installation instructions

[ NEED TO BE REPLACED BY YOURSELF ]

## Documentation

Before this development, **be sure to be comfortable with your current work environment**.
Like to setup your IDE, install all necessary plugins, prepare your keyboard shortcuts, create your Bash aliases etc...
To follow best practices and good resources you can read :

- [The starter used for this repo](https://github.com/gothinkster/node-express-realworld-example-app)
- [NodeJS best practices](https://github.com/i0natan/nodebestpractices)
- [A complete NodeJS starter](https://github.com/sahat/hackathon-starter).
- [Gitflow](https://fr.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

[⬆️ Back to top](#YoShip)
