# Student Result Processing System

## 1. Project Overview

The Student Result Processing System is a command-line application developed using Go. It accepts student details and marks for five subjects, then calculates the total, average, percentage, grade, and pass/fail status.

## 2. Objectives

- Develop a command-line application using Go.
- Use structs, arrays, slices, loops, functions, and packages.
- Separate student data and result-processing logic into modules.
- Validate student details and marks.
- Use Git and GitHub for version control.

## 3. Technologies Used

- Programming Language: Go
- IDE: Visual Studio Code
- Version Control: Git
- Repository Hosting: GitHub

## 4. Project Structure

- `main.go` — accepts input and displays results.
- `models/student.go` — defines the Student structure.
- `result/processor.go` — processes student results.
- `go.mod` — defines the Go module.
- `README.md` — project documentation.

## 5. Features

- Processes multiple students in one run.
- Accepts marks for five subjects.
- Validates marks between 0 and 100.
- Calculates total, average, and percentage.
- Assigns grades based on percentage.
- Checks pass/fail status using a minimum mark of 35 in every subject.

## 6. Grade Criteria

| Percentage | Grade |
|---|---|
| 90–100 | A+ |
| 80–89.99 | A |
| 70–79.99 | B |
| 60–69.99 | C |
| 50–59.99 | D |
| Below 50 | F |

A student fails if any subject mark is below 35.

## 7. How to Run

1. Install Go and Git.
2. Open the project folder in VS Code.
3. Open the terminal in the project directory.
4. Run `go run .`.
5. Enter the number of students, roll number, name, and five subject marks.

## 8. Testing

A successful test produced a total of 457 out of 500, an average of 91.40, a percentage of 91.40%, grade A+, and PASS status.

An additional test should check that a student with any subject mark below 35 receives FAIL status.

## 9. Conclusion

The project demonstrates modular programming in Go and basic student result processing. Git and GitHub are used to track development changes and maintain the project source code.
