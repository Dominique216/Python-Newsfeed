[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Python-Newsfeed
## Description 
This application is a Fullstack blog application with a frontend made using Handlebars and Javascript and a backend made using a mySQL database, RESTful api routes and python. Upon opening the app, it can be used to view posts. Once logged in, the user can add comments, like posts, or go to the dashboard to view, update, or delete thier own posts.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
## Installation
To install on locally:
1. Copy the SSH key from the Repo into a folder on your own computer
2. Once the files are installed, open the folder in your personal workspace
3. For this application you will need to install bcrypt, Flask, PyMySQL, SQLAlchemy, and python-dotenv.
4. Once the dependencies are install, open the integrated terminal on the root and create the python virtual environment, then activate it.
5. The python seeds.py command can be run if preseeded data is desired.
6. Run python -m flask run to start the app.
## Usage
Visit the deployed Heroku page [here](https://python-newsfeed22.herokuapp.com/)

Upon visiting the site for the first time, the user can view posts and comments. They can also see the top nav-bar links.
<img width="1271" alt="Screenshot 2023-04-07 at 4 38 45 PM" src="https://user-images.githubusercontent.com/117382111/230683220-7a683af6-c9d1-404d-a48f-88af79f53a8b.png">


If the user tries to add an comment or navigate elsewhere, the login page will be rendered instead.

If the user has not created an account on this site, they sign up. Otherwise, they can login in with thier existing account information.
Once logged in, the login link on the nav-bar is replaced with a logout option, the dashboard option appears, and the user can now upvote or add comments to posts by clicking the upvote or add comment button.
<img width="1246" alt="Screenshot 2023-04-07 at 4 38 57 PM" src="https://user-images.githubusercontent.com/117382111/230683257-0c4b993b-66fb-4b87-8551-3ce205207add.png">

If the dashboard option is pressed, the user can add a new post, or update an exising post they made by clicking on the post title.
<img width="1261" alt="Screenshot 2023-04-07 at 4 39 30 PM" src="https://user-images.githubusercontent.com/117382111/230683290-f7f85412-dabe-4f82-a2e9-ecb7b82ad56e.png">

## License
This project uses an MIT license. For more information click the license badge at the top of the README.
