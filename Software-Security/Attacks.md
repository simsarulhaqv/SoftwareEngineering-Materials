## Architectural/Design level attacks

####Man in the middle attack
* This is an attack, that is caused because of design flaws. Here a third person will be able to get the message between two people and is able to alter the message.

####Race condition attack
* A race condition occurs when a device or system try to execute two or more operations at the same time, but one those can only be executed sequentially.
* Defense is to use a lock or by differentiating atomic and non-atomic operations.

####Reply attack
* Here a valid data is retransmitted or delayed.
* Defense is to keep a sequence identifier.

####Session Hijacking attack
* This exploits the web session control mechanism. It exploits a valid computer session to gain unauthorized access to information in a system.

####Sniffer attack
* A sniffer is an application that can capture network packets. If the network packets are not encrypted, the data within the network packet can be read using a sniffer.
* Defense is stronger encryption.


## Implementation level attacks

####Buffer overflow attack
* Input recieved at buffer is overflown

####Back door attack
* Back door was implemented deliberately for administrators to fix issues.

####Parsing error attack
* Getting access to unintended location.
* Defence is to have a valid set of inputs, only which the application can accept. Nothing else should be used to get access to unintended information.


## Operation level attacks
* (Caused because, not tested in a proper environment)

####DoS Attack (Deniel of service)
* High frequency requests come to application, and fail to handle.

####Default Accounts attack
* There will be default easly guessable usernames and passwords like admin (pass: admin).

####Password Cracking attack
* Passwords are cracked in various ways.
