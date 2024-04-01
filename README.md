# IPK-Projekt24
## Author: Dominik Václavík ( xvacla37 )
Project was implemented with C and **works only on Linux**
Body of program is splitted into several files:

 - main.c
 - input.c
 - globals.c
 - tcp.c
 - udp.c
 - utils.c
 - message_id_stack.c
 - defines.h
 ### main.c
 Handles arguments parsing.
 ### input.c
 Handles all input from *stdin*. Program reads all data from input till new line and stores them into buffer. Data overreaching buffer size are thrown away.
 ### globals.c
 Handles allocation of memory for global variables and their disallocation. All global data are stored in one struct.
 ### tcp.c
 Handle TCP all connection.
 ### udp.c
 Handle UDP all connection. 
 ### utils.c
 Contains logics for comparing strings.
 ### message_id_stack.c
 Contains expansive stack for message IDs.
 ### defines.h
Contains defines.
