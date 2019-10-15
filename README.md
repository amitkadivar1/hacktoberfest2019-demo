# Hacktoberfest2019
## Demo on How to host in cloud 
**Step to host in cloud (heroku)**
- Have [git](https://git-scm.com/downloads) installed
- Have [heroku](https://id.heroku.com/login) account (if not then click [Here](https://signup.heroku.com/login))
- You need either to install [heroku cli](https://devcenter.heroku.com/articles/heroku-cli) on your system or host the repository in [github](https://github.com)    
- After Complete all the above steps
  - if you host using the cli then type  ```heroku login``` in your **cmd** or **Terminal**
  - if you choose to host using git then open [heroku.com](https://www.heroku.com/) in a browser and login in heroku. 
- After Successfuly login you are redirected to the dashboard of heroku 
- Click on **new** and you should be displayed a page with two input box
  - enter **app-name** and **choose region**
- Type in a console ``` heroku config:set DISABLE_COLLECTSTATIC=1 ``` 
  - if it raise an error **Error: Missing required flag** then enter ``` heroku config:set DISABLE_COLLECTSTATIC=1 --app wmthacktoberfest2019 ```
- You can see a preview of my website [here](https://wmthacktoberfest2019.herokuapp.com/)
