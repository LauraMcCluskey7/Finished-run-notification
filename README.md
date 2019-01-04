# Finished-run-notification

## Description
This code is used to update the user when a run is complete, by sending them an email via Trello.

## Run
1) Create a Trello account
https://trello.com/en-GB

2) Create a board in Trello

3) Add a list to this board

4) To get an API key and API token for the Trello account use:
https://developers.trello.com/v1.0/reference#understanding-nested-resources
You must be logged in to the Trello account when getting this API key and API token.

5) To get the idList (https://customer.io/actions/trello/):
- create a card in the list on Trello
- click on this card then type ".json" after its url and press enter 
- the output will contain the value for the idList


6) Insert the API key, API token and idList into the relevant places in the code 

7) Run:
   python addcard.py [--runid]
   
   Options:
   --runid     : enter the id of the run
 
 


