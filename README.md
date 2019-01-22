# Transmit-binary-file-via-UDP-protocol
This is a sender and receiver program, where the sender accepts a file as a command line parameter, 
breaks it into smaller chunks, and sends it to the receiver using UDP. The receiver will concatenate 
the pieces it receives and will store it to a file on its end. There will be at least 12 datagrams 
sent by the sender to the receiver. Both sender and receiver will write out a detailed log of what 
they are doing on the console.

This was an assignment in a Networks and Security class. All descriptions and details of functions
are written out in the source code. Included is a test image file to use, or you can use your own. 
