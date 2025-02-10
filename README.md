# Automated Testing of User Authentication System

📌 Project Overview

This project focuses on testing the registration and login pages using manual and 
automation testing techniques. It ensures that users can register and 
log in seamlessly with proper validation, security, and functionality checks.

## 🛠 Technologies & Tools Used

Languages: Java, HTML, CSS, JavaScript

Testing Frameworks: Selenium WebDriver, TestNG

Test Management & Reporting: JIRA, TestNG Reports, Excel (Bug Report & Test Cases)

Automation Tools: Selenium, ChromeDriver, GeckoDriver

Browsers Tested: Chrome, Firefox

Version Control: Git, GitHub

## 🔍 Features Tested

✅ User Registration Form Validation (Username, Email, Password requirements)

✅ Login Authentication (Correct vs. Incorrect Credentials)

✅ Error Message Handling (Validations for empty or incorrect inputs)

✅ Cross-Browser Compatibility Testing (Chrome, Firefox)

✅ Functional & Usability Testing (Ensuring smooth user experience)

✅ Test Execution & Bug Reporting (Tracking & documenting issues)

## 📂 Project Structure

|-- registration-page-testing/
    |-- src/
        |-- registration_page_testing/
            |-- NewTest.java  # Selenium test script
    |-- test-output/
        |-- emailable-report.html  # TestNG Report
        |-- testng-results.xml  # Test results
    |-- bugs report.xlsx  # Documented test defects
    |-- test case report.xlsx  # Designed test cases
    |-- README.md  # Project Documentation
    
    
## 🚀 Setup & Execution Guide

Prerequisites

1.Install Java JDK (8 or higher)

2.Install Eclipse/IntelliJ for Java development

3.Add Selenium WebDriver dependencies

4.Download ChromeDriver/GeckoDriver for browser automation



Steps to Run the Tests

1️⃣ Clone the Repository:

git clone https://github.com/your-username/User-Authentication-Testing.git
cd User-Authentication-Testing

2️⃣ Open in IDE & Configure Dependencies:

Import the project into Eclipse/IntelliJ

Ensure Selenium & TestNG libraries are configured

3️⃣ Run the Test Cases:

mvn test  # If using Maven
# OR run directly from TestNG in the IDE

4️⃣ Check Test Reports:

Open test-output/emailable-report.html for results

Analyze testng-results.xml for detailed execution logs




# register-page-testing
### This is an automation script using Selenium and TestNG to test a register page.

### testing scope : 
    - in scope : functions related to register process,
      1- verifiy if all input fields meets the requirements 
         (first name - last name - email - phone - password)
      2- verify the verification email sent or not.
      
    - out of scope : all non-functional tests -load and performance test- also UI test.


# to run this project on your machine:
1- install java and eclipse IDE.
2- install TestNG extension to eclipse (from eclipse marketplace). 
3- add selenium JARs as external JARs to the project (JARs exist in folder "selenium").
4- the class newtest : it contains all methods used to perform test cases.
5- after running the project successfully an auto-generated report would be created contaiining the testing results, it can be found at:
    folder->test-output/index.html and test-output/emailable-report.html
5- the test can be run only once successfully, to rerun it again a change would be done,emails used in all functions would be changed.

## attached to this project two excel files containg test cases report for manual testing and bugs report for manually detected defects.
## also attached the automation reports in two .html files "index.html" & "emailable-report.html"


📝 Test Reports & Findings

Test Cases: Defined in test case report.xlsx

Bugs & Issues: Logged in bugs report.xlsx

Automation Execution Report: Available in test-output/emailable-report.html



# 📢 Future Improvements

🛠 Enhance test coverage by adding more edge case validations

🚀 Integrate with CI/CD pipelines (Jenkins/GitHub Actions)

🔐 Expand security testing to check for vulnerabilities in authentication


# 🤝 Contributing

Pull requests are welcome! If you find any issues, please open an Issue on GitHub.



# 📜 License

This project is licensed under the MIT License.

  
