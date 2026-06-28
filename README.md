# OperatingPlatforms
Portfolio Submission from my Operating Platforms class.

Client and Software Requirements Summary:
The client was The Gaming Room. They wanted to design a web-based game called "Draw It or Lose It" where teams compete to guess stock images over a one minute round. The software requirements include creating unique names and id numbers for all games, teams, and players while ensuring exactly one instance of the game managing service exists.

Documentation Successes:
The documentation provides a clear evaluation of how different platforms like Linux, Mac, Windows, and mobile devices handle server and client requirements. It also gives specific, practical recommendations for storage, memory management, and security features. This details how all aspects of the application must work together holistically.

Value of the Design Document Process:
Working through the design document outlines the requirements and constraints clearly before code development begins. Defining the domain model and using class inheritance helps avoid redundant code across the game, team, and player entities. It also ensures that critical structures like the Singleton design pattern are planned early to manage memory effectively.

Areas for Revision and Improvement:
I would choose to revise the system architecture section because it currently notes that nothing is required for the project. I would improve it by adding a completed logical topology to describe the communication and storage aspects of the application. This would provide a helpful reminder and a complete view of the system and subsystem components.

Interpreting and Implementing User Needs:
The user needs were interpreted by focusing on the web-based nature of the application and the requirement to handle multiple users interacting at the same time. These needs were implemented by selecting a Linux 64-bit architecture to handle concurrent processes and choosing WebSockets to ensure precise timing. Considering user needs is important because it ensures the game functions properly on various client screens and protects user data from security attacks.

Software Design Approach and Future Strategies:
The software design was approached by using a UML diagram to map out classes and establish relationships between the game service, games, teams, and players. In the future, I would use a Singleton design pattern as a strategy to ensure unique instances and save memory. I would also use a relational database strategy to manage persistent storage and maintain unique identities among all entities.
