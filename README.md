# StaffDataSimulator-v1
JavaScript program, that generates random employee data based on certain input parameters.


Code is a JavaScript program that generates random employee data based on certain input parameters. Let's break down what the code does:

Input Configuration:

The dtoIn object is used to configure the generation of employee data. It includes the total count of employees (count) and age range (age with min and max values).
Data Arrays:

Lists of male and female names, surnames, genders, and workload values are defined to be used in generating random employee data.
Random Data Generation Functions:

getRandomElement: A function to randomly select an element from an array.
getRandomDate: A function to generate a random birthdate within the specified age range.
Employee Data Generation:

The main function generates random employee data based on the input configuration. For each employee, it randomly determines gender, selects a name and surname, generates a birthdate, and assigns a random workload.
Data Analysis Functions:

generateEmployeeData: Calls the main function to generate employee data based on the input configuration.
getEmployeeStatistics: Analyzes the generated employee data, calculating statistics such as average age, age range, median age, median workload, and more.
Main Execution:

The mainFunction function combines data generation and analysis, calling generateEmployeeData and then getEmployeeStatistics.
Output:

The final result, containing various statistics about the generated employee data, is stored in the dtoOut object and printed to the console.
Third-Party Libraries:

The code uses two external libraries: lodash for additional utility functions (although there is an issue with the _.median function) and simple-statistics for calculating statistical measures.
