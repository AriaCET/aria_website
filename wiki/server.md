# ARIA Server

Web interface to control asterisk. Nodes can be authenticated and groups can be configured.

## Installing

The server can be installed as a systemd/init.d/upstart service.

    #!/bin/bash
    $ git clone git@github.com:AriaCET/aria-server.git
    $ git checkout release
    $ ./install SYSTEMD   #for install as systemd service

## Dependencies
 - Python 2
 - Asterisk
 - Python-Flask
