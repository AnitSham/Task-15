# Task-15
1.
DIFFERENCE BETWEEN SELENIUM IDE, SELENIUM WEBDRIVER, AND SELENIUM GRID
SELENIUM IDE:

Here record and playback the script
It doesn’t depend on the Selenium server for running the test script.
Limited Features
Few times usage
SELENIUM WEBDRIVER:

It doesn’t record and playback the script
Selenium server isn’t a requirement for running the test script.
Support various platform & technique
We usually use
SELENIUM GRID:

We can’t use it for recording and playback the script
It uses the Selenium server prior to processing the test script.
Parallel Execution of test script

2.
WebDriver driver = new ChromeDriver();

driver.get(“https://www.google.com/");

driver.findElement(By.id(“APjFqb”)).sendKeys(“Selenium Browser Driver”);

3. Selenium is an open-source, automated testing tool used to test web applications across various browsers. Selenium can only test web applications

Automation testing aims to improve testing efficiency, accuracy, and speed time-consuming manual testing tasks. Automation testing or test automation uses open source or paid automated testing tools to test software applications quickly and efficiently, and 24/7 without human intervention

4.
ChromeDriver
GeckoDriver
SafariDriver
InternetExplorerDriver

5.
Launch the browser [WebDriver driver = new ChromeDriver();]
Navigate to a website [driver.get(“https://www.google.com/");]
Interact with the webpage [driver.findElement(By.id(“APjFqb”)).sendKeys(“Selenium Browser Driver”);]
Close the browser
Run the script [Right Click->Run As->Java Application
