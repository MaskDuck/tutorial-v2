# Bots with Admin

Giving bots the administrator permission in your server is almost always a bad and dangerous idea, for several key reasons:

1. In the case of a token leak your bot has the permissions to do anything in all the servers it is in. This means it can ban all members, remove all of the channels, post illegal material, anything.
2. If *you*, the developer, make a mistake while programming the bot which causes your bot to - for example - remove all channels in a server by accident. People make mistakes, no matter how skilled or competent they are, and at some point having admin will cause issues when you make one of those mistakes. You can try as hard as you like not to make mistakes but they are inevitable and *will* happen.
3. In general a best practice for security is the principle of least privilege. This means that nothing should have more privileged than it needs to operate, and it is highly unlikely that your bot actually warrants the administrator permission to function correctly.

A common argument in favour of using this permission is "if you're careful with your tokenb and make sure it never gets leaked it's fine." No. As mentioned in point 2 people make mistakes. You are the weakest link in the security chain, and you have the capability to break it.
