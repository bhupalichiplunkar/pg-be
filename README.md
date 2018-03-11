<h1>Pg-app backend repo</h1>
This repo is for backend apis of pg website.

Steps to get it up and running

- Install sails, node/yarn [Ensure you have node version > 8(if not use nvm)]
- Clone this repo and run ```cd pg-be```
- Run ```yarn install / npm install```
- Run ```sails lift```

To create user : http://localhost:1337/user/create?username=user1&password=12345&email=bhupali@gmail.com

To create calendar : http://localhost:1337/calendar/create?bookingdate=25-05-2018&bookingtime=param_value&userid=1

To update calendar : http://localhost:1337/calendar/update/<id>?bookingtime=param_value

To delete calendar : http://localhost:1337/calendar/destroy/<id>


