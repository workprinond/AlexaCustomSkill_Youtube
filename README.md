# AlexaCustomSkill_Youtube

This is A custom made alexa skill to stream youtube videos.

Bugs discovered:

1) To use this project stream youtube in it make sure your alexa device language is tuned to en-usa.

2) To avoid a specific kind of error like  

{ "type": "INVALID_RESPONSE", "message": "SpeechletResponse was null" }
 
 use this response:

{
    "version": "1.0",
    "sessionAttributes": {},
    "response": {
        "shouldEndSession": true
    }
}


Requirements:

ASK CLI

AWS account

AWS developer account

AWS Management console

Node.js v:12

Intellij IDEA

