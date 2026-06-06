# PortSwigger JWT Lab 1

Lab:
JWT Authentication Basics

Steps Performed:

1. Logged in using provided credentials.
2. Opened Burp Suite.
3. Intercepted requests.
4. Located session cookie.
5. Identified JWT token.
6. Decoded token.
7. Analyzed header and payload.

Observations:

Header:
- alg: RS256

Payload:
- iss: portswigger
- sub: wiener
- exp: expiration timestamp

Result:

Successfully identified and analyzed a JWT token.
