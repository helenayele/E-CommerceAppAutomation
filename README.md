# Amazon Automation Suite

## Frameworks
- Selenium grid
- selenium webdriver 
- TestNG 
- Extent Report
- Docker

## Tecknology Stacks
- Java 11 (as the core programming language)
- Maven 3.8.5 (for dependency management)
- Google Chrome latest version (browser to run your tests)

## Selnium Grid
 - hub
 - node-chrome
 - node-firefox
 - node-edge
 
## Run Examples
In Selenium Grid
![seleniumgrid](https://user-images.githubusercontent.com/31482729/204040293-3910261e-57d0-4d54-b83a-7f03ae4ed636.png)
![seleniumgrid](https://user-images.githubusercontent.com/31482729/204040317-a4b24b1c-d928-41cb-a6be-377d942964d0.png)


## How To Run the project
1. extract the project either open it in IDE or open powershell
2. navigate to {your_location}\AmazonWebsiteAutomation\src\test\resources\docker
J. run docker-compose up
4. wait till the services in the compose file are up
5. navigate to {your_location}\AmazonWebsiteAutomation
6. To run the automation suite locally invoke 
  - mvn clean test -Dbrowser=chrome -Druntype=local
  To run in docker container
 - mvn clean test -Dbrowser=chrome -Druntype=remote

