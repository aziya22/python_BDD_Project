# Python Behave BDD Framework
<br>
This is a BDD automation framework developed on Selenium and Python Behave. Sample test side used in this project is - https://www.saucedemo.com/
<br>
**Page Object Model(POM)** is followed in this framework
<br>
**pages** folder contains the elements and corresponding actions of the pages
<br>
**features** folder contains steps folder which has all the test files and also the feature files.
<br>
**configuration** directory contains the configuration files
<br>
**drivers** directory contains the chrome and firefox driver for mac
<br>
**requirements.txt** file contains all the python packages needed to run this framework
<br>
**reports** directory contains the json files generated with allure reports
<br>

## Commands to run the tests
<br>
To run the test with allure report behave -f allure_behave.formatter:AllureFormatter -o reports/ features/login.feature
<br>
To run the test without allure report behave features/login.feature
<br>
To generate the html allure report from the json files inside reports folder allure serve reports/