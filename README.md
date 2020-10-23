# My-store_cucumberjavaselenium
E2E testing suite for 'My Store' web app

## General info
Test automation suite for 'My Store' web application written with Selenium-Cucumer framework in Java using Maven . 'My Store' web app is dummy website for learning test automation. Contains all basic flows of a e-commerce website.

Test case for smoke test in Cucumber studio:
<a href="https://studio.cucumber.io/l/folder/1517828/smoke-test" target="_blank">Smoke test</a>

Test cases for regression test in Cucumber studio : 
<a href="https://studio.cucumber.io/l/folder/1517829/regression-test">Regression test</a>

## Prerequisites
- Java version 1.7
- Chrome version 84.0.4147.125
- Firefox version 81.0.2
  
## Setting up
After cloning run mvn clean install
  
## Running test
- "mvn test -Dbrowser=chrome" to run project on  Chrome or
- "mvn test -Dbrowser=firefox" to run on Mozzila Firefox browser.
  
## Status
Currently project contains only smoke test script