# MasterSeleniumFramework

It has a concept of Atomic tests (Achieved by Selenium WebDriver API and RestAssured API)

Updations done:
------------------------------------------------------------
**ExtentReports V5** 
1. User can apply the Filters - 
- Author - Rajat, Nishant, Gautam, Pankaj 
- Browser - Chrome, Edge, Safari, Firefox 
- TestType - Smoke, Sanity, Regression, BVT

2. Screenshots are attached in the ExtentReport as Base64 format.

file:C:/Users/Dell/AppData/Local/Temp/Temp7fc85c1d-d89b-472e-b1cb-d93b158ea2e7_ExtentReports.zip/AutomationReport.html

**Others implementations:**
1. Retry failed test cases
2. Custom Enums, Exceptions, Annotations 
3. Serialization and Deserialization using Jackson-Databind dependency
4. Data Driven testing using JSON file
-------------------------------
5. Icons addition in ExtentReport
a. Browser icon with every test case
b. Test status 
	       Test Description -> Last -> Pass (Happy), Fail (Sad)
c. WIN + Browser
d. Navigating to Right
e. Details (Add subahanbasha Github URL)
	      Make them Links and align it with Name
------------------------------
6. Zip the ExtentReports directory into Project path (you can send this Zip file as well as an Attachment in Email)
7. Automatically open the report after tests execution.

**How to run the Project from Local machine**
1. Pull the code into your machine and import in IDE (Eclipse/intelliJ).
2. Go to testng_Local.xml -> Run this file as TestNG suite
  It should start the execution -> Parallel Cross Browser Testing.
 - **NOTE:** stg_config.properties is the default configuration file.
3. To view the Allure reports 
 - Setup the Allure in your machine
 - Go to URL (https://docs.qameta.io/allure/) -> Search for Manual installation -> Steps are mentioned
 - Go to your project location
 - Open command prompt -> allure serve allure-results

