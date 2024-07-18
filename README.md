# Install-webserver-website
The project is useful for anyone who want to create enviorments, support solutions, and collaborte with other engineers.
The 3 tier architecture is modern and the most prevalent projects useful to show a clear separation of the application into specific tiers. Not only does it provide the greatest level of separation it promotes scalability, maintainabily and flexibilty.

Presentation Tier: The user interface where the end-user interacts with the system (website).
Logic Tier: The middle tier of the architecture, also known as the logic tier, handles the application’s core processing, business rules, and calculations.
Data Tier: Manages the storage, retrieval, and manipulation of the application’s data, typically utilizing a database.

The fundamental principle of a 3-tier application is the flow of information and requests through the tiers. In this project I built the system first on paper then with the offical aws icons and mapped out the flow of information from layer to layer. I listed all the parts of the system and labeled them all with their own  ip addresses, and if they were present, I also listed the security groups around them. I labled the internet gateway and made it face the public subnet so it can reach the internet. The database is in the private subnet. There is no Nat Gateway there isnt a way for the db to reach the internet. Once I installed the software on the server, saved the server creds and added the contents to the file I was able to see the form on the appear on screen.




