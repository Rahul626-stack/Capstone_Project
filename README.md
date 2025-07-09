# d-app-expense-tracker
I am Manas Dhote
for the solidity
the feature I am choosing is to get total no of registered users the codefix is below
#function getUsers() public view returns (uint256) { 
    #return registeredPeople.length;
    #}
    for app.js also i am showing total registered people
    here are snippet i am adding
    #<p>Total Registered Users: {people.length}</p>
    also added a header
    #<h3>People ({people.length} registered)</h3>
    I have uploaded the text file
   
update added fetchusers function in app js to call solidity getUsers function.
(note I am not taking the console error into consideration)
In app js I have changed the theme for a cleaner UI.
