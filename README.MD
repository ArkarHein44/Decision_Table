## Decision Table 
A decision table is a graphic tool that identifies 
- the conditions in a problem and  
- the actions resulting from each unique set of conditions.   

> It is easy to use but it is time consuming to construct. 
> It can be used to check for ambiguity, redundancy and completeness of a description.  

| Title          | Rule Number     |
| :------------- | :-------------- |
| Condition Stub | Condition Entry |
| Action Stub    | Action Entry    |

### Decision table is divided into four sections 
- A list of all conditions 
- A list of all conditions that are possible based on combinations of conditions 
- A matrix that indicates condition combinations and  
- The corresponding actions that will occur for a specific combination 
Therefore, each column of the matrix may be interpreted as a processing rule. 

### Types of Decision Tables 
- Limited entry: Condition entry has ‘Y’ (Yes) ,’N’ (No) or ‘-’ Action entry has ‘X’ (cross mark)  or blank 
- Extended entry: Various conditions are specified in the condition entry. Description of an action is given in the action required  
- Mixed entry: a mixture of limited & extended entry  

### Steps in Creating a Decision Table 
1. Identify all the conditions, or variables, in the specification. Identify all the values that each variable can take on. 
2. Calculate the number of combinations of conditions (i.e. 2N) 
3. Identify each possible action that is called for in the specification. 
4. Create an empty decision table by listing conditions and actions on the left hand side and drawing appropriate number of columns for the rules. 
5. List the combinations of conditions, one for each vertical column. 
6. Examine each vertical column (rule) and identify appropriate action (s) to be taken. 
7. Identify any omissions, contradictions or ambiguities in the specification. 
8. Discuss omissions, contradictions and ambiguities with the user. 

### Example of a limited entry decision table 
| Is order>$5000?  | Y | Y | N | N |
| :--------------- |:-:|:-:|:-:|:-:|
| Is credut OK?    | Y | N | Y | N |
| Give 3% discount |   |   | X |   |
| Give 5% discount | X |   |   |   |
| See supervisor   |   | X |   | X |

- Conditon Entry has ‘Y’ (Yes) ,’N’ (No) or ‘-’ Action entry has ‘X’ (cross mark)  or blank.

### Example of a extended entry decision table
| Stock              || S   | S   | S   | S    | T    | T   |
| :----------------- ||:---:|:---:|:---:|:----:|:----:|:---:|
| Customer           || W   | R   | W   | A    | W    | R   |
| Order Value($1000) ||>=50 | >50 | 20< | >=50 | 20<= | 50< |
|                    ||     |     |     |      |      |     |
| %Discount          || 22  | 20  | 15  | 25   | 18   | 20  |
| Carriage           || Y   | N   | N   | N    | Y    | N   |
| Terms              || N20 | N20 | P5% | N20  | P5%  | N30 |

- Stock: S=Socks, T=T shirt 
- Customer: R=Retailer, W=Wholesaler, A=Agent 
- Terms: N20 = 20 days payment,  
- P5% = 5% initially payment  