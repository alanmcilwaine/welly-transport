# Heuristic Evaluation 
Evaluator Name: Sergio

## Top Recommendations

- Replace the dropdown for selecting bus routes with a searchable input to help users find services faster, especially when dealing with many options.
- Slightly reduce the number of moving elements on the map screen to prevent users from feeling overwhelmed.
- Consider adding a short onboarding screen or tooltips to introduce key features like the map and starred routes.

###  Severity Rating 

0 = I don't agree that this is a usability problem at all  
1 = Cosmetic problem only: fix if time is available  
2 = Minor usability problem: fixing this should be given low priority  
3 = Major usability problem: important to fix, given high priority  
4 = Usability catastrophe: fix this before product can be released  

| Heuristic                                                    | Violation | Recommendation | Severity |
| ------------------------------------------------------------ | --------- | -------------- | -------- |
| 1. Visibility of system status - Always keep users informed about what is going on, through appropriate feedback within reasonable time. | The app offers real-time updates on the map, but with many moving icons, the visual feedback could become hard to interpret at a glance. | Ensure map elements (e.g., moving buses) are clear and not overly dense. Consider simplifying or grouping elements for clarity. | 1 |
| 2. Match between system and the real world - Follow real-world conventions, making information appear in a natural and logical order. | The timetable page closely resembles real-world transit layouts, making it intuitive and familiar. | No changes needed. | 0 |
| 3. User control and freedom - Users should leave the unwanted state without having to go through an extended dialogue. undo and redo. | The navigation bar allows free switching between pages, but there is no indication of undo/cancel for actions like filtering or selection. | Where applicable, consider offering a back or cancel button on multi-step actions or filters. | 1 |
| 4. Consistency and standards - Users should not have to wonder whether different words, situations, or actions mean the same thing. | Icons and interface language appear consistent across all screens, making it easy to learn and navigate. | No changes needed. | 0 |
| 5. Error prevention - Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. | The dropdown for route selection could result in accidental choices or user frustration due to long lists. | Replace the dropdown with a searchable field to help users easily find specific services. | 1 |
| 6. Recognition rather than recall - Minimize the user's memory load by making objects, actions, and options visible. | The current dropdown requires users to remember specific route names or numbers. | Switch to a searchable input field to reduce reliance on memory. | 1 |
| 7. Flexibility and efficiency of use - Accelerators. Allow users to tailor frequent actions. | Starred routes and quick access features support efficient usage. However, there's no sign of power-user features like keyboard shortcuts or filters. | Maintain starred route access and consider adding optional personalization in the future. | 1 |
| 8. Aesthetic and minimalist design - Dialogues should not contain information which is irrelevant or rarely needed. | The app layout is clean and minimal, but the map screen might become visually cluttered due to dynamic movement. | Slightly simplify the map interface or provide toggles to control visibility of layers. | 1 |
| 9. Help users recognize, diagnose, and recover from errors - Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution. | Error states or messages were not visible in the wireframes. | Add clear, friendly error messages for things like failed searches or unavailable routes. | 1 |
| 10. Help and documentation - Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. | No onboarding, tooltips, or help section was shown. | Consider adding a brief help overlay or tip system for new users to understand the app’s navigation and features. | 3 |
