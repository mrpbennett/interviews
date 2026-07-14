# Interview tasks

These tasks are here for you to complete to measure your skill level, these are not a pass or fail but more to help us gauge where you are at with your current skill level.

## Task 1

Please visit [SQL Tests](https://tam-sqltests.vercel.app/) to get started with 10 SQL querying tasks.

## Task 2

- BaseURL: `https://upright-devotion-sterility.ngrok-free.dev`
- Endpoint: `GET /users`

| Query param | Required | Values                  | Effect                                      |
| ----------- | -------- | ------------------------ | -------------------------------------------- |
| `active`    | no       | `true` or `false`         | filter by state (`active` vs `blocked`)      |
| `country`   | no       | any string, case-insensitive | filter by country                        |


All questions use the `/users` endpoint.

-  Q1 — Pull only active users
-  Q2 — Pull only users from one of the following countries: `england`, `usa`, `spain`, `china`, `india`, `russia` or `brazil`
-  Q3 — Combine both filters: `active` users from the country `england`

## Task 3

```bash
p=2026
s='cHVsc2Vwb2ludGlzYXdlc29tZQ=='
domain='cloudpetal.io'

curl -s "https://upright-devotion-sterility.ngrok-free.dev/domains?p=$p&s=$s" \
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

What thought process would you use to test the list of the domains above with the same curl command and `p` / `s` variable values, what steps could you take to achieve this? 

Can you share your screen and show us within a text editor? Or tell us the logic you may use to achieve the end goal.

You have full creative freedom. If you want to write a script and test be our guest.
