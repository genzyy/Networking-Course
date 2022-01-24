<div align=center>
  <h1>Structure Of Network</h1>
</div>


# Structure of Network

- In this section we will learn the models that are used in today's networking technology and their layers.


## OSI Model

- It stands for Open Systems Interconnection Modal.
- There are 7 layers in this model:

                - Application Layer
                - Presentation Layer
                - Session Layer
                - Transport Layer
                - Network Layer
                - Data Link Layer
                - Physical Layer


### Application Layer

- It is implemented in the application itself.
- This is the only layer the user directly interacts with.
- Some protocols used are HTTP, FTP, etc.
- The application layer will give data to next layer which is Presentation Layer.


### Presentation Layer

- This layer handles encryption, encoding, translation, etc of the data received by the application layer.
- This layer assumes that the next layer which is Session Layer will convert the data by itself for further processing.
- SSL (Secure Socket Layer) is used for encryption and encoding in this layer.


### Session Layer

- This layer focuses on setting up the connection and managing it and then enabling processing of data followed by termination of the connected sessions.
- This layer assumes that the next layer which is transport layer will send the data once the connection is established.


### Transport Layer

- This layer divides the data into segments which have a sequence number attached to them to align them sequentially in the received device.
- This layer has `Flow Control` which manages the upload speed of the sending device according to the receiving device so we do not lose any data packet during the data sending process.


### Network Layer

- This layer takes data segments from transport layer and then transports it from uploading device to the downloading device.
- Router is a part of network layer.
- The function of this layer is logical addressing.


### Data Link Layer

- This takes data packet from network layer and does logical address and physical addressing.
- MAC Address is used for physical addressing.
- A frame is the data unit that is has the MAC Address to it added by the data link layer.
- After creating these data frames, all the above layers can access these frames and control how they are placed and received.
- Adds MAC Address to frames or data segments received from network layer.


## Flowchart

- This flow shows how a packet goes layer by layer from uploading device to downloading device.

- Application => Message formed by the user and this layer sends it to presentation layer.
- Presentation => Transports the message by modifying it (encoding, encrypting, decrypting, etc).
- Session => Creates a connection between devices and sends the message to transport layer.
- Transport => Makes the message into packets and segments and sends it to network layer.
- Network => Bundles and assigns IP Addresses to packets and sends it to Data Link layer.
- Data Link => Adds MAC Address to the received frames and sends it to physical layer.
- Physical => Sends the data to physical router.

## Real World Example

- ME => A => P => S => T => N => D => P => Router => P => D => N => T => S => P => A => MY FRIEND.



## TCP/IP Model

- Internet Protocol Suite.
- This model has 5 layers:
                  - Application Layer
                  - Transport Layer
                  - Network Layer
                  - Data Link Layer
                  - Physical Layer

- The working of the layers is same as OSI Model but with few exceptions.
- OSI model's Application, Presentation, Session are merged together into Application.
- This is used practically and OSI is used for theory and concepts.
