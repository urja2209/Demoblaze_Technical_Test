# Demoblaze_Technical_Test

Welcome to the DemoBlaze website, an online demo e-commerce platform. This README provides instructions on how to use the website, including logging in, adding items to the cart, and completing a purchase.

## Table of Contents
-Prerequisites
- Setup
- Running Tests
- Report Generation
- Project Structure
- Contributing
- License

# Prerequisites
Before you begin, ensure you have met the following requirements:
-Java: Install Java Development Kit (JDK) version 8 or higher.
-Maven: Install Maven to manage project dependencies.
-IntelliJ IDEA: I have used IntelliJ IDEA as the Integrated Development Environment (IDE) for this project.
- Cucumber Plugin: Install the Cucumber for Java plugin in IntelliJ IDEA for better Cucumber support.
Selenium WebDriver 
OS: Windows 

## Setup
1.	 Clone the repository to your local machine:
                -  git clone <repository-url>
      2.  Open the Project in IntelliJ IDEA
      3.  Install Project dependencies using Maven:
            - mvn clean install 
## Running Tests
You can run the tests using TestRunners and to execute the test suite, follow these steps:
-LoginTestRunner:   Open the LoginTestRunner Class
                                    Right Click select Run’LoginTestRunner’
-SignUpTestRunner: Open the SignUpTestRunner Class
                                    Right Click select Run’SignUpTestRunner’
-CartTestRunner    : – Open the CartTestRunner    Class
                                    Right Click select Run’CartTestRunner’

## Report Generation
Cucumber Extent Report is used to generate detailed HTML reports. After running the tests, you can find the report in the target/Extent_Reports/report.html.
## Project Structure
src/main/java/com/demoblaze/pages: Each webpage Contains their webelements and respective methods.
src/main/java/com/demoblaze/utility/Utility.java: It will contains all the reusable methods
src/main/java/com/demoblaze/FailedTestsScreenshots: It will capture Scrrenshot for Failed the TCs
src/main/java/com/demoblaze/logs/log.out: Explain any key information, data, or logs that it contains related to the framework.
src/test: Contains test classes organized by feature.
  src/test/java/com/demoblaze/steps :contains step definition files used in test automation frameworks, particularly when implementing Behavior-Driven Development (BDD) frameworks like Cucumber.
src/test/java/resources/featurefile: Contains Cucumber feature files.
src/test/java/resources/propertiesfile/config.properties: Configuration file contains the all-configuration data used for this project such as BaseUrl and Browser.
target: Auto-generated directory for build outputs and test reports.
## Contributing
If you would like to contribute to the development of this demo website or have suggestions for improvements, please check out the [GitHub repository](https://github.com/demoblaze/demoblaze) for this project and follow the contribution guidelines.
## License
This project does not currently have an associated license
