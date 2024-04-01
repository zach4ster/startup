# startup
## Elevator Pitch
There are plenty of tictactoe games online, but I want to make a version that lets you play with other people online and keeps track of your record. 
## Key Features
To play on the website, users will have to make an account with an email and a password. They will be able to play games with other people, and a database will keep track of everyone's wins, losses and ties. There will be a leaderboard displaying the best players on the site. 
##  Technologies
#### Authentication
I plan to implement authentication in my site by requiring players to sign up with an email and password.
#### Database Data
The site will display each player's record. 
#### WebSocket Data
My site will have a leaderboard that updates in real time.
## Wireframe
![Homepage](https://github.com/zach4ster/startup/assets/156482224/d50228d2-3b32-427c-9952-a23d21281266)
![Signup](https://github.com/zach4ster/startup/assets/156482224/4fb0644d-dbeb-42d2-b4c9-9b2ff5417fd6)
![Login](https://github.com/zach4ster/startup/assets/156482224/48c3ba7f-3786-4c66-a8e2-147150f98cd6)
![TicketList](https://github.com/zach4ster/startup/assets/156482224/0b515287-4053-4318-ae8d-bc03938c6270)
![Checkout](https://github.com/zach4ster/startup/assets/156482224/3211c4d8-e906-4ca2-b9b4-b901914e336f)
## HTML Deliverable
For my HTML deliverable, I added the basic structure of my startup
*HTML Pages: 6 HTML pages (index, homepage, band, band_view, profile, shows)
*Links: The login page links directly to the homepage. The homepage links back to the login page through a logout link and to each of the other pages. All the other pages contain a logout link and a link back to the homepage
*Text: The login page has a welcome message and a small mission statement
*3rd party service: The homepage has a dropdown menu place holder for a third party chat function
*Images: The profile page has a placeholder image that the user will provide when creating their account
*Login: The login page has a placeholder that allows a user to inout their name and then be directed to the homepage
*Database: The band_view page has a table that is standing in for an element that will list the bands made on the site along with some info about them and any openings they have
*Websocket: The shows page has a table that is standing in for an element that will have a live list of shows that bands on the site are involved in with information about them and possible openings for other acts.
