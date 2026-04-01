[[Web Security]]

**OWASP ZAP** is a powerful **web vulnerability scanner and proxy**.

Docker is great because the install is messy otherwise.

Run headless scanner:

```
docker run -t owasp/zap2docker-stable zap-baseline.py -t https://example.com
```

Useful for:

- automated web scans
    
- CI security testing
    
- recon during bug bounty