# FlaskBeginnerProject
Learning Flask by creating a web based application using Flask Tutorials on Youtube


1. In the first session, we learn how to:
    - install flask in our machine
    - start with the "Hello World!" page.
    - set the environment variable with "export FLASK_APP=flaskblog.py" {No spaces between "FLASK_APP=flaskblog.py". Otherwise it is going to through error!}
    - set the environment variable in Debug mode to reload the page automatcally without restarting the program everytime we make any small changes.
    - set the environment variables in the code itselfto reduce the manual work in the terminal.
    -add multiple decorators to a function so as to resue it multiple times under different commands.
2. In the second session, we learn how to:
    - We first create the templates folder to create and store multiple html files to be rendered as the output.
    - We go on to create the basic home and about html pages, call them using render_template function in flask.
    - Next, we learn about jinja templates and understand how we can use the for loop and if-else statements to customise the tab and display contents.
    - As there was redundancy in the basic code structure for  botht he home and about pages, we created a common template for both.
    - Then, we imported them in the respective html pages using {% extends %}.
    - To add a bitt more style to the page, we imported bootstrap files into the layout.html page. This includes the Bootstarp CSS added in the head section and then the optional JS part added at the end of the body section.
    - To add style and css files  in the pages, we created a new folder called static. This is because the all the js and css files need to be stored in that folder to be used. Later, using url_for from the flask library, we import them main.css file into the layout.html page.
    - After that, we added the navigation bar at the top of the window for Login, Resgister, Home and About in the bode section. 
    - Later, we updated the "block content" block and added another sidebar to the page. With the updated "block content", the details about the all the articles we have is presented in a more neat way. 