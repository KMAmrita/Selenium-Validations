# Selenium-Validations
----------------------------------problem statement-----------------------------------
No TestNG found and no run of test suite
 because the https://dl.bintray.com/testng-team/testng-eclipse-release/6.14.3/ are banned and hence no testNG is not running in the test suite.

* updated the eclipse to latest version since the TestNG for Eclipse is not getting installed from Eclipse Market Place.
* After downloading new version of eclipse faced below issue.
* so tried downloading latest jdk version and install it by giving the path of jdk - in Edit the system env variable.

*in market place of Eclipse if tried to install TESTNG for Eclipse then the below error is getting popup.
Unable to read repository at https://testng.org/testng-eclipse-update-site/content.xml.
Certificate for <testng.org> doesn't match any of the subject alternative names: 
[*.github.com, www.github.com, github.io, github.com, *.github.io, githubusercontent.com, *.githubusercontent.com
----------------------------------problem statement-----------------------------------

--------------------------------------------------------issue solution starts from here -------------------------------------------------------------------
https://mvnrepository.com/artifact/org.testng/testng/7.6.0
1)downaload latest jar file of Testng from website -configure to buildpath - add external jar to  libraries - > to check it -> ReferencedLib added jar is displayed
2)Then copy the dependency of maven and paste in pom.xml file of the project - mvn dependecies - > added dependency jar will be visible
