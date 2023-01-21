# J.A.R.V.I.S

JARVIS is a simple program i've made in my free time. It is a personal home assistant inspired by the Tony Starks J.A.R.V.I.S

**SYSTEMS OVERVIEW**
restAPI - in charge of protocols and how to redirect requests to the IO
compute - responsible for computing the response
database/ - contains all of the keywords and their associated values

**IO**
client - a simple user interface to
display - screen - a simple TV display screen
sound-speak - responsible for handling speech, music, sound effects, etc.

---
**_To Run_**

#### Start end user client
> `cd ./client/`  
> `python3 ./server.py`

#### Start JARVIS IO output display screen
> `cd ./display-screen/`  
> `npm start`
