# File-Server-with-Retransmission-Security

>This is a ReadMe to understand project info.

---

### Table Of Contents

- [Description](#description)
- [Process](#process)
- [Techonologies and Languages](#languages)

---

## Description

In the project, it is necessary to create a client / server application that is used to send a large file in blocks with retransmission support.

A protocol consisting of two parts, Control and Transfer, has been developed.



### [Back To The Top](#File-Server-with-Retransmission-Security)

---

## Process

- The server has a predefined IP address and port number and is waiting for a client to connect.Basically clients are authenticated.
- Control protocol includes: Starting a session, Generating Session key and IV (counter for counter mode), Getting file data (block count, etc.), Requesting a missing block, Ending a session
- The transmission protocol is used to send and receive a particular block.
- Each block must be encrypted separately using the session key.
- A command line interface is provided for sending commands for the command protocol.
- It can be assumed that the sender has a public key and is known to the clients. 


### [Back To The Top](#File-Server-with-Retransmission-Security)

---

## Techonologies & Languages

- Jupyter Notebook ( which is a web-based interactive development environment for Jupyter notebooks, code, and data)
- Python ( programming language )


### [Back To The Top](#File-Server-with-Retransmission-Security)

---



