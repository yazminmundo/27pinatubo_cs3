# Activity 2: Code Quality Assessment

Group Members:
- 25 Kristielle Garcia
- 26 Kzyra Gumabon
- 27 Yazmin Mundo

Section : 9 - Pinatubo
08/14/16

# Answers

## 1. Efficiency
Which algorithm is faster when the list of numbers is very large? Why?

- Pseudocode 1 is quicker when it comes to larger lists of numbers because it only uses one loop.

Checklist:
                       Pseudocode 1                                             PseudoCode 2
   one loop - Does the algorithm use one loop or two nested loops?       two nested loops - Does the algorithm use one loop or two nested loops?

   no - Does the algorithm repeat work unnecessarily?                    yes - Does the algorithm repeat work unnecessarily?

pseudocode 1 -  Which algorithm finishes in fewer steps?                              Which algorithm finishes in fewer steps?


## 2. Readability
Which algorithm is easier to understand at first glance? What makes it clearer?

- Again, Pseudocode 1 is easier to understand and work with when dealing with maximums. Again, it only has one loop, a simple if-condition,
 and is consistent with its working sequence, which makes it easier to absorb. 

Checklist:
                     Pseudocode 1                                             PseudoCode 2
   yes - Are variable names meaningful (e.g., max vs. bigger)?       not really - Are variable names meaningful (e.g., max vs. bigger)?

   simple - Is the logic simple or complicated?                      complicated - Is the logic simple or complicated?

   yes - Are there fewer lines of code?                              no - Are there fewer lines of code?


## 3. Maintainability
If you had to add a new feature (like finding both max and min), which algorithm would be easier to update? Why?

- Pseudocode 1 would be easier to update because of its straightfoward program. You can easily add a new variable (for example one for min) since the
  maximum value is stored separately in another variable. Complex functionalities in this pseudocode is avoided and less chances of errors when updating.

Checklist:
                     Pseudocode 1                                             PseudoCode 2
   yes - Is the structure straightforward?                      no - Is the structure straightforward?

   no - Would adding new steps break the code easily?           yes - Would adding new steps break the code easily?

   yes - Is there less chance of errors when updating?          no - Is there less chance of errors when updating?

## 4. Testability
Which algorithm is easier to test with different inputs? Why?

- Pseudocode 1 is easier to test because again, of its simple and straightforward structure.

Checklist:
                     Pseudocode 1                                             PseudoCode 2
   yes - Can you test with small lists easily?                      yes, but it's slightly difficult - Can you test with small lists easily?

   yes - Does the algorithm have fewer conditions to check?         no - Does the algorithm have fewer conditions to check?

   yes - Is the output predictable and clear?                       yes, but requires more steps - Is the output predictable and clear?

## 5. Security
Imagine the input list comes from a user. What should the algorithm check to avoid errors or misuse?

- The algorithim should examine its ability to check if the list is empty, handle invalid inputs, and avoid crashing. But in the pseudocode, it fails to do
any of these, so we suggest fixing the program.

Checklist:
                     Pseudocode 1                                             PseudoCode 2
   no - Does the algorithm check if the list is empty?                      no - Does the algorithm check if the list is empty?

   no - Does it handle invalid inputs (like letters instead of numbers)?    no - Does it handle invalid inputs (like letters instead of numbers)?

   no - Does it avoid crashing when inputs are unusual?                     no - Does it avoid crashing when inputs are unusual?

## 6. Final Answer
Based on your answers from 1 to 5, which one is the better algorithm that you will use to solve the problem of finding the highest number? 
Why? Summarize your answer

- Based on our answers, Pseudocode 1 is in favor because it has a simpler, more efficient, readable, maintainable, and testable algorithm. It avoids

  
