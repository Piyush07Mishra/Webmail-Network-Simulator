# Webmail Network Simulator

## Run it
1. Extract the ZIP (if downloaded as ZIP).
2. Open `index.html` in Chrome, Firefox, or Edge.
3. Edit sender, recipient, subject, and message body.
4. Click **Run simulation** to animate the whole flow, or **Next step** to advance manually.
5. Use Reset to restart.

No server, package installation, API key, or internet connection is required. This is a front-end educational simulation; it does not send real email or collect credentials.

## Concepts visualized
- Browser to webmail application over HTTPS
- Authentication and send request
- Mail preparation, queue and mailbox storage
- DNS MX lookup and A/AAAA hostname resolution
- SMTP server-to-server transfer
- TCP's reliable transport role
- Receiving mail checks and storage
- Recipient webmail fetch and display
- SMTP, DNS, HTTPS, TCP, IMAP and POP3 reference cards

## Accuracy note
The diagram is a simplified teaching model. Real providers use distributed systems and internal services. Webmail can access provider mailbox storage directly; IMAP/POP3 are primarily relevant to compatible external email clients. Traditional HTTP/1.1 and HTTP/2 use TCP, while HTTP/3 uses QUIC over UDP. SMTP server-to-server delivery commonly uses TCP port 25; authenticated message submission commonly uses port 587.
