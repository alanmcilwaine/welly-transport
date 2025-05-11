# Heuristic Evaluation 
Evaluator Name: Sergio

## Top Recommendations

- Add brief text labels next to icons in the quick menu to ensure all users can navigate confidently.
- Relocate placeholder text labels in form fields to above or outside the fields to improve clarity and reduce confusion.
- Provide subtle tooltips or onboarding hints to help new users understand interactive elements such as dropdowns or filters.

###  Severity Rating 

0 = I don't agree that this is a usability problem at all  
1 = Cosmetic problem only: fix if time is available  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, given high priority  
4 = Usability catastrophe: fix this before product can be released  

| Heuristic                                                    | Violation | Recommendation | Severity |
| ------------------------------------------------------------ | --------- | -------------- | -------- |
| 1. Visibility of system status - Always keep users informed about what is going on, through appropriate feedback within reasonable time. | No clear implementation of dynamic feedback for actions like search or submission. | Ensure that system status (e.g., loading indicators, success/failure confirmations) is clearly visible in interactive screens. | 1 |
| 2. Match between system and the real world - Follow real-world conventions, making information appear in a natural and logical order. | Text field placeholders are used as labels, which disappear on click, diverging from standard form design. | Move labels outside the input fields to improve clarity and reduce potential for confusion. | 1 |
| 3. User control and freedom - Users should leave the unwanted state without having to go through an extended dialogue. undo and redo. | No undo or cancel actions shown in wireframes for actions like route planning or form input. | Consider including clear back or cancel options in all input-heavy screens. | 1 |
| 4. Consistency and standards - Users should not have to wonder whether different words, situations, or actions mean the same thing. | Icon-only quick menu could lead to uncertainty for users unfamiliar with the icons. | Pair icons with labels or offer brief tooltips for clarity. | 1 |
| 5. Error prevention - Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. | Text input fields lack clear labeling and validation cues. | Use explicit labels and consider inline validation to reduce mistakes. | 1 |
| 6. Recognition rather than recall - Minimize the user's memory load by making objects, actions, and options visible. | Users must recall the meaning of icons and may not immediately recognize their purpose. | Add brief labels or descriptions to commonly used icons and controls. | 1 |
| 7. Flexibility and efficiency of use - Accelerators. Allow users to tailor frequent actions. | Quick menu allows fast navigation, but lacks advanced user options like recent searches or saved filters. | Consider adding optional shortcuts or personalization features in future iterations. | 1 |
| 8. Aesthetic and minimalist design - Dialogues should not contain information which is irrelevant or rarely needed. | UI is minimal, but heavy reliance on icons might limit clarity for some users. | Maintain minimalism but enhance communication through light labeling or onboarding. | 1 |
| 9. Help users recognize, diagnose, and recover from errors - Error messaging not visible in wireframes. | Add helpful, friendly messages for input errors, failed actions, or empty results. | 1 |
| 10. Help and documentation - Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. | No help features or onboarding are visible in the current design. | Consider adding a brief intro screen or tooltips to assist first-time users. | 1 |
