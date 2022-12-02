# Title : Front_End_Test
 Author : Matthew Doss

 Languages : Python, Javascript
 
 Tools used : Flask, JSON

Notes :

    I wrote and tested this on a Windows machine.

    The version of Python I used for this is 3.8.7

    I also used Flask version 1.1.2, but the new version 2.1.x should run it fine.

    If not look for the older version.


Instructions :

    Step 0 : Installations
        To run this app you will need to have the following projects installed : 
        Flask

        For Flask you will need to install it. To do so go into the terminal and run the command:
        "pip install Flask"

    Step 1 : Setting up the Flask environment.
        This is different depending on whether you are using a Windows or Mac/Unix machine.
        For Windows users in the CMD prompt:
        "..\Front_end_test>set FLASK_APP=main.py"
        "..\Front_end_test>set FLASK_ENV=development"

        For Mac/Unix users in the bash terminal:
        "../Front_end_test
            $ export FLASK_APP=main.py "
        "../Front_end_test
            $ export FLASK_ENV=development "

        *NOTE : Here's a link for a better explanation or if you need a different command:
          https://flask.palletsprojects.com/en/2.1.x/tutorial/factory/#run-the-application

    Step 2 : Run the app.
        To run the app you can use either of these two commands:
        "..\Front_end_test>flask run"

        or

        "..\Front_end_test>python main.py"

    Step 3 : Go into your browser and go to the address of http://127.0.0.1:5000/
        The nav bar will link you to all the tools you will need for testing.