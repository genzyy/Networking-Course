<div align=center>
  <h1>Protocols</h1>
</div>

- In this section we will be learning about what are protocols and how many types of protocols are used and what are they.

# Protocols

- In networking, a protocol is a set of rules for establishing a connection and then processing the data through that connection.
- Let's have a situation in mind, there is `Company X` which provides email service with their own protocol and then there is `Company Y` which also provides email service with their own protocol.
- Now in today's world, we already know that we can send message from our gmail account to some other non-gmail account. But if we go with the above situation, we would have not be able to send email to accounts of email service providers that are different to ours.
- This is why today we have some protocols that are being followed by every company, client and servers. This way we have standardize the rules to provide any service on the internet to anyone.

- On the Internet, there are different protocols for different types of processes. Protocols are often discussed in terms of which OSI model layer they belong to.

- Below is a list of web protocols that are important to know and are followed.


## TCP/IP

- This protocol is `Transmission Control Protocol/Internet Protocol`.
- If you want to learn more about this protocol now, you can go [here]() or if you are following it by index, then don't worry we will be going to cover it in the course.
- For now, we can know that TCP is a stateful connection meaning it preserves the state and gives feedback about the packet if it is received or not.
- There are various sub protocols or TCP that are followed and are listed below.

    - HTTP (Hyper Text Transfer Protocol)
    - DHCP (Dynamic Host Configuration Protocol)
    - FTP (File Transfer Protocol)
    - SMTP (Simple Mail Transfer Protocol)
    - POP3 (Post Office Protocol 3)
    - IMAP (Internet Message Access Protocol)
    - SSH (Secure Socket Shell)
    - VNC (Virtual Network Computing)


### Telnet

- A terminal emulation that enables the user to connect to a remote host or device using the telnet client.
- It runs on port 23 (Just know this for now. We will cover ports later).
- The data processed is neither encoded nor encrypted.


## UDP

- This Protocol is `User Datagram Protocol`.
- This is a stateless connection meaning no state is preserved for the processed data and this does not collect any feedback about if the data got lost in between transmission or not.


## Sockets

- This is the interface between the process and internet.
- We can visualize sockets as the socket which we have in our home where we connect the wire of our Landline.


## Ports

- These are addresses to identify applications running on a device.
- Just like we have IP Addresses to identify unique devices, we have port or port addresses to identify unique applications on a device.
- Let's say we have multiple instances running of an application, then it assigns random port numbers to it so it can recognize which instance needs what. These are known as Ephemeral Ports.
- Once the process is done the port will be freed.


## HTTP

- HTTP means Hyper Text Transfer Protocol.
- A client-server protocol that tells us how we request data from the servers and how it will send us that data.
- This is an application layer protocol.
- HTTP is TCP protocol.
- HTTP is a stateless protocol and will not save any state.


## Status Codes

- Status codes are 3 digit numerical strings which are passed as feedback to the data processed.

- 100 to 199 are the informational responses means they give information about protocol switching and mainly connection related information.
- 200 to 299 are Success code responses that tells us the request succeeded.
- 300 to 399 are redirectional code responses meaing they give information about the relocation or redirectional url of the current address.
- 400 to 499 are client error code responses which gives error information on the client side.
- 500 to 599 are server error code responses which gives error information about the server side connection issues.


## Cookies

- These are unique user strings which are stored in the browser.
- Cookies are used to get the state of the user on a website.

### Third Party Cookies

- These are the cookies which are set for the URLs that we do not visit.
