# Asterisk RadIo Archetecture

__ARIA__ is an attempt to build a broadcasting system over local network which is flexible. Originally developed for in house use at [College of Engineering, Trivandrum](http://cet.ac.in). The [source code for aria is available in Github](https://github.com/AriaCET).
ARIA is highly flexible and can be addressed by each node if one wishes so. It has four parts.

 - [Asterisk server](/asterisk.html) at the center of the system.
 - A [web interface to control the server](/server.html) and the grouping of nodes.
 - A [transmitter client](/client.html).
 - [Speaker nodes](/ipspeaker.html)

ARIA streamlines managing of a network based public addressing system in an organisation. It uses the Asterisk Telephony server at the back and uses SIP/RTP protocols for data transfer.

ARIA server doesn't do any magic of itself. It is simply an abstraction of the asterisk paging system so that users can manage it without messing with the asterisk configuration scripts.

## Installing Aria

The infrastructure consists of a server,client and speaker nodes.

### Server
It should be powerfull enough to handle the amount of traffic the system will generate. Install [Asterisk](/asterisk.html) and [Aria Server](/server.html) onto this.

### Client
The transmitter end, install [Aria client](/client.html) onto this.

### Nodes
Setup a node and configure it in the web interface (Or use a linphone deamon).
