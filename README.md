# OEC Infection Probability Calculator

This is a program for the Ontario Engineering Competition in programming that calculates the probabilities for students, teachers, and TAs at a certain school to be infected with the fake ZBY1 disease. It reads from an Excel file and stores the probabilities internally to be accessed via the terminal.


# Folders and files


## Objects

Contains data models for various parts of our application.

```ClassPeriod.py```  models a single class during one of the 4 periods through the day


```Directory.py``` models a structure mapping periods to classes


```ExtraCurricular.py``` models extracurricular activities in the school

```Lunch.py``` models a lunch period

```Student.py``` models a student and their classes, chance of infection

```Teacher.py``` models a teacher and the class they teach, chance of infection

```TeachingAssistant``` models a teacher's assistant and the classes they assist

## Functions
```__init__.py``` contains various helper functions

## constants
```__init__.py``` contains various constants used to calculate infection rate
''
## Main
```main.py``` run the program



# How to run
```
git clone git@github.com:Thomas-Oliv/OEC2021-TEAM-Csharp.git //clone code
python3 -m venv venv //create virtual environment
source venv/bin/activate //activate virtual environment
pip install -r requirements.txt //install dependencies
python3 main.py //run code

1. When running the application you will be prompted for a file. This should be the full path of the file. Optionally you can leave it blank to use the default file includedd with the repo.

2. You can then specify a person's name or type 'f' to export to excel. The location of this file will be in the same directory as the source file. Its name should be in the format of Results{INTEGER}.xlsx where {INTEGER} is a random integer.

3. at any point you can type 'e' to exit.
```
