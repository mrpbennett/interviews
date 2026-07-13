## Task 1

[SQL Tests](https://tam-sqltests.vercel.app/)

10 SQL tasks to complete. This shouldn't take more than 5-10mins to finish

## Task 2

```txt
https://upright-devotion-sterility.ngrok-free.dev
```

`GET /users`

| Query param | Required | Values                  | Effect                                      |
| ----------- | -------- | ------------------------ | -------------------------------------------- |
| `active`    | no       | `true` or `false`         | filter by state (`active` vs `blocked`)      |
| `country`   | no       | any string, case-insensitive | filter by country                        |


All questions use the `/users` endpoint.

-  Q1 — Pull only active users
-  Q2 — Pull only users from one of the following countries: `england`, `usa`, `spain`, `china`, `india`, `russia` or `brazil`, case-insensitively
-  Q3 — Combine both filters: `active` users from the country `england`

## Task 3

```bash
p=1024
s='MTc3ODUxOTA5NDYzMw=='
domain='gtm-env.vercel.app'

curl -s "https://upright-devotion-sterility.ngrok-free.dev/users?p=$p&s=$s" \
  --header "Referer: $domain"
```

**10 Domains**
```
"cloudpetal.io"
"frostbyte.dev"
"nomadledger.com"
"vaultspring.net"
"hexdrift.co"
"pinewave.org"
"irongate.app"
"lunarstack.dev"
"quickmarsh.net"
"emberflow.io"
```
### Question:

How would you test the list of the domains above with the same curl command and variable values, what steps could you take to achieve this? 
Can you share your screen and show us within a text editor? Or tell us the logic you may use to achieve the end goal.

You have full creative freedom. No need to test the code!
