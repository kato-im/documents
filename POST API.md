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
    
All parameters but text are optional.
-  color is any html color
-  renderer can be default or markdown.
