# Content
* Api Testing Report
* Summary
* Introduction
* Install
* API Documentation
* Test Cases written
* Postman Execution
* Newman Report

# Introduction
  This documentt shows how to perform api testing from test cases and api documentation using postman and newman report

# Install
  * Postman v10.24.16 https://www.postman.com/
  * Newman 6.1.2
  * Necessary commands for newman
      * npm i newman
      *  npm install -g newman-reporter-html
      * npm install -g newman-reporter-htmlextra
 * For getting the summary report
      *  newman run CollectionName.json -e EnvironmentName.json -r cli,html
      *  newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra
 # API Documentation
    * https://docs.google.com/document/d/1YyzPMbEu6eEMFrvp-WHiJW-SvDTJvikqx1QGyyFgRXw/edit

