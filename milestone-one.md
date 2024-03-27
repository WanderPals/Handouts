## Overview
* Graded on working together as a team, organization and good practices
* Not graded on software testing and development

## Sprint 2
* Coaches will review PRs and give not graded feedback

## User flow - Trip Planning and Itinerary Creation
1. Sign in/up into the app
	* User enters the app by signing in or signing up.

	* [ ] Create a Logo (SP1: William)
	* [x] Implement Google authentication (SP1: Paul)
	* [ ] Create Login Screen and add tests (SP2: Paul)

2. Creating a New Trip
	* User selects the option to create a new trip.
	* User enters trip details (name, date range) and invites fellow travelers via email or app username, which creates a group linked to that specifc trip.

	* [ ] Create the Overview screen (SP2: Lorin)
	* [x] Navigation actions and navigation Bottom Bar (SP2: Matvey)
	* [ ] Creating Trip Creation Screen with inputs (SP2: Matvey)
	* [x] Create DataClasses (SP2 : Anton)
	* [ ] Link Trips Creating Screen to Dataclasses
	* [x] Setup Firebase (SP1: Anton)
	* [ ] Fetch and Push datas to Firestore (SP2: Anton)
	* [ ] Invite other users functionality / group creation

3. Exploring and Pinning Locations
	* Within the trip, users access the map feature to search for destinations, lodging, tourist attractions, and restaurants.
	* Users pin selected locations to the map, creating a visual representation of potential places to visit.

	* [ ] Creating Map Screen + Map API Setup (SP2 : Paul)
	* [ ] Search for destinations
	* [ ] Pins for visual display of dataclasses

4. Collaborative Itinerary Building
	* Group members suggest daily activities and places to visit through a suggestion feed integrated into the trip dashboard.
	* Members vote on suggestions using a like/dislike system and discuss details in the comments section under each suggestion.
	* The group finalises the daily itinerary based on the most liked suggestions and discussion outcomes.

	* [ ] Suggestion Creation Screen (SP2: William)
	* [ ] Suggestion Feed Screen (SP2: Wei)
	* [ ] Daily activities based on suggestions
	* [ ] Like/dislike System on suggestions
	* [ ] Finalised itinerary

5. Shared Agenda Creation
	* A shared agenda is automatically generated based on the finalized itinerary, detailing activities and locations for each day.
	* All group members can view the shared agenda, which includes times, dates, and locations.

	* [ ] Agenda Screen Display (SP2: Gabin)
	* [ ] Shared Agenda with group members
	* [ ] Shared Itinerary visible in the Agenda

## Expected Deliverables
- Figma of the main user flows
	* [x] User flows creation (SP1: Gabin)
	* [ ] Wireframes 
	- [ ] Mockups linked
	- [ ] Screen linking (between mockup screens)

* Architecture Diagram
	* [ ] Overall architecture of your application
	* [ ] Relations between its different screens, data sources, internal state, etc.

- Product backlog (Maintained is the responsibility of the Product Owner in any given sprint): 
	
	- [ ] High-priority user stories at the top

- Plan for Sprint 4
	* [ ] Create Tasks for Sprint 4

- A code repository with a configured CI
	* [x] Sonar Configuarition/Analyzed (SP1: Matvey)
	- [x] CI with Jacobo and Sonar (SP1: Matvey)
	* [ ] One End-to-end test
	* [ ] Good code coverage >80%

* Working, stable APK, bug-free
	* [ ] Generate an APK
	* [ ] Test one end-to-end user flow on a real phone with APK

* Scrum process documents
	* [ ] Analyze the way you're working together and to come up with reasonable solutions for whatever issues you've been facing as a team.
	* [ ] At least 1 documented stand-up per sprint
	* [ ] 1 sprint retrospective document per sprint
	* [ ] Put a link to it in your GitHub wiki for ease of access.


Furthermore, as an individual, you will need to submit:
- Individual retrospective per sprint (before the meeting with your coaches)
- The PRs you created (and were merged), at least 1 per sprint (2 by Milestone One)
- The PRs you reviewed, at least 1 per sprint (3 by Milestone One)

## Grading (10%)

### Group Grade
| Deliverables | Points |
| ---- | ---- |
| Figma / Screens, Wireframes, Linking | 25% |
| Architecture Diagram | 10% |
| Sprint Planning & Product backlog | 15% |
| Implementation (APK, CI, tests) | 40% |
| Sprint Retrospective | 10% |
| Total | 100% |

### Individual Grade
| Deliverables                          |  Points  |
|---------------------------------------|----------|
| (At least) 2 Code PRs                 |   10%    |
| Quality of PRs *                      |   30%    |
| 3 Code Reviews                        |   10%    |
| Quality of Reviews (Sprint 3 only)  |   10%    |
| Attendance                            |   10%    |
| Individual Retrospective              |   10%    |
| Task Ownership                      |   20%    |
| **Total**                             | **100%** |

## Quality of PRs and Reviews
* Not be about code quality

* Aligns with a given task's definition of done
* Clear goal and description
* Single purpose (i.e. not mixing 3 unrelated things in one PR)
* Constructive feedback
* Useful and humble suggestions
* Focused on the code, not the person
* Not missing serious, major flaws

## Task Ownership
* Taken responsibility for the tasks assigned to you
- Finishing the task yourself
- Asking for help in a timely fashion when you're stuck or unavailable
- Bringing up the challenges during the stand-up meeting (at the latest)
- Asking the coaches if your team is completely stuck and the teams' attempts have failed
- Raising serious blockers for discussion in the retrospective and/or planning
- Finishing what can be finished, and discussing a change of strategy/approach for what's left
