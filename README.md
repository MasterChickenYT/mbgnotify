# mbgnotify
A simple client/server based notification service.

mbgnotify (working title) is a notification service, that works on three layers:

1. A Raspberry Pi Zero with a touchscreen is going to be the "sender". Information inputted on it
will be sent over a 3G/4G connection or Ethernet to...

2. the server, which is a Raspberry Pi (3B+ in my case, but can be anything), which recieves the information,
decodes the variables, makes all of the nessecary changes to the message (such as adding an ID for reception confirmation)
and sends it at speciefied times to...

3. the clients phone over an app. The interface will only be used for setup and connection testing.


At least for now, that's my goal, more features will be added once coding on the foundations is done.
