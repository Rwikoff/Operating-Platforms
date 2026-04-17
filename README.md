# Project Portfolio: Software Design & Architectural Migration

CLIENT SUMMARY AND REQUIREMENTS

The client, The Gaming Room, requested a comprehensive software design to migrate their existing Android game, "Draw It or Lose It," into a scalable, multi-platform web application. The core requirements focused on scalability to accommodate a growing player base and data integrity to ensure unique naming conventions for games, teams, and players. Technically, the design mandated the use of the Singleton pattern for centralized game management and an inheritance hierarchy to streamline the codebase.

DOCUMENTATION STRENGTHS

I believe I was particularly effective in articulating the Domain Model and the application of Object-Oriented Programming (OOP) principles. By clearly defining how the Entity base class provides a template for Game, Team, and Player objects, I demonstrated how inheritance and encapsulation reduce redundancy and improve system maintainability. Additionally, the platform evaluation table provided a balanced look at the trade-offs between Windows, Mac, and Linux, justifying the final recommendation with clear technical and financial reasoning.

THE DESIGN-TO-CODE PROCESS

Working through the design document was incredibly helpful for visualizing the structural dependencies before writing a single line of code. Identifying the need for the Iterator pattern during the design phase ensured that I had a concrete plan for enforcing unique naming constraints. This proactive approach prevented "logic gaps" that often occur when jumping straight into development, as the relationships between the GameService and individual entities were already mapped out.

AREAS FOR REVISION

If I were to revise one section of this documentation, I would expand on the Storage Management strategy. While the current document recommends a Relational Database (RDBMS), I would improve it by including a detailed Entity-Relationship Diagram (ERD) or a more granular comparison between SQL and NoSQL options. This would provide the development team with a clearer path for database schema implementation and data migration from the original Android version.

INTERPRETING USER NEEDS

I interpreted the user’s needs by translating high-level business goals—like "unique naming"—into specific technical constraints, such as the use of long-integer IDs and collection traversal logic. It is critical to consider the user’s needs during the design phase because it ensures the final product is both functional and intuitive. For example, failing to account for network latency in a distributed environment would lead to a poor user experience, regardless of how robust the backend logic is.

SOFTWARE DESIGN APPROACH

My approach to software design is centered on modularity and the "fail-fast" philosophy. I prioritize creating independent, reusable components that can be tested in isolation. In the future, I plan to use UML (Unified Modeling Language) diagrams more extensively to analyze similar applications. Visualizing the flow of data through sequence and class diagrams allows for a more rigorous analysis of how different modules interact, which is essential for building stable, professional-grade distributed systems.

