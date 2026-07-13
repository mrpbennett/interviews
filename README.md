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
-  Q2 — Pull only users from a country, case-insensitively
-  Q3 — Combine both filters: active users from a specific country

## Task 3

```bash
p=1024
s='MTc3ODUxOTA5NDYzMw=='
domain='gtm-env.vercel.app'

curl -s "https://api.somedomain.com/users?p=$p&s=$s" \
  --header "Referer: $domain"
```
### Question:

Using the above curl command, how would you test a list of 10 domains (these don't have to be real domains) with the same values? What steps could you take to achieve this? Could you share your screen and show us within a text editor?

#### Hint! 
Bash, Python.....AI
