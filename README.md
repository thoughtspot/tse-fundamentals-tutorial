# ThoughtSpot Everywhere Fundamentals for Developers

This repository contains the training content for the ThoughtSpot Everywhere Fundamentals for Developers course.

File and folder structure:

* index.html - the main html file
* `./js` - contains the javascript for the application.
* `./js/tse.js` - the main javascript file for the application.
* `./css` - contains the css for the application.
* `./css/tse.css` - the main css file for the application.
* `./img` - contains the images for the application.

## Running the application in CodeSandbox

The training content has been created as a sandbox in <a href="https://codesandbox.io/s/github/thoughtspot/tse-fundamentals-tutorial?file=/index.html" target="_blank">CodeSandbox</a> to make it easy to run and test. To edit the code, simply fork the sandbox and make your changes.

![codesandbox-fork](img/codesandbox-fork.png)

You can either create a CodeSandbox account, or choose the "Continue without an account" option at the bottom of the dialog that appears.

You can export your existing fork from CodeSandbox using the top left menu, then chooseing *File*->*Export to Zip*

![codesandbox-export](img/codesandbox-save-to-zip.png)


## Running the application locally

This is a web application and will need to be deployed to a web server to run.  

Bring down the tutorial from GitHub, or export the fork you made in CodeSandox (see above)

If you want to test locally, you can use something simple like the [Python http.server](https://docs.python.org/3/library/http.server.html):  `python3 -m http.server <port>`.  Simply run that command from the root folder (where `index.html` exists).  
