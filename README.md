# Task 38 Video - Selenium WebDriver and page object pattern
Please, watch video about waiters in Selenium WebDriver and page object pattern.
https://coherentsolutions.sharepoint.com/sites/training-center/_layouts/15/stream.aspx?id=%2Fsites%2Ftraining%2Dcenter%2FPrograms%2FTest%20Automation%2Fvideo%2Fen%2FLecture4%2Emp4&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview

# Task 40 Selenium WebDriver
This training is related to complex interaction with Selenium WebDriver (Waiters, Actions class, Data-Driven Testing). You could use any other source of information based on examples.
Complete task 40 with help of documentation and task 25.

Complete tasks:
1. Create a parametrized test, which will login to the site with at least 2 different credentials (you can use account from task 30 + create additional one).
2. Add implicit waiter for WebDriver.
3. Add Thread.sleep for login test, which was created on previous training. What type of waiter is it (add your answer as comment near sleep)?
4. Add explicit waiter for login test, which will wait until name appears (after login). Add polling frequency, which is differ from default value  
5. Create test with multiselect (URL - https://demo.seleniumeasy.com/basic-select-dropdown-demo.html). Select 3 random options in “Multi Select List Demo” section and verify that they are selected (for this case don’t work with UI verification)
6. Create 3 tests for alerts (URL - https://demo.seleniumeasy.com/javascript-alert-box-demo.html). 2 tests for “Java Script Confirm Box” and test 1 for “Java Script Alert Box”.
7. Create automated script, which waits for user (URL - https://demo.seleniumeasy.com/dynamic-data-loading-demo.html).
8. Create automated script for the following task:
- Go to https://demo.seleniumeasy.com/bootstrap-download-progress-demo.html
- Click Download
- Refresh page when percentage is >= 50
9. Create automated script for the following task:
- Go to https://demo.seleniumeasy.com/table-sort-search-demo.html
- Select “10” option in dropdown “Show () entries”
- Create method, which returns list of your custom objects (class fields: Name, Position, Office) with age > x and salary <= y for all pages 