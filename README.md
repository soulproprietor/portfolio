# portfolio

Table Of Contents
Prerequisites

install python / pip
install django
install VS Code
Setup

create virtual env
clone repo
Open in VS Code
Launch app
What to do next?

look through the code, look at templates, models, views, understand how they work together
use the portfolio for yourself
modify and upgrade the portfolio for practice
repurpose the code for a similar website (ex: blog)
Prerequisites
Before you begin this tutorial, please make do the following items first:

Install Python from www.python.org
Install "VS Code" (or other IDE) https://code.visualstudio.com/
Install django. Terminal command: "pip install django". more info: https://www.djangoproject.com/
Install and configure git
(On Mac): brew install git
git config --global user.name "Your Name"
git config --global user.email "yourname@email.com"
Clone Repo and Open in Browser
First we will clone the repository of code from it's online location on github, then we will launch the website locally on our computer so we can see it in a browser.

Open VS Code and clone repository: (

How to Clone Tutorial: https://code.visualstudio.com/docs/editor/github)
Repository Link: https://github.com/soulproprietor/portfolio
Run the local server and check out the demo site

To run the server, in the terminal, navegate to your project folder, called portfolio. It will have the manage.py file inside. Use the command: python3 manage.py runserver. open a browser to: http://127.0.0.1:8000/ to visit your site.
Make This Portfolio Your Own
This portfolio is just a template and a starting point for you to have your own portfolio made from python and django. Experiment with the code and make your own modifications and customizations to it to make it yours!

You can change the colors, layout and so much more by playing around with the code.

How to add / edit projects
Every django project comes with its own admin dashboard already built in that allows you to update/add/delete data, control users, and much more.

In this portfolio project we will use this admin dashboard to add and edit our projects that make up our portfolio

Make sure the django local server is running and navegate web browser to: http://127.0.0.1:8000/admin

username: admin
password: admin

In the "portfolio_app" section, you can "add" or "change" your projects.

To view your portfolio, return to http://127.0.0.1:8000/

How to edit the visual layout
You can edit directly in VS code by selecting the files in the project.

Edit this file to edit the home page : portfolio_app/templates/project_index.html

Edit this file to edit the detail page: portfolio_app/templates/project_detail.html

learn about templates here: https://docs.djangoproject.com/en/3.2/topics/templates/

Publishing to the web
I like to use Heroku to quickly and easily deploy my projects to the web. There is a free basic use tier that is great for small projects.

It is very easy to deploy, once you get the hang of it, you can deploy a website with heroku in just a few lines of code.

Go to their tutorial to learn how it works. https://devcenter.heroku.com/articles/getting-started-with-python

What can I do with this portfolio?
This is your first django web app! You can update it or customize it as you wish, and upload it to the internet to serve as your portfolio. You can explore the code and see how it works, make small changes to it to see what happens etc.

Also, you can use this project as a starting point or template for any other web app you would like to create.
