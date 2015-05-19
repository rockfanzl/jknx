# jKNX: Jave home automation server and visualization #

The jKNX home automation visualization tool exists of two separate components:

  1. The jKNXcore: this is a pure Java application that is connected to the KNX home network. The core captures all messages on the KNX bus and is able to put any kind of message on the bus. Its main functionality is to keep track of the state of all the actors and sensors on the bus, trigger light switches, set heating modes, etc.

  1. The jKNXweb application: this is a JSP/Javascript based web application that provides a user interface to the jKNXcore. It communicates with the web browser through HTTP. The web applications itself communicates with the jKNXcore through web sockets.