#automatic-timetable-generator (team name :Triple stack)
----------------------------------------------------------------------------------------------------------------------------
### An intelligent timetable generator that generates University timetable using `Genetic Algorithm`

#### team members :
1.[Deeksha.c] (https://github.com/Deeksha11c) <br>
2.[Chaitra.P] (https://github.com/Cha-itraP) <br>
3.[Charvita Rao Pavar] (https://github.com/charvita )<br>
  A wrorking version of the prototype:- ['automatic-timetable-generator'] 
 #### Dependencies:
 1. python3.6 or above
 2. Django2.0 or above
 
#### Run on your local machine by:
* `git clone https://github.com/Deeksha11c/automatic-timetable-generator/`
* `cd M1`
* `python manage.py runserver`
* then go to port `http://127.0.0.1:8000/automatic-timetable-generation/` to run the local server

#### About the project:
project uses genetic algorithm to satisfy the constraints related to Timetable scheduling. The program satisfies the following constraints:- 

| Hard Constraints                                  | Soft Constraints                                     |
| --------------------------------------------------|:----------------------------------------------------:|
| Unique class timing                               | classes are alloted according to section requirements|
| Course.students <= room.seating capacity          | All courses are according to their department        |
| Two classes dont have same room                   | Even distribution of course in a section per week    |
| Class timing for each teacher is unique           |
| Teachers are allocated to their course accordingly|


