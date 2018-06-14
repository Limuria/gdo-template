# gdo-template
This project contains a template for creating a new application for the GDO Section mode using Heroku and Node.js. 

## How this work:
This project is composed by 6 static webpages. One of the webpages (at /control) is meant as a control panel; the other five (/0, /1, /2, /3 and /4) are meant to be displayed in five consecutive browsers. Notice, that the pages have no connection between them; should you want to implement any connection or interactivity of the control panel, you can do it.


## Getting started:

1. Clone this repository from GitHub and checkout that clone locally.
```sh
$ git clone git@github.com:dsi-icl/gdo-template.git
$ cd gdo-template
```

2. Create an account on https://www.heroku.com/.
3. Create a new Node.js app on Heroku and follow the instructions provided online on using the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

4. Configure git to [deploy to heroku](https://devcenter.heroku.com/articles/git)

4. Deploy your code to Heroku 
```sh
$ git add .
$ git commit -m "Your new changes"
$ git push heroku master
```

5. Create a new entry on the GDO One-button (Touch) system that points to your app. (for this, talk to someone in the visualisation team).

6. Repeat step 4 as many time as you want to commit new changes, fixes and improvements. Heroku will redeploy your project after each commit, and the GDO will automatically reflect the changes.
