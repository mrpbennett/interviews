# task

```bash
p=1024
s='MTc3ODUxOTA5NDYzMw=='
domain='gtm-env.vercel.app'

curl -s "https://api.somedomain.com/users?p=$p&s=$s" \
  --header "Referer: $domain"
```
### Question:

Using the above curl command, how would you test a list of 10 domains with the same values? What steps could you take to achieve this? Could you share your screen and show us within a text editor?
