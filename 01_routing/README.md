# Server-side Routing

## Compare to multiple domains routing

- Avoids browser security issues (CORS)
- Enables sharing data like login-state through cookies
- Better performance (only one DNS lookup, SSL handshake, …)

Pros
- allows applications to be loosely coupled.
- one application goes down, the others are unaffected.

Cons
- applications can only communicate with each other through "links".
- difficult to manage common parts such as headers.
