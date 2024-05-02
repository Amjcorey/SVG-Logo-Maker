# SVG-Logo-Maker
Week-10 Challenge (node.js): A command line application that generates SVG file logos. Making graphic design a cake walk for developers! It uses inquirer to prompt the user within the command line for how they would like their logo to look, allowing them to choose color, shape, and 3 characters to id their logo as a signature. Once all inputs are met, the user will be presented with an SVG file.


# Installation
Clone the repo: git clone 

Open in VS Code. If you do not have VS code you must install it.

Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

Next, use the terminal to run the command "npm i" to install the dependencies associated with this application (developers may need to install inquirer and jest directly from the command line, to do so the command for inquirer will be "npm i inquirer@8.2.4" to install Inquirer.js, and "npm i jest" to install the latest version of jest).

To run the application, within the terminal, type the command node index.js. 
(See below.)

# Usage Information
To run this application, use the command line, install all dependencies-- then type the command node index.js. You will then be presented with a series of questions. Once all questions have been answered, a message will display indicating you that your logo has been generated.search for newly generated SVG file.

For unit testing instructions, navigate to the Test Instructions section. 
(See below.)

# Test Instructions 
To run unit testing, open the terminal, and use the command "npm run test"

As of now there is one test suite with three tests. The test suite is checking for a render() method to return a string for the corresponding SVG file with the given shape color.

# Credits 
Worked with tutor Gustavo Duque to help get me started on this assignment. GitHub https://github.com/Wormhole616/SVGLogoMaker