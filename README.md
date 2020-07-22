# Guidance for installing the nidirect-frontend node.js package manager (npm) package
##  Before you install the nidirect-frontend package
 - You need to install [node.js](https://nodejs.org/en/) and the [govuk-frontend npm package](https://www.npmjs.com/package/govuk-frontend).  For guidance on how to do this, visit the [GOV.UK frontend website](https://frontend.design-system.service.gov.uk/installing-with-npm/#requirements).
## Installing the nidirect-frontend package using the command prompt application
### Within the command line window:
- Open a command line window
- Navigate to the root folder of your application.  Using the change directory command `cd` followed by the path to the root folder. 

For example: 
  `cd user/documents/myapplication` 
  
- Within your application's root folder, install the npm package using the command:

  `npm i nidirect-frontend`
  
 When the installation finishes, the nidirect-frontend package will be in the same folder that govuk-frontend package is held.
  
## Implementing the code in your project using your integrated development environment (IDE)
**Note:** This example is uses the IDE, 'Visual Studio Code' and the extension, 'Live Sass Compiler'.  Similar extensions and plugins can be found within most popular IDEs.  The SASS can also be compiled manually using command line if you prefer.
- Open your project root folder
- Turn on your SASS complier
- If the files don't compile automatically when you turn on the compiler, make a small change to the file, 'nidirect-all.scss' (for example a space at the end of a line), and save the file.  This should trigger the SASS complier and create the file, 'nidirect-all.css' within the folder: node_modules > nidirect-frontend.
