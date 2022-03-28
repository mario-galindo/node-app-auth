## Authentication using HTTPS client certificates
### Stack: node.js

```
curl --insecure --cert bob/bob.p12 --cert-type p12 https://localhost:9999/authenticate
```
```
curl --insecure --cert alice/alice.p12 --cert-type p12 https://localhost:9999/authenticate
```
### Resources
[Authentication using HTTPS client certificates](https://medium.com/@sevcsik/authentication-using-https-client-certificates-3c9d270e8326)<br>
[Client Certificate Authentication (mTLS) with Node.js](https://github.com/julie-ng/nodejs-certificate-auth)<br>
[Postman Client Certificates](https://stackoverflow.com/questions/27501819/how-to-add-a-client-side-pkcs12-certificate-to-postman-chrome-w7)
