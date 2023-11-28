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
443.https.tls.certificate.parsed.extensions.subject_alt_name.dns_names:root-domain.com
```

#### Shodan
```
ssl.cert.subject.CN:"root-domain.com"
```