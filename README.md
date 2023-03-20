# A3
# about the project
This is a simple 3 page project that allows you to enter and store cars locally
it also allows you to find them on a car site
# navigating your repo
there are 4 folders. 
## js : contains javascript
  - main.js : contains javascript for all the pages. This accesses and stores care info
## css : contains styling 
  - main.css : styling for all pages
## pages : holds html pages 
  - index.html : main page to switch between enterinfo and search
  - enterInfo.html : allows user to store cars in local storage
  - search.html : allows user to find cars and find them on car site
## images : holds images for project
  - wood.jpg : background image
# Project Guidelines
please keep all files in there respective folders
# Testing
You can alter the enterInfo.html and the main.js to test the access to the local storage
# Going Live
This can be done using AWS Amplify<br />
You need to login using your AWS account<br />
then in the search bar find Amplify<br />
find and click Host your web app<br />
then in our case we click github > continue<br />
then it will ask you to connect to your github account<br />
then choose your repo then branch from the dropdowns<br />
the defaults for the build and test settings are fine for this simple project<br />
then you can click save and deploy<br />
then it should be live after it builds the project
# Getting the link
under the apps find and click the name of your project<br />
then find the name of the branch from the github repo and click it<br />
then under domain is the link for your site<br />
Note in our case it wont give you the link to the index page. you need to add /pages/index.html to the link
# Bugs and future improvements
You can record all bugs in github. and new devs can pull from the master branch and create a new branch. Then you can create a merge to master request.
