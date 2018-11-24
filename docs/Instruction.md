Project A: design and implement a chatting tool with reliable data transfer using UDP.
With this chatting tool, two programs on different hosts can send messages to each other. The applications should exchange messages using UDP.
 
Minimum requirements for chatting tool: 
(1) Basic UI. There are basic UI that allow users to do the operations. 
(2) Support both text/emoji/picture. Users should be able to send both text, emoji and picture.
(3) Support file transfer. The file should be correctly and completely delivered to the receiver. The file directory and name could be chosen by the receiver. Both users should know the progress of the file transfer. 
(4) Support chatting history; A user can find their chatting history.

Minimum requirements for reliable data transfer: since the program is based on UDP, you have to implement some mechanisms for reliable data transfer.
(1) Handshake; 
(2) Go-back-N or Selective Repeat; 

Minimum requirements for experiments:
(1) You should conduct experiments on transferring different size of files (from bytes to MB). 
(2) You should design experiments to show that your reliable data transfer mechanisms work.

Bonus: multi-users chatting room with multiple users chat at the same time. 