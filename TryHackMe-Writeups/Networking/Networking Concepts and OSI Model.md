## Learning Objectives

- **ISO OSI Network Model**
- **IP addresses, subnets and routing**
- **TCP, UDP and Port Numbers**
- **How to connect to an open tcp port from the command line**

## OSI Model

The OSI model is a conceptual framework that standardizes how data is transmitted across a network by dividing communication into seven layers.

**OSI meaning** : *Open Systems Interconnection*.

**Developed by** : *International Organization for Standardization*.

## OSI Layers

## Layer 1 - **Physical Layer**
- *The Physical Layer is responsible for the actual transmission of raw bits over a physical medium. It defines the electrical, optical, and mechanical characteristics required to send data between devices.*

**Example Protocols and Standards**

- *Electrical, optical, and wireless signals*
  

## Layer 2 - **Data Link Layer**
- *The Data Link Layer is responsible for reliable communication between devices on the same local network. It packages data into frames, adds addressing information (MAC addresses), handles error detection, and manages access to the physical medium so devices don’t “talk over” each other.*

**Example Protocols and Standards**

- *Ethernet (802.3), WiFi (802.11)*


## Layer 3 - **Network Layer**
- *The Network Layer is responsible for moving data between different networks. It handles logical addressing (IP addresses), routing, and determining the best path for data to travel across interconnected networks.*

**Example Protocols and Standards**

- *IP, ICMP, IPSec*


## Layer 4 - **Transport Layer**

- *The Transport Layer is responsible for delivering data reliably or unreliably between devices, depending on the protocol. It handles segmentation, reassembly, flow control, and ensures data is delivered in the correct order when required.*

**Examples of Protocols and Standards**

- *UDP, TCP*


## Layer 5 - **Session Layer**

- *The Session Layer manages and controls the connections (sessions) between two devices. It establishes, maintains, and terminates communication sessions to ensure applications can exchange data reliably and in an organized way.*

**Examples of Protocols and Standards**

- *RPC (Remote Procedure Call), NetBIOS, SQL session management, NFS sessions*


- ## Layer 6 - **Presentation Layer**

- *The Presentation Layer ensures that data exchanged between systems is in a usable and understandable format. It acts as a translator between the application and the network, handling data formatting, compression, and encryption.*

**Exampples of Protocols and Standards**

- *Unicode, MIME, JPEG, PNG, MPEG*


## Layer 7 - **Application Layer**

- *The Application Layer is the closest layer to the end user. It provides the interfaces and services that applications use to communicate over a network. This layer doesn’t refer to the applications themselves, but the protocols and services that support them.*

**Example Protocols and Standards*

- *HTTP, FTP, DNS, POP3, SMTP, IMAP*
