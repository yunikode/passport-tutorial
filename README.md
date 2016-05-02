# passport-tutorial

To run the server you need to create the cert/key pair called `my.crt` and `my.key`

## For a simple self-signed key
```openssl req -x509 -nodes -days 365 -newkey rsa:1024 -out my.crt -keyout my.key```
