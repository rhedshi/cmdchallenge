### extract_ip_addresses/

```bash
# Extract all IP addresses from files that start with "access.log" printing one IP address per line.
(0)> grep -Ehor '((25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)' --include access.log*
```
