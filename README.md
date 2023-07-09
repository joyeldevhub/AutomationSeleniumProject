# AutomationSeleniumProject
MedAll Website Automation testing in Java Selenium

### MedAll Website: Healthcare training for everyone.
* Live and on-demand healthcare courses, conferences, workshops, webinars, and sessions.
* Everything you need to host live and hybrid events with our all-in-one platform.

### The Code Explanation =>
The provided code represents a test automation scenario using Selenium WebDriver in Java. The code is organized into several classes: AutoOne, AutoTwo, AutoThree, AutoFour, and AutoFive, each building upon the previous class.

AutoOne class:
It launches the Chrome browser and navigates to the "https://medall.org/" website.
Performs various actions such as clicking on elements, scrolling, entering text, and taking screenshots.
It contains a main method that creates an instance of AutoOne and calls the one method to execute the automation scenario.

AutoTwo class:
Inherits from AutoOne and extends the automation scenario.
Calls the one method from the parent class and adds additional actions.
It contains a main method that creates an instance of AutoTwo and calls the two and three methods to execute the extended scenario.

AutoThree class:
Inherits from AutoTwo and further extends the automation scenario.
Calls the two and three methods from the parent class and adds additional actions.
It contains a main method that creates an instance of AutoThree and calls the four and five methods to execute the extended scenario.

AutoFour class:
Inherits from AutoThree and extends the automation scenario.
Calls the four and five methods from the parent class and adds additional actions, including scrolling to specific elements.
It contains a main method that creates an instance of AutoFour and calls the six and seven methods to execute the extended scenario.

AutoFive class:
Inherits from AutoFour and further extends the automation scenario.
Calls the six and seven methods from the parent class and adds additional actions.
Contains a private method eight that calls the six and seven methods from the parent class.
It contains a main method that creates an instance of AutoFive and calls the eight methods to execute the extended scenario.

Each class represents a specific level of automation and extends the functionality by adding new actions or behaviors. The main methods in each class create an instance of the corresponding class and call the appropriate methods to execute the automation scenarios.

Overall, the code performs a series of interactions with the "https://medall.org/" website using Selenium WebDriver to automate various actions like clicking, scrolling, entering text, taking screenshots, and navigating between pages.
