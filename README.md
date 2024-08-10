# Install-webserver-website / brianprojects.com
The project is useful for anyone who want to create enviorments, support solutions, and collaborte with other engineers.
The 3 tier architecture is modern and the most prevalent projects useful to show a clear separation of the application into specific tiers. Not only does it provide the greatest level of separation it promotes scalability, maintainabily and flexibilty.

Presentation Tier: The user interface where the end-user interacts with the system (website).

 Bankend Tier: The middle tier of the architecture, also known as the logic tier, handles the application’s core processing, business rules, and calculations.

Infrastucture Tier: Manages the storage, retrieval, and manipulation of the application’s data, typically utilizing a database.

The fundamental principle of a 3-tier application is the flow of information and requests through the tiers. In this project I built the system first on paper then with the offical aws icons and mapped out the flow of information from layer to layer. I listed all the parts of the system and labeled them all with their own  ip addresses, and if they were present, I also listed the security groups around them. I labled the internet gateway and made it face the public subnet so it can reach the internet. The database is in the private subnet. There is no Nat Gateway there isnt a way for the db to reach the internet. Once I installed the software on the server, saved the server creds and added the contents to the file I was able to see the form on the appear on screen.


![image](https://github.com/user-attachments/assets/905c66f5-540d-4155-b144-66a06be3e896)

The infrastructure tier is the network and systems needed to support the webserver and database. In this project I am using the aws rds database and placingn it in a private subnet. While a ec2 will have software installed on it to host a Wordpress website on the public subnet. The ec2 will be facing and accessable to the internet while the database is secured with security groups or firewalls.

The backend tier of my project I have a apache server and mysql database both in separate subnets.

The presentation tier is the website that will host all my projects.
Brianprojects.com








