### Decision Table Exercise 
A university has the following criteria for deciding whether to admit students to the graduate programme: 
- Admit a student who has undergraduate grade of B or better, has test scores on the admission test of over 550, and has a grade average of B or better for the past two years.  
- Also admit if the overall grade average is less than B but the last two years average is B or better and the test score is over 550.  

### Decision Table Exercise 
- Admit on probation if the overall and 2-year grade average are B or better but test score is 550 or less.  
- Admit on probation if overall grades are B or better and tests score is above 550 but last 2 years are below B.  
- Also admit on probation if overall grade are less than B average and test score is 550 or less, but grades for past two years are better.  
- Refuse to admit all others. 

---

### Prepare a limited entry decision table for the above procedure.  
#### Decision Table: Solution  

- Condition Stubs: 
    - Undergraduate grade of B or better  
    - Test score of over 550  
    - Grade average of B or better past 2 years 
    - Test score of 550 or less  
    - Grade less than B last 2 years  
    - Overall grade average less than B  

- Action Stubs: 
    - Admit  
    - Admit on probation  
    - Do not admit  

- Second step is to combine conditions  
    - Undergraduate grade of B or better  
    - Test score of over 550  
    - Grade average of B or better past 2 years  

> Note: Condition 4,5,6 are the negative form of Condition 1,2,3. So, we can combine these conditions. 

- Third step is to prepare Y & N for all possible combinations of conditions  
- Then for each condition, mark the action(s) to be taken with ‘X’  

|    | Admission Procedure                |-| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|:--:| :--------------------------------- |-|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| 1  | Undergraduate Grade of B or better |-| Y | Y | Y | Y | N | N | N | N |
| 2  | Test score over 550                |-| Y | Y | N | N | Y | Y | N | N |
| 3  | Grade of B or better past 2 years  |-| Y | N | Y | N | Y | N | Y | N |
| -  | -                                  |-| - | - | - | - | - | - | - | - |
| 1  | Admin to Program                   |-| X |   |   |   | X |   |   |   |
| 2  | Admin on Probation                 |-|   | X | X |   |   |   | X |   |
| 3  | Do not Admit                       |-|   |   |   | X |   | X |   | X |

### Redundancy Check
The existence of two or more rules with different combination of conditions leading to same action
|   |-| N | Y |
|:-:|-|:-:|:-:|
|   |-| Y | Y |
|   |-| N | N |
| - |-| - | - |
|   |-| X | X |

> Note : These two rules can be combined in one:

|-|
|-|
|Y|
|N|