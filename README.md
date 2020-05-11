# family-graph-marco-furone
A Java Application that creates a Graph of people by reading CSV files and tests relationships between them

## The Application
This application creates a family **Graph** data structure that is populated from 2 CSV files, 
one containing a list of people and the other containing the relationships between them, 
using the **OpenCSV** library to read from CSV files.

## Tests
Several Unit Tests have been written to check the code works properly, using the **JUnit** library and passing mock data to them.

## Build
This project uses **Gradle** to build and test the application.  
The comand `gradlew clean test` can be used to run the tests.
