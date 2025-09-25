# vulnerabilities-scan
My report on host 192.168.240.1 identifies a high-severity vulnerability: untrusted SSL/TLS certificates on ports 443/60443 and 8834. The self-signed and private CA certificates break the chain of trust, making the host susceptible to man-in-the-middle attacks. The fix is to replace them with certificates from a publicly trusted CA 
