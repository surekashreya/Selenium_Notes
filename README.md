# Selenium_Notes

A framework defines teams way of doing things ‘common standard’ 
It Achieves 
•	Easy to maintain.
•	Data Driven tests. 
•	Meaningful reporting – automatically generate reports and can be easily understand by others 
•	Standard and consistent coding- there should be standard coding throughout the project code conventions, loggers etc. 
•	Encapsulation of UI interactions – test methods are imposed to implemented libraries of the framework. No direct interaction of test method with the UI. 
•	Maximize code re-usability – can be used by others. We should always use the DRY principle. 

Page Object Model?
•	A design pattern that has become famous in selenium test framework. 
•	A page object wraps an html page with APIs, that allows us to work with page element. 
•	A page object should encapsulate the code used to find and manipulate the data/elements in the page itself.
•	It enhances the test maintenance and reduces the code duplication. 
•	Page object will have a wrapper kind of thing that will interact with our web application and interface to interact with it. 
•	Test class will only call the method, but the page object will have all the methods to interact. 
Advantage 
Code reusability- write once and use it in different tests.
Code Maintainability- There is a clean separation between test code and page specific code. 
Efficient – shorten the learning curve for the testers and help QA teams meet timelines. 
Readability- Improves readability due to clean separation between test code and page specific code .


Data Driven - Testing your application with different datasets for e.g., Login feature – with different validations like long pass, short pass, without special character.  
