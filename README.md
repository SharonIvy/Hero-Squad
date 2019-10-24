# HERO SQUAD
**v1 (as of 11th October, 2019)**
 ### By: Sharon Ivy Kendi M.

## Description:
  This is an app that allows you to recruit a well-balanced team of super-heroes
  
## Built With:
  * Language - [Java](https://www.java.com/)
  * Intergated Development Environment - [IntelliJ IDEA](https://www.jetbrains.com/idea/)
  * Framework - [Apache Spark](https://spark.apache.org/)


## Project Pre-requisites
  You need the following installed on your machine:
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
  
## Setup Process
 ### Requirements:
  * See pre-requisites
  * Fork this repository
  * Run the command;
  'git clone https://github.com/SharonIvy/Hero-Squad.git' to clone this repository locally
 ### Installation:
  * After cloning to your local machine navigate to the folder you cloned into and open it with IntelliJ
  * Navigate into the ``` src/main/java/App.java ``` and click run in IntelliJ
  * On your browser and type ``` localhost:4567 ```
    
## Running Tests 
 Create a test class for running tests in the application
 Below is a sample test that tests if the getter method works:
 ```
 @Test
 public void newHero_getName_String(){
   hero testHero = Hero.setUpNewHero();
   assertEquals("Audrey", testHero.getName());
 }
 ```
 
## Known Bugs
 No bugs detected during the development of this project
 :+1:
  
## Licensing
  MIT License
    Copyright (c) 2019 **Sharon Ivy Kendi M.**
   See LICENSE file for further details
  
## Support and Contact Details:
  e-mail address; kendishivy72@gmail.com
