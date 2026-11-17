# CGPA Calculator

A command-line C++ program that calculates a weighted CGPA from course grade points and credit hours.

For each course, enter a grade point on a 0–10 scale and its credit hours. The program computes the weighted average:

`sum(grade point × credits) / sum(credits)`

## Build and run
Requires a C++ compiler with C++11 support.

```bash
g++ -std=c++11 cgpa_calculator.cpp -o cgpa_calculator
./cgpa_calculator
```

On Windows, run `cgpa_calculator.exe` after compiling.

## Note
Enter a positive number of courses and a non-zero total of credit hours.
