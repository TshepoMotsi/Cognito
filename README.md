To set up (after project has been cloned or downloaded):

Install Node.js (When you run the .exe installer, node will become available globally). Run this in your C-drive directory: npm install -g @angular/cli. In your project directory run npm install aws-sdk. Then run npm install in your project folder (There might be an error that suggests you run npm audit fix, this is just to resolve package issues. Just follow the given solution)

When all this is successful, you should be able to run the project on localhost:4200

PLEASE NOTE: The project is a work in progress. The core functionality that I am testing for Registering a new user, being able to send a registration confirmation email via SES and ultimately being able to log in the new user and display profile information on the securehome dashboard as a form of data retrival.
