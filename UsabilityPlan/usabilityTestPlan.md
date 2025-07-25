# Testing Overview:
The following document describes the plan for usability testing of the prototype of the Team 12 Transport App.

These are the objectives of usability testing:
* Determine a first-time user performance and satisfaction with the application; allowing
comparison to be done on later usability testing.
* Identify potential errors in the application and design concerns to be altered in later
versions.
* Determine user satisfaction with the application.

These objectives will be completed through analysis of data from test participants, including participant feedback and interaction with the system. Specific metrics have been set out in this test plan to standardise data obtained for test participants. 

The intended user base of Team 12's Transport App are daily commuters in the Wellington region. Participants in testing consist of 4 groups of 6 students (expected) studying SWEN303 at Victoria University of Wellington.

# Materials
* Each participant will be instructed to sign a consent form. All of the consent forms will be stored under ./ConsentForms.  
* Each participant will test the prototype on ECS lab computers.

# Methodology:
There will be 6-12 test users, who will carry out testing in-person in computer labs CO238 and CO234. Testing will be carried out on a Figma prototype of the application.

## Participants
Test Subjects will be selected from other groups from Group C, working on similar projects. For this reason, they will be more familiar than the average first time user with the software engineering involved in creating this kind of system. As a result, we expect them to be more proficient at the tasks we present them with than the average user would be. This bias should be accounted for when reviewing the test results. Each Test Subject will be asked to complete 6 tasks, giving feedback on their experience after each one. When all tasks are complete, they will fill out a Google form with their overall experience.

## Training
Test Subjects will be briefly shown the 4 main pages of the application, and then given a brief explanation of the app's purpose and the functions it can perform. This information should be just enough to give the Subject some idea of what is expected of them, while not telling them how to solve any task.

## Procedure
Testing will take place at a specific ECS machine, ideally in a designated quiet corner of a lab. Before testing, the Experimenter will prepare the Figma prototype and response form in a browser window on this machine, ensuring that both are reset. The Test Subject will be guided to the designated machine by the Experimenter, where the Recorder will be seated to one side. The Experimenter will introduce the test according to the script, ensuring the Test Subject has given their consent.

For each task, the Experimenter will first explain the task. Care must be taken to **not give any further information on the task through gesture or tone of voice**, beyond what is written in the plan. Some tasks will include instructions, to emulate a more experienced user, and others will have no instructions. Once the Test Subject has heard and understood each task, they will attempt to complete it. When they are confident they have completed (or failed to complete) the task, the Experimenter will ask for their thoughts on the experience. These two steps will have **no input or direction by the Experimenter or Recorder**. The prototype will be reset after each task.

The Recorder will record any potentially useful information about the Experimenter's explanation, the Subject's attempt at the task (actions performed, errors encountered, time taken), and the Subject's response on completion. This information will be stored for later analysis, and is not to be shared with the Experimenter or Test Subject before all testing is over. After all tasks are complete, the Test Subject will be prompted to fill out the response form with any feedback on the test as a whole. This information will be recorded alongside the Recorder's notes.

# The Script
## Intro
**Note-Taker will create a GitLab issue for the subject, titled with the subject name "Student: #####", Label="Usability Test", and the description is our roles for this test, Note-Taker: ####, Experimenter: ####.**

E: Welcome to the usability testing of Team 12's transport app. In this session, we will be recording your interactions and feedback while testing the prototype.

**Experimenter hands subject the consent script**

E: Do you provide consent?

**Experimenter makes sure subject has signed the script**

E: The purpose of our app is to organise and plan a transport route for a diverse array of commuters. Users will be able to plan a route between two stops and select their preferred route. These can be saved, and viewed under widgets on the home screen. Alongside route planning, users can: 
* Customise their home screen with an array of widgets,
* View train and bus alerts in the Wellington region,
* View timetables of specific stops or services,
* And seek help through the settings.
E: The main goals of our app is to:
* Improve customisability for each user,
* Minimise the amount of taps to get required information,
* And undo from multiple states.
## Your Tasks
E: In order to make the testing process as simple as possible, we'll get you to perform a short set of tasks on our Figma prototype. At the end of each task, please note any difficulties you had with the task. When you've finished the task set, please fill out the Google form. We’ve tried to make the form as concise as possible, so that it won’t take too long. That being said, we’d really appreciate as much detail in the feedback as you’re comfortable giving us. We have included multiple tasks, some with lots of help and some with less. We’ve done this to simulate the contrast in experience between that of an ideal user flow (with instructions) compared to that of a new user (without instructions). Please comment on any differences between the two.

E: Here is the link to our prototype.
**Experimenter will then send the subject the link to the prototype**<br>
E: Once the prototype has loaded, let me know, and we can begin going though the tasks.
**Experimenter will then proceed to ask the user to complete the tasks detailed below in order:**<br>

