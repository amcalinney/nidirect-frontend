# Guidance for installing the nidirect-frontend node.js package manager (npm) package
##  Before you install the nidirect-frontend package
 - You need to install [node.js](https://nodejs.org/en/) and the [govuk-frontend npm package](https://www.npmjs.com/package/govuk-frontend).  For guidance on how to do this, visit the [GOV.UK frontend website](https://frontend.design-system.service.gov.uk/installing-with-npm/#requirements).
 - You will need a Sass compiler to generate the CSS code for both packages.
## Installing the nidirect-frontend package
- Open a command line window;
- Navigate to the root folder of your application.  Using the change directory command `cd` followed by the path to the root folder. 

For example: 
  `cd user/documents/myapplication` 
  
- Within your application's root folder, install the npm package using the command:

  `npm i nidirect-frontend`
  
 When the installation finishes, the nidirect-frontend package will be in the same folder that govuk-frontend package is held.
  
## Implementing the code in your project
 - Once you have verified that both the govuk-frontend and nidirect-frontend packages are in your project folder, compile the Sass.  
     -Most popular integrated development environments (IDE) support plugins or exentions that allow you to compile SASS easily.
 - If you prefer, you can compile the Sass manually using the command line.
