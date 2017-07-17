## ScURL
### Jordan Ebel


This script clones command line cURL functionality, supporting
HTTPs only.  

Help information:

```
Secure cURL implementation, Jordan Ebel

positional arguments:
  url                   Request URL

  optional arguments:
    -h, --help            show this help message and exit
    -v                    be verbose
    --tlsv1.0             use TLS v1.0
    --tlsv1.1             use TLS v1.1
    --tlsv1.2             use TLS v1.2
    --sslv3               use SSL v3
    -3                    use SSL v3
    --ciphers CIPHERS     cipher list
    --crlfile CRLFILE     CRL file
    --cacert CACERT       CA Cert
    --allow-stale-certs STALECERTS
                          CA Cert
     --pinnedpublickey PINNEDPUBLICKEY
                          pinned public key
```


Supported TLS/SSL versions:

* SSL v3
* TLS v1.0
* TLS v1.1
* TLS v1.2

