# cloudflare-dns-updater
A PowerShell script that demonstrates how to update records in CloudFlare DNS.

PLEASE NOTE: Original script created by June Castillote (https://adamtheautomator.com/cloudflare-dynamic-dns/).

Updated by Justin Braun to support multiple host names.

# Sample usage

.\cfdns_updater.ps1 -email 'user@domain.net' -token 'token' -domain 'dnszonename' -record '<record1.domain.net>,<record2.domain.net>'
