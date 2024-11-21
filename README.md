
 Group Project: Personality Quiz

Welcome to our collaborative Java project, Group-Project-personality-quiz! This project aims to create a personality quiz application with a user-friendly interface, robust core logic, and accurate result analysis.

---

 Project Overview

Our application will:
1. Present users with a series of personality-based questions.
2. Calculate and display results based on their answers.
3. Provide an engaging and seamless user experience.

---

 Team Members and Roles

 1. Adam (Team Leader)
   - Oversee the entire project and ensure timely progress.
   - Manage the GitHub repository (branches, merges, pull requests).
   - Handle integration of all components and final testing/debugging.
   - Develop the result analysis and tie together UI and core logic.

 2. Juliana
   - Design and develop the user interface (UI) for the application.
   - Create the main menu, question screens, and result display.
   - Implement input validation for user interactions.
   - Ensure the UI integrates smoothly with the back-end.

 3. Daniel
   - Implement the core logic and data handling for the quiz.
   - Develop a scoring system to calculate results based on answers.
   - Create methods for storing and retrieving questions, answers, and results.
   - Handle data persistence (e.g., saving quiz progress).

---

 Tasks Breakdown

 Adam (Leader)
- Set up the GitHub repository with branches for each member:
  - `frontend` (Juliana)
  - `backend` (Daniel)
  - `integration` (Adam)
- Write the `Main` class to integrate the UI and quiz logic.
- Implement the result analyzer to display personality results.
- Perform final testing and debugging.

 Juliana (UI Developer)
- Design a user-friendly interface:
  - Create methods for:
    - Main menu.
    - Question/answer input screen.
    - Result display.
  - Add input validation to prevent errors.
- Work with Adam to integrate the UI with the back-end logic.

 Daniel (Core Logic Developer)
- Create classes to handle:
  - Quiz questions and answers.
  - Scoring logic.
  - Data persistence for results and quiz progress.
- Write unit tests to validate the logic.

---

 Folder Structure Example

```
Group-Project-personality-quiz/
│
├── src/
│   ├── main/
│   │   ├── Main.java
│   │   ├── QuizLogic.java
│   │   ├── ResultAnalyzer.java
│   │   ├── UI/
│   │   │   ├── Menu.java
│   │   │   ├── QuestionScreen.java
│   │   │   ├── ResultScreen.java
│   ├── test/
│   │   ├── QuizLogicTest.java
│   │   ├── UITest.java
│
├── data/
│   ├── questions.json
│   ├── results.json
│
├── README.md
```
