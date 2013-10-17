HTTP POST API
=============

Kato allows users to integrate their own notifications using the HTTP POST method.
You can POST with application/json content type to your Kato room-specific URL.

JSON object format:
    
    {
        "from": "Walter",
        "color": "red",
        "renderer": "markdown",
        "text": "@Donny, you're out of your **element!**"
    }

###Required
-  __"text":__ message content to be pushed to the Kato room.

###Optional
-  __"from":__ who is sending the message into the room.
-  __"color":__ the background color of the message. Can be any html color.
-  __"renderer":__ how the message is displayed, can be default or markdown.
