# OneMapAutomationProject
BDD Maven based framework for automation using Selenium Cucumber and TestNg
Cucumber-BDD-Automation-Framework
BDD Maven based framework for automation using Selenium Cucumber and TestNg
Pre-requisites
Java
Maven
Eclipse

Eclipse Plugins
•	Maven
•	Cucumber
•	TestNg
This framework contains Automation Test Scenarios for OneMap Website, containing:
The framework has following features
1.	POM Approach to Project Structure
2.	Maven based framework
3.	Report Generation (Extent Report)
4.	Helper class to handle web component such as (TryCatch, ExplicitWait)
5.	Hooks for different browser support and Take Screenshot on Test Failure
6.	Tests are runnable from the command line with parameter browserName
7.	Tests can be configured to run on a various browser and OS combinations and Tests are runnable from the command line with parameter browserName
8.	Tests run in headless mode

 
The Project contains:
•	1 feature (feature file)
Feature: Validate the OneMap site
•	6 Scenarios
Scenario: Validate Different options in Home Page
Scenario: Validate Covid Test Providers Option
Scenario: Validate Nearby Park Option
Scenario: Validate Essential Amenities Option
Scenario: Validate Different options in More Menu
Scenario: Validate Happy Smiley Option
Directory structure:
 

![image](https://user-images.githubusercontent.com/86979987/124560934-f859f500-de5a-11eb-96d9-cc895e9c0c42.png)

Steps to run at your system:
•	Clone the repository using "git clone "
•	Open command prompt and Go to your project directory 
•	To run test in Chrome Browser: Run mvn test -DbrowserName="chrome"
•	To run test in Firefox Browser: Run mvn test -DbrowserName="firefox"
Cucumber Reports: 
•	Cucumber Advance (folder - "target\cucumber-reports\advanced-reports\extentReports"), file - "extentReport.html"
Folders for this report:
![image](https://user-images.githubusercontent.com/86979987/124560992-04de4d80-de5b-11eb-96a9-75ad6984173d.png)

Sample Extent Report:
![image](https://user-images.githubusercontent.com/86979987/124561027-1162a600-de5b-11eb-843e-12a7af8d411a.png)
![image](https://user-images.githubusercontent.com/86979987/124561043-158ec380-de5b-11eb-93b2-cb7a8ec4e3ec.png)
