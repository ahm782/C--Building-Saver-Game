# Cryptography-Based Rescue Game (C++ – First Semester Project)

This is a console-based game developed using C++ during the first semester of the Data Science program. The game introduces players to basic cryptographic techniques such as Caesar Cipher and character array reversal. The objective is to decrypt randomly generated words to prevent the destruction of fictional buildings. It serves as a foundational project to practice programming logic, user interaction, and modular design.

---

## Project Summary 

### Situation
In the first semester, students were tasked with creating a C++ project that demonstrated understanding of programming fundamentals such as loops, functions, arrays, and user input handling.

### Task
Develop a console-based application in C++ that challenges users to solve encryption puzzles under time and attempt constraints. The application must simulate a game scenario, include difficulty levels, and allow users to engage interactively with the logic.

### Action
- Implemented game logic for two cryptographic methods: Caesar Cipher and Reverse Word
- Used random generation to produce unpredictable challenges
- Introduced difficulty levels with varying attempt limits
- Created a modular design using multiple functions
- Simulated a game-like environment with real-time user input and result evaluation

### Result
- Successfully built a fully functional game using only core C++ concepts
- Demonstrated early understanding of algorithm design and control flow
- Shared on GitHub as part of an academic and professional portfolio
- Gained confidence in writing interactive console programs with clear structure

---
##  Project Impact

- Improved understanding of C++ syntax, arrays, loops, and functions
- Practiced algorithmic thinking through Caesar Cipher and array reversal challenges
- Built confidence in writing interactive, user-facing console applications
- Introduced concepts of randomness, state tracking, and gameplay design
- Demonstrated ability to complete and present a structured programming project early in the degree


## Features

- Two decryption modes:
  - Caesar Cipher (random shift values)
  - Reversed character arrays
- Difficulty levels: Easy, Intermediate, and Hard
- Building-based missions: Hospital, School, and Restaurant
- Random word generation using standard ASCII character ranges
- Win/Loss logic based on number of successful rescues
- Replayability with random challenges each time

---

## Technologies Used

- **Language:** C++
- **Topics Practiced:**
  - Arrays and character strings
  - Functions and modular structure
  - Conditional logic and loops
  - Random number generation
  - Pointers (used in reversal logic)

---

##  Future To-Dos (Planned Improvements)

The following improvements are planned to enhance the functionality, maintainability, and user experience of this game:

###  Technical Improvements

####  Refactor with Object-Oriented Programming (OOP)
- Use classes such as `Game`, `Player`, and `Challenge` to organize the code better and support future extensions.

####  Scoreboard and File Handling
- Save player names and scores using `fstream` for persistent tracking across game sessions.

####  Add More Encryption Types
- Implement additional cipher techniques to add variety and complexity:
  - ROT13 Cipher
  - Atbash Cipher
  - XOR Cipher

####  Input Validation and Error Handling
- Validate all user inputs (e.g., length, characters) and handle invalid cases gracefully with meaningful error messages.

####  Game Replay & Menu Navigation
- Allow players to:
  - Replay the game after finishing
  - Change game modes or difficulty
  - Exit cleanly without restarting the program

---

###  Gameplay and UX Enhancements

####  Countdown Timer Per Round
- Introduce a timer using `ctime` to limit the response time for each challenge, increasing difficulty and engagement.

####  Use a Real Word Bank
- Replace randomly generated characters with real 4-letter words from a text file for a more meaningful and educational experience.

####  Multiplayer Mode
- Add support for two players to take turns and compete, with a scoreboard to display results and declare a winner.

####  Develop a Graphical User Interface (GUI)
- Convert the console game into a GUI application using:
  - Qt or SFML
  - Improved visuals, buttons, and feedback

####  Add Inline Comments and Code Documentation
- Comment each function and logic block to make the code easier to read, understand, and maintain.
