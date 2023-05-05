## What is OSI model ?
 OSI stands for Open Systems Interconnection. It is conceptual framework for understanding how computer networks communicate with each other.
 It is divided into seven layers, each of which represents a different aspect of network   communication. All these 7 layers work collaboratively to transmit the data from one person to another across the globe.

## 7 Layers of OSI 

1. Physical Layer:
The lowest layer of the OSI reference model is the physical layer. This layer is responsible for the physical transmission of data over the network. The physical layer contains information in the form of bits. When receiving data, this layer will get the signal received and convert it into 0s and 1s

 2. Data Link Layer:
This layer is responsible for error-free transfer of data between two devices on the same network. When a packet arrives in a network, it is the responsibility of the DLL to transmit it to the Host using its MAC address

3.  Network Layer :
The network layer works for the transmission of data from one host to the other located in different networks. . It determines the shortest path for data to travel from one network to another and ensures that it arrives at its destination. The sender & receiver’s IP addresses are placed in the header by the network layer. 

 4. Transport Layer:
This layer is responsible for end-to-end delivery of data between applications on different devices. The data in the transport layer is referred to as Segments. It provides a reliable way to transport data by breaking it down into segments and reassembling them at the receiving end.

 5. Session Layer:
This layer is responsible for the establishment of connection, maintenance of sessions, and authentication, and also ensures security.   It enables two applications to establish a connection and exchange data in a structured manner. 

 6. Presentation Layer:
This layer is responsible for data formatting and conversion between different formats. It ensures that the data is presented in a way that is understandable by the receiving application. For example, ASCII to EBCDIC and Encryption/ Decryption.

 7. Encryption/ Decryption:
This layer is responsible for providing services to applications running on different devices. These applications produce the data, which has to be transferred over the network.
Example: Application – Browsers, Skype Messenger, etc.

