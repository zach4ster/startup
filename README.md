# startup
## Elevator Pitch
Students that have a ROC pass pay for it with the expectation that they will be able to attend enough sporting events to get the full value out of it. The reality is that even if they do meet the cost, no student is able to attend every game that the pass qualifies them for. This has resulted in a market for selling tickets obtained through ROC passes and even ROC passes themselves through the BYU Snapchat stories and Venmo. Students interested in purchasing tickets this way have to go through the process of adding a stranger on Snapchat and hoping that the offer is legitimate before sending them money. The same is true for the seller except that they have to take the risk of sending the ticket to a stranger without knowing if they will get paid; in either scenario, someone is taking a risk. I want to take the risk out of the equation by setting up a website accessible only to BYU students where they can post listings for tickets and others can purchase them securely with the confidence that they will get what they are paying for. This concept exists as a facebook group but lacks the security I want to implement. 
## Key Features
The website I plan to build will be accessible through students' BYU emails to maintain a level of exclusivity and security. It will include the option for sellers to choose thier own prices as well as the value of the ticket they are selling based on the current average sales price, secure payment options that support Apple Pay, Venmo, Zelle, card numbers etc., messaging options so that buyers can haggle with sellers, and an intuitive and attractive user interface. Additionally, there will be minimal banner ads to offset costs and hopefully generate some passive income. 
##  Technologies
#### Authentication
I plan to implement authentication in my site by requiring buyers and sellers to sign up with a BYU email and password linked to their profile.
#### Database Data
The site will have an option to review past transactions that will be stored in a database, as well as a list of upcoming events. 
#### WebSocket Data
My site will allow buyers and sellers to chat and negotiate prices. Additionally, there will be a section with listings that potential buyers can navigate and estimated values for tickets based on the current average price paid for tickets of the same kind. 
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