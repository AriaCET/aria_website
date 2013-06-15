# ARIA Server

Web interface to control asterisk. Nodes can be authenticated and groups can be configured.

## Installing

The server is installed as a systemd service.

    #!/bin/bash
    $ git clone git@github.com:AriaCET/aria-server.git
    $ git checkout release
    $ ./install

## Dependencies
 - Python 2
 - Asterisk
 - Python-Flask