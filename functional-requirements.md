### Functional

Here are the main questions for which I need answers to capture some of the initial requirements for a software development project:

1. What is the business objective behind the requested functionality?
2. What basic functionality do you need for this part of the system?
3. What is the underlying goal of the requirement?
4. Is this particular design critical to the business goal, or would any design be equally effective?
5. How does it work today?
6. What specific steps do you go through to complete a task in the system?
7. What do you not like about the system today?
8. If X does not happen, then what should happen?
9. What do you want to have happen in the future?
10. Are there any known constraints from other systems or users?
11. What are the non-functional requirements that apply for each of the users, operating environments, and interfacing systems?
12. Keep drilling deeper with variations of “why?”

In order to formulate use cases, here are some questions that need to be answered:

1. Use case description
  * What is the actor’s goal?
  * What are the high level actions the actor will need to take to reach that goal?

2. Assumptions
  * What assumptions are we making when analyzing this use case?

3. Frequency of Use
  * How many times per minute, hour, or day will this use case be executed?

4. Actor
  * Who uses the system (what is their job)?
  * What other systems will interact with this system?
  * Who or what provides information to the system?
  * Who or what receives information from the system?

5. Trigger
  * What event causes this use case to happen?
  * What actor initiates this use case?

6. Preconditions
  * What conditions must be true before this use case can begin?
  * What state is the system in before this use case can begin?

7. Success End Conditions
  * What conditions must be true when the use case ends?
  * What state will the system be in at the end of the use case?

8. Main Steps
  * How does the actor interact with the system?
  * What does the system do at this step? (present options, display data, execute a process)?
  * What does the system do next?
  * What does the actor do next?
  * Is there part of this use case that is another use case called by multiple other use cases?

9. Alternative Courses
  * What possible error conditions exist at each step of the main scenario?
  * If X doesn’t happen, what should happen?
  * What are the interrupts that can happen at any time?
  * What is the “non-happy” path?
  * What other possible actions can the user take at each step?
  * If the user cancels out at any step, what should happen?

