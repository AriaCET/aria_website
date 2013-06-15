# Asterisk RadIo Archetecture

__ARIA__ is an attempt to build a broadcasting system over local network which is flexible. Originally developed for in house use at [College of Engineering, Trivandrum](http://cet.ac.in). The [source code for aria is available in Github](https://github.com/AriaCET).
ARIA is highly flexible and can be addressed by each node if one wishes so. It has four parts.

 - [Asterisk server](/parts/asterisk) at the center of the system.
 - A [web interface to control the server](/parts/server) and the grouping of nodes.
 - A [transmitter client](/parts/client).
 - [Speaker nodes](/parts/ipspeaker)

ARIA streamlines managing of a network based public addressing system in an organisation. It uses the Asterisk Telephony server at the back and uses SIP/RTP protocols for data transfer.

ARIA server doesn't do any magic of itself. It is simply an abstraction of the asterisk paging system so that users can manage it without messing with the asterisk configuration scripts.

## Installing Aria

The infrastructure consists of a server,client and speaker nodes.

### Server
It should be powerfull enough to handle the amount of traffic the system will generate. Install [Asterisk](/parts/asterisk) and [Aria Server](/parts/server) onto this.

### Client
The transmitter end, install [Aria client](/parts/client) onto this.

### Nodes
Setup a node and configure it in the web interface.