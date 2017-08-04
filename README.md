# Description
- Useful python script to test tls connection
 
## API Management Version Compatibilty
This artefact can be used with every API Management Plus version


## Install
- Copy the .py file on the server
- Generate the key and the certificate in the directory where the script is submitted : openssl req -newkey rsa:2048 -keyout ssl.key.pem-x509 -days 365 -out ssl.crt.pem

## Usage
```python pyhttpsserv.py```
Listen on port 8443 and list all files of the directory where the script is submitted
For tests without TLS, just submit ```python –m http.server```
   
## Bug and Caveats
Nothing identified

## Contributing

Please read [Contributing.md](https://github.com/Axway-API-Management-Plus/Common/blob/master/Contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Team

![alt text][Axwaylogo] Axway Team

[Axwaylogo]: https://github.com/Axway-API-Management/Common/blob/master/img/AxwayLogoSmall.png  "Axway logo"


## License
[Apache License 2.0](/LICENSE)
