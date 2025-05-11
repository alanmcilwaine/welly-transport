# Heuristic Evaluation 
Evaluator Name: Alison

Evaluating: Ming

Version 2, now with less detail!

## Top Recommendations

- Give the user more visible options for accessing information: Switching the date/direction of the timetable being viewed, accessing lines by selecting them on the map, etc.
- Settings/help: Replace the "profile" icon on the bottom bar with a "settings" icon, which could then have its own subpages for profile/account settings, general settings, and support/FAQ.
- Alerts for disruption to lines should be visible on the relevant timetable pages, and possibly also on the map screen.

###  Severity Rating 

0 = I don't agree that this is a usability problem at all 

1 = Cosmetic problem only: fix if time is available 

2 = Minor usability problem: fixing this should be given low priority 

3 = Major usability problem: important to fix, given high priority 

4 = Usability catastrophe: fix this before product can be released 


| Heuristic | Violation | Recommendation | Severity |
|---|---|---|---|
| 1. Visibility of system status - Always keep users informed about what is going on, through appropriate feedback within reasonable time. | The current page is not communicated very well, with the darkened icon on the bottom bar being the only indication. There is no displayed name for each page, and so each icon's purpose is non-obvious and must be learned. | Add a visible title to the top of each page, or labels to the bottom bar icons (ideally both!) | 2 |
| 2. Match between system and the real world - Follow real-world conventions, making information appear in a natural and logical order. | The app functions similarly to a directory of paper timetables, which likely makes it more user-friendly for less tech-savvy users. Information is presented in a way that feels logical. | - | 0 |
| 3. User control and freedom - Users should leave the unwanted state without having to go through an extended dialogue. undo and redo. | Implemented very well. Actions can be switched between quickly with the bottom bar, and a back button is available where one is appropriate. | - | 0 |
| 4. Consistency and standards - Users should not have to wonder whether different words, situations, or actions mean the same thing. | Some actions are unintuitive, such as selecting a bus bringing you to the line's full timetable. | Add intermediate steps to some actions (such as selecting a bus showing a panel with tracking info on that bus, which the user could then open the line's timetable from). | 2 |
| 5. Error prevention - Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. | User may miss disruptions to a line, if they navigate directly to that line's timetable without seeing the alert on the homepage. | Alerts for disruption to lines should be visible on the relevant timetable pages, and possibly also on the map screen. | 3 |
| 6. Recognition rather than recall - Minimize the user's memory load by making objects, actions, and options visible. | Some types of information, or options for accessing information, are unavailable to the user. | Give the user more visible options for accessing information: Switching the date/direction of the timetable being viewed, accessing lines by selecting them on the map, etc. | 4 |
| 7. Flexibility and efficiency of use - Accelerators. Allow users to tailor frequent actions. | Starred routes make for fast access for regular users, and the homepage showing warnings related to them is a nice touch. | - | 0 |
| 8. Aesthetic and minimalist design - Dialogues should not contain information which is irrelevant or rarely needed. | Excellent use of minimalist design, all information shown is useful and aesthetically well-presented. | - | 0 |
| 9. Help users recognize, diagnose, and recover from errors - Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution. | It is unclear how some situations would be presented to the user, for example the first-time main page (with no starred routes) or viewing a line's timetable when there are no more trips on that line for that day. | Explore options for how first-time use and edge case situations are presented to the user. | 1 |
| 10. Help and documentation - Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. | Settings and help are not available to the user, which is a major usability issue. | Replace the "profile" icon on the bottom bar with a "settings" icon, which could then have its own subpages for profile/account settings, general settings, and support/FAQ. | 4 |