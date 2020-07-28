#Run The Application
Now you can run your application using the flask command. From the terminal, tell Flask where to find your application, then run it in development mode. Remember, you should still be in the top-level flask-tutorial directory, not the flaskr package.

Development mode shows an interactive debugger whenever a page raises an exception, and restarts the server whenever you make changes to the code. You can leave it running and just reload the browser page as you follow the tutorial.

#####For Linux and Mac:
    $ export FLASK_APP=flaskr
    $ export FLASK_ENV=development
    $ flask run

#####For Windows cmd, use set instead of export:
    set FLASK_APP=flaskr
    set FLASK_ENV=development
    flask run

#####For Windows PowerShell, use $env: instead of export:
    $env:FLASK_APP = "flaskr"
    $env:FLASK_ENV = "development"
    flask run

You’ll see output similar to this:

* Serving Flask app "flaskr"
* Environment: development
* Debug mode: on
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
* Restarting with stat
* Debugger is active!
* Debugger PIN: 855-212-761
Visit http://127.0.0.1:5000/hello in a browser and you should see the “Hello, World!” message. Congratulations, you’re now running your Flask web application!