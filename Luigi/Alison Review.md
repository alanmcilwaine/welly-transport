# Heuristic Evaluation 
Evaluator Name: Alison

Evaluating: Luigi

## Top Recommendations

- Add a more traditional navigation bar, either along the top of the screen, or at the bottom to replace the quick menu (which could then be swapped back in as an accessibility setting, as it could be preferred by some users).
- Include only top-level information on alerts (eg. severity, services affected), further information accessible by selecting that alert. Similar fix for route planning options, settings groups, etc.
- Add help page to top bar, alongside profile and settings. This is a position where new users will look for it first.

###  Severity Rating 

0 = I don't agree that this is a usability problem at all 

1 = Cosmetic problem only: fix if time is available 

2 = Minor usability problem: fixing this should be given low priority 

3 = Major usability problem: important to fix, given high priority 

4 = Usability catastrophe: fix this before product can be released 


| Heuristic | Violation | Recommendation | Severity |
|---|---|---|---|
| 1. Visibility of system status - Always keep users informed about what is going on, through appropriate feedback within reasonable time. | This design does a good job of showing what state the user is in through the consistent use of coloured icons on the bottom bar and in menus. | Possibly investigate if the difference in colour is effective for visually impaired users. | 1 |
| 2. Match between system and the real world - Follow real-world conventions, making information appear in a natural and logical order. | The bottom bar could be better utilised to cover more use cases; regular commuters or casual local users may be confused by their de-emphasis in this layout and think the app will not be useful to them. | Move notifications icon to the top right for visibility, and add icons to the bottom bar for maps and saved trips/destinations (currently only accessible from homepage). | 3 |
| 3. User control and freedom - Users should leave the unwanted state without having to go through an extended dialogue. undo and redo. | There is no way to return to a previous state, unless that state is one of the four main pages in the bottom bar (eg. to return to the results from a search). | Add "back" button to sub-pages when relevant. | 2 |
| 4. Consistency and standards - Users should not have to wonder whether different words, situations, or actions mean the same thing. | No issue, terminology and imagery is used consistently. | - | 0 |
| 5. Error prevention - Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. | Some options may be selected by mistake - for example, the logout button being so close to the change language button, and the "my tickets" button being very close to the right side of the search bar. | Space icons that the user might not want to interact with further apart. | 2 |
| 6. Recognition rather than recall - Minimize the user's memory load by making objects, actions, and options visible. | The settings page may be difficult to navigate for first-time users. | Add icons to settings submenus, and/or group similar submenus together visually. | 1 |
| 7. Flexibility and efficiency of use - Accelerators. Allow users to tailor frequent actions. | Implemented well. Trips and destinations can be saved and accessed easily, and in-depth options allow tailoring results to find the best option quickly. | - | 0 |
| 8. Aesthetic and minimalist design - Dialogues should not contain information which is irrelevant or rarely needed. | As above, there is a large focus on tourist use, which does mean a large part of the UI will not be relevant to most users. For tourist users, however, the aesthetic design is attractive and understandable. | - | 0 |
| 9. Help users recognize, diagnose, and recover from errors - Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution. | No issue here that I can see. | - | 0 |
| 10. Help and documentation - Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. | The settings panel is very in-depth, but it is missing help and documentation features. | Add a helpdesk and FAQ section to a clearly visible position in the settings panel. | 3 |