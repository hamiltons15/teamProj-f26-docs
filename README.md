# cps490-26f-team21-docs

## Team Roster:

_Ash Ahmed Abdullah F AlHarbi_
- GitHub: AshAlharbi

_Sebastien Finch_
- GitHub: SebasFinch

_Sean Hamilton_
- GitHub: hamiltons15

_Jeremy Sowder_
- GitHub: sowderj1

---

## Pathway Selection:

- Option 2 (Original MERN Stack Project)

---

## Pathway Concept:

- A sports networking application that sets out to provide users with a personalized sports dashboard, multiple sporting updates, and user interaction based on team affiliation through online public group messaging. The different sporting leagues that would be featured include the NFL, NBA, MLB, and UFC. Users will also be permitted to register and maintain identifiable accounts. The application will display lists of scores/results for games/events in multiple sporting leagues. The users will also be able to join global group messaging chats for games/cards between two teams/fighters. Lastly, the application will provide an easily usable user interface where registered users can send and receive messages from other users.

---

## Preliminary Scope:

- Opening Documentation
- Implementation of Graphical User Interface (GUI): the personalized sports dashboard which will display scores, results, upcoming events. Allowing for filtering by the specific sport that we implement
- Implementation of score tracking capabilities: retrieving info from an external sports data source, display available scores, and handling incomplete or unavailable information
- Implementation of messaging capabilities: authenticated users join specific chatrooms that correlate to the sport and team they choose. They will be able to send and receive messages, and retrieve persisted discussion history
- Final Documentation

### Scope and feasibility: 
This is more than a static site because it combines authenticated accounts, user preferences, external API integration, persistent messages, and interactive communication. Technical challenges include authentication, sports data integration, database relationships, message delivery, and front/backend coordination. Our four person team will build incrementally, prioritizing a functional MERN foundation, authentication, personalized dashboard, sports data integration, and event-based messaging. Additional features and a polished UI will depend on testing results and time.

---

## Pathway-Specific Acknowledgement:

### How will it use the MERN Stack:

MongoDB: Persistent user accounts, favorite teams, global discussion rooms, message history.
Express: Implement backend API routes for authentication, sports data, and messaging. Also validating requests and enforcing access restrictions. 
React: Building an interactive login, registration, dashboard, and discussion interfaces. Also, will update views as the data changes, like new messages or updated scores. 
Node.js: Run the backend server and Express app, communicate with Mongodb, retrieve sports data, and help support front/backend communication.

---
