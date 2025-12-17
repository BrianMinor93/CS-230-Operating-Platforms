# CS-230-Operating-Platforms
Module 7 Requirement

CS 230 – Module Eight Portfolio Reflection

Project: Draw It or Lose It (Web Edition)
Client: The Gaming Room

Client and Software Requirements Summary

The client for this project was The Gaming Room, a game development company seeking to expand their existing Android-only game, Draw It or Lose It, into a browser-based, multi-platform application. Their primary goal was to reach a broader audience by supporting desktop and mobile users through a web-accessible solution. Key software requirements included supporting multiple games, teams, and players; enforcing unique names for each entity; and ensuring that only one instance of the game service runs at any time. The design needed to be scalable, platform-independent, and structured in a way that could later support a web API and persistent storage 


Strengths in the Documentation

One area I handled particularly well was creating a clear and organized domain model that accurately represented the client’s requirements. The use of inheritance through a shared Entity base class, along with encapsulation of identifiers and names, resulted in a clean and maintainable design. I also effectively applied design patterns, specifically the Singleton pattern for the game service and the Iterator pattern for enforcing name uniqueness. These choices demonstrated both technical understanding and the ability to justify design decisions in a way that could be communicated to both technical and nontechnical stakeholders 

Value of the Design Document Process

Working through the design document before focusing on code was extremely helpful. The process forced me to think through system behavior, constraints, and relationships ahead of time instead of solving problems reactively in code. By defining requirements, constraints, and the domain model early, implementation became more straightforward and intentional. This approach reduced rework and helped ensure the final solution aligned closely with the client’s expectations.

Areas for Revision and Improvement

If I were to revise one part of the documentation, I would expand the system architecture section. While the assignment guidelines did not require a detailed architecture diagram, adding a high-level web architecture view (such as clients, load balancers, services, and databases) would improve clarity and make the document more complete as a real-world design artifact. This enhancement would better prepare the design for future implementation and scaling.

Interpreting and Implementing User Needs

User needs were interpreted by closely aligning the system design with how players and teams interact with the game. Requirements such as unique game and team names, multi-player support, and consistent system behavior were directly reflected in the domain model and service logic. Considering user needs is critical because software that does not align with user expectations—even if technically correct—will ultimately fail. Designing with the user in mind ensures usability, reliability, and long-term success.

Software Design Approach and Future Strategies

My approach to software design emphasized incremental modeling, starting with requirements, followed by constraints, domain modeling, and platform evaluation. In future projects, I would continue using this structured methodology while also incorporating additional techniques such as early prototyping, architectural diagrams, and threat modeling. These strategies would further strengthen analysis and ensure that both functional and nonfunctional requirements are addressed early in the design process.
