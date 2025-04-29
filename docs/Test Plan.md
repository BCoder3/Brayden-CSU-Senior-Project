IDENTIFICATION INFORMATION
--------------------------

### Product

- **Product Name:** Puzzle Heart Video Game

### Project Description

Puzzle Heart is a video game that revolves around solving puzzles in a procedurally generated, digital world. 
Its purpose is for entertainment and to challenge the user's problem-solving abilities.

### Testing Objectives

The purpose of the Puzzle Heart video game study is to evaluate the
problem-solving skills required to complete the game, with every playthrough
being timed. Test users will be instructed to complete the game to the best
of their ability and as fast as they can. Test operators will also be given a
short survey to complete after their experience for feedback purposes.

### Features to be Tested

The running state of the Puzzle Heart video game is the main feature to be tested. 
Within this facet of the project there are many other subfeatures to be tested, 
such as ensuring that the procedural generation of the world does not hinder 
the flow of gameplay, and to ensure that every puzzle is sovlable.


### Features Not to Be Tested

The engine of the game's creation does not need to be tested in this test plan.


UNIT TEST
---------

### UNIT TEST STRATEGY / EXTENT OF UNIT TESTING:

Evaluate new features and bug fixes introduced in this release. 
(Specify the properties of test environment: hardware, software, network etc.)

### UNIT TEST CASES

| \#  |          OBJECTIVE          |                   INPUT                    |         EXPECTED RESULTS        |     TEST DELIVERABLES     |
| --: | --------------------------- | ------------------------------------------ | ------------------------------- | ------------------------- |
|  1  | Check procedural generation | Procedural Generation code | Generated game world functions and map randomization | Playable game world |
|  2  | Check puzzle solvability    | Puzzle coding + procedural generation | Generated puzzles can be solved | Game can be completed |
|  3  | Check player movement       | W key press | Player avatar moves forward | Player can move forward |
|  4  | Check player movement       | A key press | Player avatar strafes left | Player can move left |
|  5  | Check player movement       | S key press | Player avatar moves backward | Player can move backward |
|  7  | Check player movement       | D key press | Player avatar strafes right | Player can move right |
|  8  | Check world interaction     | E key press | Player interacts with object | Player can interact |
|  9  | Check camera movement       | Mouse movement | Camera moves with mouse motion | Player can look around |
| 10  | Check option selection      | Left mouse button click | Player selects item desired | Player can select items |
| 11  | Check pause menu display    | Esc key press | Player opens pause menu | Player can open menu |
| 12  | Check player inventory      | I key press | Player opens inventory menu | Player can open inventory |
| 13  | Check timer on screen       | T key press | Game displays active timer | Player can engage timer |
| 14  | Game can be run             | Developer feature | Game runs without issue | Game runs |
| 15  | Game can be edited          | Developer feature | Game can be edited without issue | Game can be edited |
| 16  | Game can be edited          | Developer feature | Game can be edited without issue | Game can be edited |



USER-ACCEPTANCE TEST
--------------------

In order to test for User-acceptance, users designated to test the Puzzle Heart 
video game will be asked to complete the game at their own pace, and will be timed 
from the start of their gameplay to their completion of the game. This will be used 
to determine an average time of completion on the game itself, and users will then be 
surveyed on their experience of the game.

### User-Acceptance Test Strategy

The user will be informed of their goal to complete within the game, and then start the game. The game will always be able to be completed, and the only variable is the terrain that has been procedurally generated - including the seed of the world - and a timer that will record how long it takes for the user to complete the objective.

### User-Acceptance Test Cases

| #   |              TEST ITEM               |             EXPECTED RESULTS            |  ACTUAL RESULTS  |       DATE       |
| --: | ------------------------------------ | --------------------------------------- | ---------------- | ---------------- |
|  1  | User can finish game                 | Game should be able to be completed     | To be determined | To be determined |
|  2  | Time taken for user to finish game   | Variable by tester, around 8-12 minutes | To be determined | To be determined |
|  3  | User provides feedback on experience | Variable by tester, expecting positive  | To be determined | To be determined |


Test Deliverables
-----------------

-   Test Plan
-   Test Scripts are to be determined
-   Defect/Enhancement Logs are to be determined
-   Test Result Reports are to be determined


Schedule
--------

Schedule is to be determined

Risks
-----

-   Machine used to run the game for the intentions to complete the objectives of this test plan may be unfit in terms of hardware requirements for gameplay.
-   In order to mitigate this risk, both the game should be optimized to run on lower-hardware machines and the machine chosen to run the test cases should be fit     if possible


Appendix
--------

See Requirements Document for specifics on development process and the goals of this project.
