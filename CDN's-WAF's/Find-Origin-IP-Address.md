# Ways to find the Server's Real/Origin IP address:

## Passive
 - DNS Records
 - CIDRs
 - SSL Certificates
 - Favicon Hashes
 - Shodan, Fofa, Censys, SecurityTrails

## Method
 - Shodan: `ssl.cert.subject.CN:"domain/subdomain"`
 - Fofa: normal search for target domain/subdomain
 - Censys: normal search for target domain/subdomain
 - SecuirtyTrails: normal search for target domain/subdomain


## Active
- XML/RPC Pingbacks
- Virtual Hosts
- Google Analytics
- Re-captcha Identifier Keys
- Custom Headers

Read more:
- https://infosecwriteups.com/finding-the-origin-ip-behind-cdns-37cd18d5275
