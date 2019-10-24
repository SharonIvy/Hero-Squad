# HERO SQUAD
 #### v1, as of, 18th October, 2019
 ### BY: Sharon Ivy Kendi M.

## DESCRIPTION:
  This is an app that allows you to recruit a well-balanced team of superheroes.
### Built With:
  * [Java](https://www.java.com/)
  * [Intellij Idea](https://www.jetbrains.com/idea/)  


## Project Pre-requisites:
  You need the following installed on your machine
  - Java
  - Java Development Kit(JDK)
  - Maven
  - Gradle
  - An IDE - IntelliJ
  To confirm, run the following commands on your Linux command line:
  ```
  $ java -version
  $ mvn --version
  $ gradle --version
  ```
  
## Project setup requirements:
  * See pre-requisites
  * Fork this repository
  * Run the command;
  'git clone https://github.com/SharonIvy/Hero-Squad.git' to clone this repository locally.

## Set-up process:
  * After cloning to your local machine navigate to the folder you cloned into and open it with IntelliJ.
  * Navigate into the ``` src/main/java/App.java ``` and click run in IntelliJ.
  * On your browser and type ``` localhost:4567 ```
    
## Running Tests 
 Create a test class for running tests in the application.
 This is a sample test that tests if the getter method works
 ```
 @Test
 public void newHero_getName_String(){
   hero testHero = Hero.setUpNewHero();
   assertEquals("Audrey", testHero.getName());
 }
 ```
 
## Known Bugs
 No bugs detected during the development of this project.
 :+1:
  
## License:
  MIT License
    Copyright (c) 2019 **Sharon Ivy Kendi M.**
   See LICENSE file for further information
  
## Support and contact details:
  e-mail address; kendishivy72@gmail.com
