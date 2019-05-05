# SriRepo
This code requires 3 JSON files user.JSON, ticket.JSON and organisation in the C:\Homework directory. Create a homework folder in the C: drive and place the user.JSON,ticket.JSOn and organisation.JSON given in the previous email

If you want to replace the location , change it in the DataSearch.java class (the 3 variable which stores this are stJSONFile stJSONFIleUsers, stJSONFileTickets and run the mvn clean install command to get the zen-1.0.jar

navigate to the bin directory and run the search.bat

There are 3 options like how its mentioned in the doc

option 1 allows to search in zendesk
option 2 displays all the various search fields
option 3 will end the loop

after clicking on option1 , there are 3 options, a,b,c

a for users, b for tickets, c for organisation

after clicking on the option, the search criteria and search values needs to be entered. Please enter the search criteria and search value.

If worng search criteria field is entered it skips and returns to main menu
If wrong search value (the ones not present in JSON) is entered then it returns null and returns to main menu
