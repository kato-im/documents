HTTP POST API
=============

Sample POST:

    curl -X POST -d @element.json https://api.kato.im/rooms/{Kato room-specific URL}/simple --header "Content-Type:application/json"

##Input

###Required
-  __"text":__ message content to be pushed to the Kato room.

###Optional
-  __"from":__ who is sending the message into the room.
-  __"color":__ the background color of the message. Can be any html color.
-  __"renderer":__ how the message is displayed, can be default or markdown.

###JSON object format:
element.json

    {
        "from": "Walter",
        "color": "red",
        "renderer": "markdown",
        "text": "@Donny, you're out of your **element!**"
    }

##Response (needs to be updated)

    HTTP/1.1 200 OK
    Content-Type: application/json; charset=utf-8
