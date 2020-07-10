# Guidance for installing the nidirect-frontend node.js package manager (npm) package
**Note:**  Before you install the nidirect-frontend package, you need to install the [govuk-frontend npm package](https://www.npmjs.com/package/govuk-frontend).  For guidance on how to do this, visit the [GOV.UK frontend website](https://frontend.design-system.service.gov.uk/installing-with-npm/#requirements).
## Installing the nidirect-frontend package
### Within the command line window
- You must navigate to the root folder of your application.  You can do this by using the change directory command `cd` to move to the location of your application. For example: 

  `cd user/documents/myapplication` 
  
- Within your application's root folder, you can install the npm package using node.js.  To do this, enter:

  `npm i nidirect-frontend`
  
  This should install the nidirect-frontend package in the same folder that your govuk-frontend package is held.
  
## Implementing the code in your project using your integrated development environment (IDE)
**Note:** This example is uses the IDE, 'Visual Studio Code' and the extension, 'Live Sass Compiler'.  Similar extensions and plugins can be found within most popular IDEs.  The SASS can also be compiled manually using command line if you prefer.
- Open your project root folder
- Turn on your SASS complier
- If the files don't compile automatically when you turn on the compiler, make a small change to the file, 'nidirect-all.scss' (for example a space at the end of a line), and save the file.  This should trigger the SASS complier and create the file, 'nidirect-all.css' within the folder: node_modules > nidirect-frontend.
