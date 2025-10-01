# ESEP Grade Calculator

This library is a simple utility to calculate your grades based on weighted averages of assignments, exams, and essays.

Grading Scale:
- A: 90%+
- B: 80-89%
- C: 70-79%
- D: 60-69%
- F: 0-59%

Current Weights:
- Assignments: 50%
- Exams: 35%
- Essays: 15%

Runtime requirements:
Golang 1.24+

Installation:
```
cd grade-calculator/
go install
go version // verify Go installation
```

Usage:
```
// Initialize grade calculator
gradeCalculator := NewGradeCalculator()

// Add grades
gradeCalculator.AddGrade("Assignment Title", 80, Assignment)
gradeCalculator.AddGrade("Exam Title", 81, Exam)
gradeCalculator.AddGrade("Essay Title", 85, Essay)

// Compute Final Grade
finalGrade = gradeCalculator.GetFinalGrade()
```

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

Resources:
[Go Documentation](https://go.dev/doc/)