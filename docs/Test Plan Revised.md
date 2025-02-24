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

The engine of the game's creation does not need to be tested for in this test plan.


UNIT TEST
---------

### UNIT TEST STRATEGY / EXTENT OF UNIT TESTING:

Evaluate new features and bug fixes introduced in this release. 
(Specify the properties of test environment: hardware, software, network etc.)

### UNIT TEST CASES

| \#  |          OBJECTIVE          |                   INPUT                    |         EXPECTED RESULTS        |   TEST DELIVERABLES   |
| --: | --------------------------- | ------------------------------------------ | ------------------------------- | --------------------- |
|  1  | Check procedural generation | Wave function collapse feature             | Generated game world functions  | Playable game world   |
|  2  | Check puzzle solvability    | Puzzle coding + procedural generation      | Generated puzzles can be solved | Game can be completed |


REGRESSION TEST
---------------

Ensure that previously developed and tested software still performs after change.

### Regression Test Strategy

Evaluate all reports introduced in previous releases.

### Regression Test Cases

| #   |     OBJECTIVE      |       INPUT       |         EXPECTED RESULTS         |      OBSERVED      |
| --: | ------------------ | ----------------- | -------------------------------- | ------------------ |
|  1  | Game can be run    | Developer feature | Game runs without issue          | Game runs          |
|  2  | Game can be edited | Developer feature | Game can be edited without issue | Game can be edited |


INTEGRATION TEST
----------------

Combine individual software modules and test as a group.

### Integration Test Strategy and Extent of Integration Testing

Evaluate all integrations with locally developed shared libraries, with consumed services, and other touch points.

### Integration Test Cases

| #   | OBJECTIVE | INPUT | EXPECTED RESULTS | TEST DELIVERABLES |
| --: | --------- | ----- | ---------------- | ----------------- |
|  1  |           |       |                  |                   |
|  2  |           |       |                  |                   |


USER-ACCEPTANCE TEST
--------------------

Verify that the solution works for potential user. Include the method (e.g.,
heuristic, performance measures, thinking aloud, observation, questionnaire, 
interviews, etc.), the number of participants and demographics, the concent
form, *scenarios*, scripts to read, and data collection methods.

### User-Acceptance Test Strategy

(Explain how user acceptance testing will be accomplished.)

### User-Acceptance Test Cases

| #   | TEST ITEM | EXPECTED RESULTS | ACTUAL RESULTS | DATE |
| --: | --------- | ---------------- | -------------- | ---- |
|  1  | User can finish game               | Game should be able to be completed | To be determined | To be determined |
|  2  | Time taken for user to finish game | Variable                            | To be determined | To be determined |


Test Deliverables
-----------------

(List test deliverables, and links to them if available, including the following.)

-   Test Plan (this document itself)
-   Test Scripts
-   Defect/Enhancement Logs
-   Test Result Reports


Schedule
--------

(Provide a summary of the testing schedule, specifying key test milestones, 
and/or provide a link to the detailed schedule.)

Risks
-----

-   (If any risks have been identified, list them here.)
-   (Specify the mitigation plan and the contingency plan for each risk.)


Appendix
--------

(Include any information that is helpful to reference.)
