# Another Method to Start Server

const server = require('http').Server('app');

server.listen(3030);


# Another method to res.send()

res.status(200).send("Hello World");

# To Create A Room Id

We need to install 'uuid' package for this purpose which generates random ids for meeting room.
