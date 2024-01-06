# Python Behave BDD Framework
<br>
<br>
This is a BDD automation framework developed on Selenium and Python Behave. 
<br>
Sample test site used in this project is -<b> https://www.saucedemo.com/ </b>
<br>
<br>
<b>Page Object Model(POM)</b> is followed in this framework
<br>
<br>
<b>pages</b> folder contains the elements and corresponding actions of the pages
<br>
<br>
<b>features</b> folder contains steps folder which has all the test files and also the feature files.
<br>
<br>
<b>configuration</b> directory contains the configuration files
<br>
<br>
<b>drivers</b> directory contains the chrome and firefox driver for mac
<br>
<br>
<b>requirements.txt</b> file contains all the python packages needed to run this framework
<br>
<br>
<b>reports</b> directory contains the json files generated with allure reports
<br>

### Commands to run the tests
<br>
To run the test with allure report behave -f allure_behave.formatter:AllureFormatter -o reports/ features/login.feature
<br>
To run the test without allure report behave features/login.feature
<br>
To generate the html allure report from the json files inside reports folder allure serve reports/