Steps for building and running the project (in Node.js):

1.Open Webstorm , select the folder with the project downloaded from github .

2.Select path for compile the project for Node.js and npm , Node.js must be installed.

3.Run project in Webstorm.


Implemented functionalities:

1.Message Channel (Messaging Systems): possibility to send and receive messages using the message broker.

2.Content Enricher (Message Transformation): the time and data of creation is added to all mesages.

3.Dead Letter Channel (Messaging Channels): the message are stored in an external JSON file so the messages may be received when the receiver comes online.

4.Message Translator (Messaging Systems): the plain string is transformed to JSON for storing data.

5.Polling Consumer (Messaging Endpoints): a receiverof this peak will receive a message, will be able to process and pass on to the next message.


Screenshots of results:

1.The broker is on.

![] https://github.com/Panfill/PAD-Lab1/issues/5#issue-508887301
