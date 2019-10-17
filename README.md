# Hacktoberfest2019
## Demo on How to host in cloud 
**Step of host in cloud (heroku)**
- Have a [git](https://git-scm.com/downloads) 
- Have a [heroku](https://id.heroku.com/login) account if not then click [Here](https://signup.heroku.com/login)
- [heroku cli](https://devcenter.heroku.com/articles/heroku-cli) install in your system or repository host in [github](https://github.com)    
- After Complate all above step if you host using cli then type  ```heroku login``` in your **cmd** or **Terminal**. if you choice host using git then open browser and type [heroku.com](https://www.heroku.com/) and login in heroku. 
- After Successfuly login redirect to dashboard of heroku 
- Then click on **new** and you show you page which is have two input box. enter **app-name** and **choose region** .
- Then in cmd in type ``` heroku config:set DISABLE_COLLECTSTATIC=1 ``` or if give you error **Error: Missing required flag** then you type like this ``` heroku config:set DISABLE_COLLECTSTATIC=1 --app wmthacktoberfest2019 ```

- My Current Website look like this click [here](https://wmthacktoberfest2019.herokuapp.com/) to view