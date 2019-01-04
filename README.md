# Finished-run-notification

1) Create a trello account
https://trello.com/en-GB

2) Create a board in trello

3) Add a list to this board

4) To get an API key and API token for the trello account use:
https://developers.trello.com/v1.0/reference#understanding-nested-resources
You must be logged in to the trello account when getting the API key and API token.

5) To get the idList (https://customer.io/actions/trello/):
- create a card in the list on trello
- click on this card then type ".json" after its url and press enter 
- the output will contain the value for the idList


6) Insert the API key, API token and idList into the code into the relevant places in the code 

7) Run:
   python addcard.py [options]
   
   Options:
   --runid     enter the id of the run
 
 


