# PREMIER LEAGUE LEGENDS FANTASY TEAM

# Brief

The overall objective of this project was to create a CRUD application with the utilistation of supporting tools, methodologies and technologies that encapsulates all the core modules that has been covered during my training. 

For this project I decided to create a fantasy football app that would have a database of premier league legends. This app would allow the user to create multiple teams and save them, as well as editing their current teams or deleting them.

# Entity Relationship Diagrams (ERD)

As shown in my ERD there are three tables. There is a 1 to 1 relationship between the team table and users table, becuase a team can only be assoicated to one user. Whilst there is a many to many realtionship between the user and the teams table becasue a user can create mutliple teams and save each one. This allows for a more intersting user experience allowing the user to create a variety of different teams. There is a 0 to many relationship between the teams table and the players table, because not every player will be selected in a team, whilst there are more than 2 players that will be sleect for the fanatsy 5 a side. Lastly there is a 1 to many relationship from the players table to the team table this is becuase a team cannot be created with out at least 1 player.


# Built with
* MySQL - Database
* Python - Source Code
* GitHub - Version Control System
* Trello - Project Tracking
* Jenkins - CI server
* Pytest - Testing
* Azure - Live Environment
