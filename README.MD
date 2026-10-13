# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

Brief overview of all files:

go.mod: Describes module properties, such as dependencies on other modules and on other versions of go. 
grade_calculator.go: The actual calculator; contains functions for adding grades, calculating letter grade, and calculating grade average. 
grade_calculator_test.go: Contains tests to verify the functionality of the calculator

Running the calculator:
1. Make sure you have Go installed. If not, go install Go from https://go.dev/doc/install
2. Download the zip file by going to Code -> Download Zip
3. Extract the zip file.
4. In terminal, navigate to the grade_calculator folder.

To run unit tests, use the following command:
go test 

To run unit tests with code coverage, use the following command:
go test -coverprofile=coverage.txt 
