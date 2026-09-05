The Users table stores both organisers and participants. An organiser can create and manage many events, while a participant can enter many events.

The Events table stores the main event information, such as the event name, date, location, and organiser. Each event can have many Categories,
such as a 5 km, 10 km, or cycling category.

Participants enter events through the Enrolments table. This table connects the participant, event, and selected category.
It resolves the many-to-many relationship between participants and events.

Each enrolment can have one result, which is stored in the Results table. Results include the participant’s finish time, position, and result status.

Finally, each event can have one Weather record and one Route record. These provide participants with weather and route information before race day.

Overall, the relationships allow RaceDay to connect organisers, events, categories, participants, enrolments, and results in one organised database.
