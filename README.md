# Usage:

```yaml
rule-providers:
  roblox_domains:
    type: http
    behavior: classical
    format: yaml
    url: https://raw.githubusercontent.com/vrzdrb/clash_roblox_ip_domains/refs/heads/main/roblox-domains.yaml
    path: ./opencck/rule-domain_clash_rules.yaml
    interval: 86400
  roblox_CIDR4:
    type: http
    behavior: classical
    format: yaml
    url: https://raw.githubusercontent.com/vrzdrb/clash_roblox_ip_domains/refs/heads/main/roblox-ip.yaml
    path: ./opencck/IP-CIDR_clash_rules.yaml
    interval: 86400
```
