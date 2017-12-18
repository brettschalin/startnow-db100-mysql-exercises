
These are some examples of how to use SQL commands. See below for instructions on how to set up and use this application

#INSTALLATION

1. Make sure you have MySQL Community Edition and MySQL Workbench downloaded and installed (Follow the instructions [here](https://dev.mysql.com/downloads/mysql/) and [here](https://dev.mysql.com/downloads/workbench/). Default settings for everything should be fine).

2. Open Git Bash. If you're using Windows, [download it](http://gitforwindows.org/) and follow the instructions (again, default settings should be okay). Mac and Linux users can use the built-in terminal application.

3. `cd` to the directory this file lives in

4. Create a file called 'config.js' and fill it with the following, replacing the username and password fields with the credentials you used for setting up MySQL:

```
module.exports = {
    username: 'your_mysql_username',
    password: 'your_mysql_password'
};
```

5. run `npm install`


#USAGE

The examples are all in the 'exercises.sql' file. You can verify they work by running `npm test`. If you feel like punishing yourself, you can modify the tests or create new ones by looking in the 'test/test.specs.js' file. 