**Once finished**<br>
E: Thank you for going through this usability test. Can you please fill out this form to give us feedback on your experience.**
**Experimenter will then send the subject the link to the form**

## Scenarios:
If the subject is taking too long to figure out how to do a task, Experimenter will give them a hint and Note-taker will note this in the description of the GitLab issue.
If the subject can't figure out how to do a task even with a hint, move on. The note-taker will take a note of this.
Note-taker will take note of:
* Any difficulties.
* Any time they've taken too long to figure out a task, and then the hint the experimenter gave them.
* Any questions the subject asks.
# Roles
In our group of 6, we paired up into 2 to do the Experimenting and Recording, the roles in these pairs switch after each testing user.. These pairs are:
Ming and Alan
Jac and Sergio
Alison and Luigi. 

** Roles outside of the day **
## Facilitator 
* Contacts the test group
* Schedules times and locations for testing
* Provides additional information on request
## Analyst
* Performs analysis on the data after testing has been completed
* Helps suggest improvements based on trends in subject answers

**Roles on the day**
## Experimenter
* Talks to the subject and walks through the script.
* Walks the subject through tasks.
## Recorder
* Records notes from the test subjects
* Records any interaction between the testing organisers and the test subjects.
## Test Subject
* Completes the tasks given by the Facilitator
* Inputs answers to the questions asked
* Submits a form

# Tasks
**Task 1: Home page**
 - On the Home page, press the plus icon. Then click on one of the buttons that appear to add a new widget to the home screen. Repeat the process to add another widget. When there are three widgets, scroll to see the bottommost widget. Now remove a widget with the cross button. 
 - Please describe any times you were lost during this task in the feedback survey. 

**Task 2: Route Planner page**
 - Navigate to the Route Planner page with the button labelled “Plan”. Set a starting point and then an ending point. Highlight a result on the map. Try to save a result as a Favourite. 
 - Navigate back to the starting page for the Route Planner. Search with only a ending point and check the results.
 - Please describe any times you were lost during this task in the feedback survey. 

**Task 3: Services page**
 - Navigate to the Services page. Search for the bus stops and then go to a bus timetable. Then go back and do the same for the train stations and then go to a train timetable. Then go back and use a favourited or suggested service to shortcut to its timetable.
 - Please describe any times you were lost during this task in the feedback survey. 

**Task 4: Alerts page**
 - Navigate to the Alerts page. Find an alert for the Hutt Valley line. If you wanted to view alerts more easily, what could you do to the home page?
 - Please describe any times you were lost during this task in the feedback survey. 

**Task 5: Settings page**
 - Where would you try to find help in this prototype?
 - Navigate to the Settings page. Take a look at each menu within this page. Change some settings for each menu. Consider the settings that would be best for you.
 - Please describe any times you were lost during this task in the feedback survey. 



# Metrics

Our team decided to use the System Usability Scale (SUS) as our testing method. SUS is known to be quick to implement into testing methodologies, easy to understand for survey takers, and versatile for any use case. [This website](https://measuringu.com/sus/) gave us a better understanding on how SUS can be implemented in a feedback forum and how using it can benefit any team, noting specifically about how SUS measures an items usability and ease of learning, as well as SUS's reliability to provide results from responses.

# Usability Goals

The mobile app should achieve an average System Usability Scale (SUS) score of at least 68, indicating acceptable usability, with an optimal target of 75 or higher to reflect good to excellent usability [source](https://measuringu.com/sus/). This score should be measured through usability testing with representative users performing key travel-related tasks, such as planning a route, checking arrival times, and navigating through the app.

# Problem Severity
This section helps to prioritise issues encountered during usability testing of our transport application. Problems are classified based on their impact, frequency, and the importance of the task in which they occur. Since this test is being conducted on a prototype version, some features may be incomplete or not available. We will only consider as problems those issues that negatively impact the user experience when performing the tasks included in the test script.  
Level of the Issue:
-	Minor – A low-impact issue that causes a small inconvenience or visual inconsistency. It occurs infrequently and does not affect the user’s ability to complete the task.
-	Moderate – A noticeable issue that affects usability and may confuse the user, but does not completely block task completion.
-	Major – A critical issue that prevents the user from completing a key function or makes the application unusable for its main purpose.  

# Data Collection and Analysis
**We are collecting data using the SUS metric. Each subject will be given a form to fill outlining:**
* 10 questions according to the SUS standard.
* Their favourite feature.
* Issues they had with the prototype.
**These will be analysed by:**
Creating a boxplot of each of the 10 questions from the form. We will then analyse the boxplot and find apparent issues of each part of the usability test.
