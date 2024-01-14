# Quizzy
This is a custom academic quiz platform for an arbitary school where instructors/teachers can set quizzes to be attempted by their students. This repo will contain the API implementation for this platform.

## Constraints
- An INSTRUCTOR instructs 1 or more COURSEs and a COURSE can be instructed by at least 1 INSTRUCTOR.
- An INSTRUCTOR can set 0 or more QUIZ and QUESTIONs. A QUIZ and a QUESTION can be set by only 1 INSTRUCTOR.
- A QUIZ can contain many QUESTIONs. A QUESTION can only be part of one QUIZ.
- A STUDENT can take many COURSEs and a COURSE can be taken by many STUDENTs.
- A STUDENT can attempt 0 or more QUESTIONs and QUIZzes. A QUIZ and QUESTION can be attempted by 1 or more STUDENTs
- A MULTI-CHOICE QUESTION can have multiple OPTIONs. An OPTION can only belong to one MULTI-CHOICE QUESTION
- A QUIZ can be under 1 or more TOPICs. A TOPIC can have 0 or more QUIZzes.
- A QUIZ can be under 1 COURSE. A COURSE can have multiple QUIZzes.
- A COURSE can include 1 or more TOPICs. A TOPIC can be under only 1 COURSE

## E-R Diagram
![image](https://github.com/streetCoderr/Quizzy/assets/98380817/4c1fc51a-d11b-4d81-bfc0-c55b7ba2c117)
