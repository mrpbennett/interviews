# task

```bash
p=1024
s='MTc3ODUxOTA5NDYzMw=='
domain='gtm-env.vercel.app'

curl -s "https://api.somedomain.com/users?p=$p&s=$s" \
  --header "Referer: $domain"
```
