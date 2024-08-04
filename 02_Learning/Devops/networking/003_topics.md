# Network HOP
Trip a piece of data takes to go from one internet node to another on the way to its destination.

# Three way handshake
Three-step method employed by TCP to establish a secure client-server connection. Data packets with the flags SYN , SYN-ACK, and ACK are exchanged). This method is executed before any exchange of data occurs.

***Step 1. SYN:** Client Sends a message to the Server to that it would like to begin a message exchange.*
***Step 2. SYN + ACK:** Server sends a message to the client that it has received the request is ready to receive data.*
***Step 3. ACK:** The client sends a data packet indicating it is about to send data. A connection has been established.*

# DNS(Domain naming system)
**(DNS) domain name system:** A hierarchical naming system used for translating a human-readable domain name into an IP Address. A DNS server will take the domain name a client sends to it and returns the IP Address for that server.

---

**==Socket==:** A logical communication endpoint for an application formed when combining the IP address and port number.Example: 66.249.75.195:83
**==Port==:** Logical endpoint for data to be sent within a device. Port numbers are associated with web browsers and other internet-communicating web applications.

---

**TLS handshake:** Method in which a client and server:

- Agree on the TLS version to use
- Agree on the _ciphers_ to use within a _cipher suite_
- Exchange keys for symmetric encryption
- Verify the validity of a host’s certificate

**Cipher**: Set(s) of steps for performing encryption and decryption

**Cipher Suite**: A set of ciphers

This method performs the following steps:

- Step 1. `ClientHello`: Client specifies the TLS version and cipher suites it supports, and then sends to the server.
- Step 2. `ServerHello`: Server verifies it can use the specified TLS version and cipher suite. It provides its certificate and public key, and then sends `ServerHelloDone`.
- Step 3. Key exchange: The client and the server exchange key data for symmetric encryption.

