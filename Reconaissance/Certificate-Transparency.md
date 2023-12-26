# Certificate Transparency Logs

Sources:
- Censys
- Shodan
- Certspotter
- crt.sh
- Facebook
- Google
- Cerstream (Calidog)

#### Censys
Look for SSL certificates:
```
443.https.tls.certificate.parsed.extensions.subject_alt_name.dns_names:<"root-domain.com">
```
```
parsed.ssl.certificate.serial_number:<certificate_serial-number>
```

#### Shodan
```
ssl.cert.subject.CN:"<root-domain.com>"
```
```
ssl.cert.serial:<certificate_serial-number>
```
