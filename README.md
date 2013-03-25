This is a proof of concept project to build a frontend web interface for the PayMeBack application.
All sections will need to be consumer facing complete, but backend interaction will be non-functional in this stage.

Website should have the below minumum functionality to be considered complete:
- [ ] Home page with application information and minimalist marketing.
- [ ] Account creation page that takes input for email, password, first/last name, phone number (this page will send POST to backend).
- [ ] Login page (this will query backend for matching user/pass and take the user to their landing page).
- [ ] Landing page should be built such that mock data can be replaced by dynamic GET data (mock-up of possible landing page for specific user, this will display various sections of user-specific information).
- [ ] Transaction page that allows user to add monetary transaction between 1 or more people. Calculations will default to even split, but can manually set values for each individual as long as total is correct (data from this page will combine POST and GET from backend to display current known users, calculate transaction, and add totals to the backend accounts).

TODO:
- [ ] Hash out other page ideas.