# Trello
Trello automation code
# Visual Studio 2019
# Create Specflow project in Visual studio
# Install below PKGs.
  FluentAssertions
  JustMock
  .NET.Test.sdk
  Nunit
  Restsharp
  Selenium.Support
  Selenium.Webdriver
  Selenium.wedriver.Chromedriver
  Specu.Specflow
# For API test cases below files details & test cases are automated. No need to send any hard coding values.
  TrelloAPItesting.feature ==> This file contains BDD scenarios
  APIClass.cs ==> APIKEY and token details are hardcoded in this class library also contains all the classes related to API Test cases
  TrelloAPIStepDefinitions ==> Step definations
    Newboard creation and validation
    Newlist creation and validation
    Newcard creation and validation
    Delete all cards and validation

# For UI test cases below files details & test cases are automated. Only board name need to send for the activites.
  TrelloAPItesting.feature ==> This file contains BDD scenarios
  APIClass.cs ==> APIKEY and token details are hardcoded in this class library also contains all the classes related to API Test cases
  TrelloAPIStepDefinitions ==> Step definations
    Trello Board add new List
    Trello Board add card to list
    Trello Board delete card
    Trello Board delete list

#Go to Test Runner 
#Press run button to run the test cases
