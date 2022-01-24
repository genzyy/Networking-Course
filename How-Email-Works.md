<div align=center>
  <h1>How Email Works</h1>
</div>

## Email Protocols

- SMTP (Simple Mail Transfer Protocols) => Used to send emails.
- POP3 (Post Office Protocol 3) or IMAP (Internet Message Access Protocol) => Used to receive emails.
- This takes place in `Application Layer`.
- This connection is `TCP/IP` connection because we don't want to lose our emails.

## Flowchart

- Sender => mail went to SMTP server => Receiver's server => Receiver.

- `NOTE`: We can try to use `nslookup` command if you are on unix based operating system. Run this command to check IP Address of a **gmail.com** server,

```zsh
$   nslookup --type=mx gmail.com
```
  or 

```zsh
$   nslookup gmail.com
```


- The POP3 service runs on port `110`.


## Flowchart of client connecting to POP server

- Client => Authorize => POP Server
- Client <= Transact <= POP Server


## IMAP (Internet Message Access Protocol)

- This is known as Internet Message Access Protocol.
- This allows us to receive emails on the same address but view them on different devices.
