# Bank Of Flatiron 

This repository contains the code for transactions in a bank, a web application that allows users to search and see transactions , It provides a user-friendly interface for searching transactions based on their description.One can also add transactions to the application.

# Author
Author: Shalom Nganga Email: minnomacharia@gmail.com.

# Table of Contents
1.Technologies Used. 2.Installation. 3.Usage. 4.Contributing. 5.License.

## Technologies Used
-HTML CSS  and React.

## Installation
To use the Bank Of Flatiron web application, follow these steps:

1.Clone this repository to your local machine or server. 
2.Open the file in your editor.
3.Run json-server --watch db.json initialise the JSON server.
4.Run the following commands to initialise the application:
    .npm install(This installs the dependancies needed to run the application).
    .npm start(This opens the application in your local browser).
# Usage
View transaction details:

The application displays transaction details , the category , date and amount. The transaction details is fetched from a server using the fetchData function and displayed on the webpage.

Each transaction info displayed on the webpage has a "delete" button. Clicking the "delete" button removes the concerned transaction details but you have to manually refresh the page in order for the details to dissapear .
To search for transaction details:

Enter a description on the tab below the Transaction heading in the search by description field. The handlesearch function fetches the character data from the server based on the provided description. The showing function displays the searched details in the webpage.

# License
The Bank Of Flatiron code is available under the MIT License. Feel free to modify and use it for your own projects.