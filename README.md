docker-node-red
===============

Node-RED in a docker container

Node-RED is the coolest thing ever.

But wait - Docker is the coolest thing ever.

What happens when you put them together??? DARE WE?

We dare.

The default port is 1880. Be aware I've had issues making this work thru a proxy (nginx) - I think it's a websockets kinda thing, if you know what to do lay it on me. 

This is most for messing around - todo is to figure out and document the right way to save data in
persistent volumes. 

Run this with "docker run -d -p 1880:1880 bortels/node-red" for top fun!
