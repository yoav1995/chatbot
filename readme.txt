1.)
on this assignment i have built a python console application.
the user is asked to enter a prompt. 
this prompt needs to be something that the user thinks is scriptable, and after the user sends his request, a query is sent to chat gpt.
if the query is somthing that the chat gpt is able to write script for- the response will be the script itself, else a proper message will be sent.
at last, the script will be written into script.py file in order to check what the machine result was, and will be executed.

2.) 
during this work iv'e tried to use different engines of chat gpt3, and used the open ai api key.

3.) 
my conclution is that engine "text-davinci-002" is the best for this mission.
i also found that some queries does not bring the exact result i wished for, the reason is that 
the machine needs a special query for the best result, and choosing the best engine is also important.


----- to run this app, 2 installs are requiered: open ai api, and python-dotenv -----

 
example for some queries and results:


queries that worked: 

1.) open youtube in chrome and search "the beatles"
 engine="text-davinci-002"

2.)open youtube in chrome and search "dance monkey"
 engine="text-davinci-002"

3.)open youtube in chrome browser
engine="text-davinci-002"

in that case it opened youtube on edge and not on chrome
when i used "text-davinci-001" it didn't open a thing and wrote:
bufsize must be an integer


queries that didn't work:

1.) open chrome browser
engine="text-davinci-002

2.)open youtube in chrome and play the most viewed video
engine="text-davinci-002
