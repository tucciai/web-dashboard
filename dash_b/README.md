# Steps to deploy to heroku

## use already deployed app
- heroku git:clone -a tucci-dash
- cd tucci-dash
- git add .
- git commit -m "message"
- git push heroku master


## clone the file from this git repo and deploy your own app
- make new app on heroku
- git clone git@github.com:tucci-io/web-dashboard.git
- cp -R web-dashboard/dash_b/. ~/path/to/copy/folder
- cd ~/path/to/copy/folder
- git init
- git add .
- git commit -m "message"
- heroku git:remote -a {name of your heroku app, remove paranthesis}
- git push heroku master
