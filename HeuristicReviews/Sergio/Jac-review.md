# Heuristic Evaluation 
Evaluator Name: Jac

## Top Recommendations

- Implement error feedback

###  Severity Rating 

0 = I don't agree that this is a usability problem at all 

1 = Cosmetic problem only: fix if time is available 

2 = Minor usability problem: fixing this should be given low priority 

3 = Major usability problem: important to fix, given high priority 

4 = Usability catastrophe: fix this before product can be released 


| Heuristic                                                    | Violation | Recommendation | Severity |
| ------------------------------------------------------------ | --------- | -------------- | -------- |
| 1. Visibility of system status - Always keep users informed about what is going on, through appropriate feedback within reasonable time. | User interaction lacks immediate response. | Implement a loading wheel-like feature. | 2 |
| 2. Match between system and the real world - Follow real-world conventions, making information appear in a natural and logical order. | N/A. Map mirrors real-world conventions well. | N/A | 0 |
| 3. User control and freedom - Users should leave the unwanted state without having to go through an extended dialogue. undo and redo. | N/A. Persistant navigation bar allows quick access back to any page. | N/A | 0 |
| 4. Consistency and standards - Users should not have to wonder whether different words, situations, or actions mean the same thing. | N/A. Consistent use of language. | N/A | 0 |
| 5. Error prevention - Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. | Lack of response for bad queries. | Inform the user when a search would return no results before the search happens. | 2 |
| 6. Recognition rather than recall - Minimize the user's memory load by making objects, actions, and options visible. | N/A. Navigation bar informs user of current page. | N/A | 0 |
| 7. Flexibility and efficiency of use - Accelerators. Allow users to tailor frequent actions. | N/A. User is able to save trips. | N/A | 0 |
| 8. Aesthetic and minimalist design - Dialogues should not contain information which is irrelevant or rarely needed. | N/A. Design relies on icons and visual representations of information as well as text. | N/A | 0 |
| 9. Help users recognize, diagnose, and recover from errors - Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution. | No indication of errors shown. | Add a form of feedback to the user for when an error occurs. | 2 |
| 10. Help and documentation - Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. | N/A | N/A | 1 |