# Sales Force Learning
Sales Force Example to connect to Google Maps and show Accounts that are in same city..
A very badly written code. Needs to be optimized later. 

Requirement: Show Accounts Address in Google Map. Also Plot the Accounts that are in same city in different colored markers. 

Implementation: 
Create Visual Force Page. It does the following:
1. Get the current Account Record and Plot in Google Map
2. Fetch Account adddresses in the same city and plot in the google map. 

This example was created when in a sales force training session and is used to create quick demo.. Has many bugs + areas of improvement.. in it like: 
- The same record id is plotted twice. 
- Unwanted alert messages
- Used salesforce js component to fetch the related accounts. 
