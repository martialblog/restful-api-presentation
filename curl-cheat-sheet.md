# cURL

cURL is a software package which consists of command line tool and a library for transferring data using URL syntax.

cURL supports protocols like, DICT, FILE, FTP, FTPS, Gopher, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMTP, SMTPS, Telnet and TFTP.

# Examples

Simple HTTP call
```bash
curl http://www.fau.de
```

Follow redirects
```bash
curl -L http://www.google.de
```

HTTP Authentication
```bash
curl -u username:password URL
```

HTTP GET Request
```bash
curl --request GET http://www.example.com
```

HTTP POST Request
```bash
curl --request POST http://www.example.com --data 'email=john@snow.com'
```

HTTP PUT Request
```bash
curl --request PUT http://www.example.com --data 'email=tyrone@lannister.com'
```

HTTP DELETE Request
```bash
curl --request DELETE http://api.example.com/users/john
```

