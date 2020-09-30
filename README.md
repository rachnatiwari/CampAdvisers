

# CampAdvisers

- Camping blog application where users can add, update and delete posts about the camping sites they visit. These posts can be viewed and reviewed by other users. User authentication is needed for reviewing and adding posts.
- **NodeJS** using Express framework with **MongoDB** as database.
<!-- - [Video](https://drive.google.com/file/d/1OeBJjihnQe3aqUmJRKZbj0t5gNnKaEOI/view?usp=sharing) -->

## Technology Stack

- Node.js
- MongoDB
- express routing
- ejs templating
- HTML, CSS , JS

> All the dependencies being used are listed in `package.json`.


## Installation

1. Clone the repository using `git clone` 
```bash
git clone https://github.com/rachnatiwari/toDoApp.git
```


<!-- 2. Create `.env` file as per the sample `EXAMPLE.env` file in the root of your project.
- The username and password are the credentials for smtp gmail Api twillio sms api.

*Lines beginning with '#' are comments and are not required in `.env` -->

 2. Use `npm` to install dependencies for the project

```bash
npm install
```


 3. Make sure, **MongoDB** is running at your configured `url` in `.env` file. If not installed, then install from [here](https://docs.mongodb.com/manual/installation/)

- Locally start mongod as

```bash
sudo service mongod restart
```

 4. Run the program either by `npm` or `yarn` using

```bash
npm start
```


The **console** logs the following if the app is running properly
```bash
Server started on port 3000!!!
```

## Project Folder Structure

> **Note**: The folder tree does not include sub-directories for common/generated folders. For example - `node_modules`.

```bash
├── README.md
├── app.js
├── middleware
│   └── index.js
├── models
│   ├── campground.js
│   ├── comment.js
│   └── user.js
├── node_modules
├── package-lock.json
├── package.json
├── public
│   ├── scripts
│   │   └── background.js
│   └── stylesheets
│       ├── landing.css
│       └── main.css
├── routes
│   ├── campgrounds.js
│   ├── comments.js
│   └── index.js
└── views
    ├── campgrounds
    │   ├── edit.ejs
    │   ├── index.ejs
    │   ├── new.ejs
    │   └── show.ejs
    ├── comments
    │   ├── edit.ejs
    │   └── new.ejs
    ├── landing.ejs
    ├── login.ejs
    ├── partials
    │   ├── footer.ejs
    │   └── header.ejs
    └── register.ejs
```
## Features
### The app supports following features

-   Any user can see all the campgrounds added
-   Password encryption at database
-   Only authorized user can add new camp ground
-   A user may comment on any post 

## Contributions Best Practices

**Commits**

- Write clear meaningful git commit messages (Do read http://chris.beams.io/posts/git-commit/)
- Make sure your PR's description contains GitHub's special keyword references that automatically close the related issue when the PR is merged. (More info at https://github.com/blog/1506-closing-issues-via-pull-requests )
- When you make very very minor changes to a PR of yours (like for example fixing a failing travis build or some small style corrections or minor changes requested by reviewers) make sure you squash your commits afterwards so that you don't have an absurd number of commits for a very small fix. (Learn how to squash at https://davidwalsh.name/squash-commits-git )
- When you're submitting a PR for a UI-related issue, it would be really awesome if you add a screenshot of your change or a link to a deployment where it can be tested out along with your PR. It makes it very easy for the reviewers and you'll also get reviews quicker.

**Feature Requests and Bug Reports**

- When you file a feature request or when you are submitting a bug report to the [Issue tracker](https://github.com/rachnatiwari/CampAdvisers/issues), make sure you add steps to reproduce it. Especially if that bug is some weird/rare one.

**Join the development**

- Before you join development, please set up the system on your local machine and go through the application completely. Press on any link/button you can find and see where it leads to. Explore. (Don't worry ... Nothing will happen to the app or to you due to the exploring :wink: Only thing that will happen is, you'll be more familiar with what is where and might even get some cool ideas on how to improve various aspects of the app.)
- If you would like to work on an issue, drop in a comment at the issue. If it is already assigned to someone, but there is no sign of any work being done, please free to drop in a comment so that the issue can be assigned to you if the previous assignee has dropped it entirely.

