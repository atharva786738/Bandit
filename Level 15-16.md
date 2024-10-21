# Level 15->16

**OBJECTIVE:** The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL/TLS encryption.

_helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage._

**COMMAND:** `ncat --ssl localhost 30001` 

1. after entering the command, enter the password for this level (8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo)

2. system identifies the correct password and returns with the next password

**PASSWORD:** kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx