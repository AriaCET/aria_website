
# Linphone Deamon

Linphone package provides `linphonecsh` a deamon mode to run linphone. This can used for our overhead speakers as following.

         # Intialize the deamon
         $ linphonecsh init

         # Register the node
         $ linphonecsh register --host <host> --username <username> --password <password>

         # Enable the autoanswer mode
         $ linphonecsh generic 'autoanswer enable'

It also supports few configuration instructions.

        # Soundcard configuration
        $ linphonecsh soundcard list
         0: ALSA: default device
         1: ALSA: HDA Intel PCH
         2: PulseAudio: default

        # set the playback to 1st soundcard.
        $ linphonecsh soundcard playback 1

### References
 - https://www.linphone.org/eng/documentation/guide/linphonecsh-control.html
 - http://manpages.ubuntu.com/manpages/precise/man1/linphonecsh.1.html

