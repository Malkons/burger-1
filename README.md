# burger
A "Hamburger" logger with MySQL, Node, Express, Handlebars and a homemade ORM. Per assignment: follows the MVC (Model, View, Controller) design pattern, uses Node and MySQL to query and route data in the app, and uses Handlebars to generate the HTML.


## Description
This is simple full stack app with a "View" created using HTML/CSS and "Controllers" with Node.js and Express. The "Model" is created utilizing mySQL.

The user can order any kind of burger by name to add it to the left column for proverbial eating; this silmultaneously adds the new burger entry into a mySQL Database. The burger is "eaten" by clicking on "Eat this burger" and is added to the right column. The burger can be deleted by clicking on the "Use the restroom" button; this removes the entry from the Database too. 

## Demonstration
### Click [here](https://apleek3-eat-da-burger.herokuapp.com/) to try this out!

## How to install
To try this app locally - clone it using the following command lines in your terminal:

    git clone git@github.com:angrbrd/eat-da-burger.git

Next, navigate to the file in your command line director and install the application's dependencies using

    npm i
    
To run the node server locally:

    node server

Lastly, open the local application on port 8080 at the URL: http://localhost:8080/.

Enjoy!
